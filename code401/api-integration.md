# Reading: API Integration

## Reading

- [Review API Server Build](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/api-server/)

1. Explain the different between a query string parameter and a path parameter.

   A path parameter determines where to look for the information, while the query parameter determines the different options for that path.

2. What would our API URL with a path id parameter be given the following information:

   1. Domain: `http://our-site.com`
   2. `v3`
   3. model name: `stuff`
   4. id: `things`

   http://our-site.com/v3/stuff?id=things

3. We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.

   The interface makes a request to the server that locates information in a database. Once it is found it sends that information back to the front-end.

- [Review Auth Server Build](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/auth-server/)

1. Describe how you would use middleware to implement basic and bearer auth.

   There is a basic auth middleware that takes in the two strings given and then compares it to the strings kept in storage. The bearer auth takes the JWT token and verifies it against the secret stored in the server. Once they are verified by one of the methods they can access the information in the server.

2. Describe the handshake necessary to implement OAuth.

   The browser initiates the handshake, and once granted permission it will send a get request to your server. The auth middleware then finishes the handshake.

3. Describe how Role Based Access Control works to a non-technical friend.

   Basically you create a set of roles that users are assigned. This gives them access to certain parts of your application based on the necessary functions of their job.
