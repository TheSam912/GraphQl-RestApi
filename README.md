GraphQL is a query language for APIs and a runtime for fulfilling those queries with your existing data. GraphQL gives clients the power to ask for exactly what they need and nothing more, makes it easier to evolve APIs over time, and enables powerful developer tools. Learn More

Some Terminologies involved in GraphQL
Query: A query in GraphQL is used to request data. It resembles the shape of the data you want to receive and is similar to a JSON object.
Mutation: Mutations are used for modifying data on the server. They are like queries but are used for creating, updating, or deleting data.
Schema: The schema defines the structure of your data in GraphQL. It includes object typesfields on those types and the relationships between them.
Type: In GraphQL, types define the shape of the data. There are two main types: Object types (representing real-world entities) and Scalar types (representing primitive data like String, Int, Boolean, etc.).
Field: A field is a specific piece of data that can be requested on an object type. Fields can also be nested to retrieve related data.
Resolver: Resolvers are functions that determine how to fetch the data for a specific field. Each field in your schema has a corresponding resolver.
Subscription: Subscriptions enable real-time data updates. Clients can subscribe to specific events, and the server sends data to the client when those events occur.
