# Catstronauts

Catstronauts is a full-stack application used to demonstrate how to combine React, Apollo and GraphQL.

This application uses a "schema-first" design. That means features were implemented based on exactly which data our client application needs. Schema-first design typically involves three major steps:

<ol>
  <li><b>Defining the schema:</b> We identify which data our feature requires, and then we structure our schema to provide that data as intuitively as possible.</li>
  <li><b>Back-end implementation:</b> We build out our GraphQL API using Apollo Server and fetch the required data from whichever data sources contain it. This example uses mocked data.</li>
  <li><b>Front-end implementation:</b> Our client consumes data from our GraphQL API to render its views.</li>
</ol>

One of the benefits of schema-first design is that it reduces total development time by allowing front-end and back-end teams to work in parallel. The front-end team can start working with mocked data as soon as the schema is defined, while the back-end team develops the API based on that same schema.

A <b>schema</b> is like a contract between the server and the client. It defines what a GraphQL API can and can't do, and how clients can request or change data. It's an abstraction layer that provides flexibility to consumers while hiding back-end implementation details.


Full demo application from this course is available [live.](https://lift-off-client-demo.netlify.app/)

![Application homepage](https://raw.githubusercontent.com/nemanjarogic/catstronauts/main/client/public/homepage.png "Homepage")

## Run the project

Castronauts fullstack app holds two main folders `server` and `client`

### server

- Install packages `cd server && npm install`
- Start server `npm start`

The graphql server pulls data from a rest API holding the

### client

- Install packages `cd client && npm install`
- Start react app `npm start`


