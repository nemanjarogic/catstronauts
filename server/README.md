# Catstronauts - server

A back-end side is responsible to:

<ul>
  <li>Receive an incoming GraphQL query from our client</li>
  <li>Validate that query against our newly created schema</li>
  <li>Populate the queried schema fields with mocked data</li>
  <li>Return the populated fields as a response</li>
</ul>

To test queries locally we can use [Apollo Studio Explorer](studio.apollographql.com/dev).
