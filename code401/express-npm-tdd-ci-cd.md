# Express, NPM, TDD, CI/CD

## Reading

### [An introduction to NodeJS and Express](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction)

1. Explain middleware, answer as though I were a non-technical recruiter.

   The middleware in node. js is a function that will have all the access for requesting an object, responding to an object, and moving to the next middleware function in the application request-response cycle.

2. Express the most popular \_\_ ** \_\_**.

   Express is the most popular Node web framework, and is the underlying library for a number of other popular Node web frameworks

3. Express is “unopinionated.” What does that mean?

   Express is unopinionated. You can insert almost any compatible middleware you like into the request handling chain, in almost any order you like.

4. What is a module and why is modularity useful to us as developers?

   A module is a JavaScript library/file that you can import into other code using Node's require() function. Express itself is a module, as are the middleware and database libraries that we use in our Express applications.

### [What is NPM?](https://docs.npmjs.com/getting-started/what-is-npm)

1. What version of npm are you running on your machine?

   8.19.2

2. What command would you type to install a library/package called ‘jshint’ into your node project?

   npm i jshint

### [What is TDD?](https://www.agilealliance.org/glossary/tdd/)

1. Explain why tests are important. Please explain as though I were your non technical elder.

   “Test-driven development” refers to a style of programming in which three activities are tightly interwoven: coding, testing (in the form of writing unit tests) and design (in the form of refactoring).

2. What are three expected benefits of testing

   - many teams report significant reductions in defect rates, at the cost of a moderate increase in initial development effort

   - the same teams tend to report that these overheads are more than offset by a reduction in effort in projects’ final phases

   - although empirical research has so far failed to confirm this, veteran practitioners report that TDD leads to improved design qualities in the code, and more generally a higher degree of “internal” or technical quality, for instance improving the metrics of cohesion and coupling

3. Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.

   Typical individual mistakes include:

   - forgetting to run tests frequently
   - writing too many tests at once
   - writing tests that are too large or coarse-grained
   - writing overly trivial tests, for instance omitting assertions
   - writing tests for trivial code, for instance accessors

   Typical team pitfalls include:

   - partial adoption – only a few developers on the team use TDD
   - poor maintenance of the test suite – most commonly leading to a test suite with a prohibitively long running time
   - abandoned test suite (i.e. seldom or never run) – sometimes as a result of poor maintenance, sometimes as a result of team turnover

### [CI/CD](https://www.youtube.com/watch?v=xSv_m3KhUO8)

1. What are three benefits of Continuous Integration?

   - Ensure everyone's changes integrate
   - Catch Bugs
   - Reduce merge conflicts

2. What is the difference between Continuos Delivery and Continuous Deployment?

   Continuous Delivery - Develop to release at any time

   Continuous Deployment - Develop new features immediately

3. Explain how GitHub fits into this process assuming the listener comes from a non-technical background

   Github puts your code at the center of your development ecosystem by serving as a clearing house that not only keeps track of changes, but also communicates with other systems about those changes using webhooks and APIs.

### Bookmark and Review

[nodeJS docs](https://nodejs.org/en/docs/)

[npm docs](https://docs.npmjs.com/)

[express docs](https://expressjs.com/en/4x/api.html)

[http status codes](https://expressjs.com/en/4x/api.html)

[supertest](https://github.com/visionmedia/supertest)

### Reflection

With Nodejs we can use Javascript to develope the backend with the same language. Making you be able to build full web stack app with just Javascript.
