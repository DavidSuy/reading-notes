# Readings: Express REST API

## Readings

### [Review: ES6 Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)

1. Classes are a template for creating \_\_\_\_.

   Classes are a template for creating objects.

2. Can a class declaration be hoisted?

   No, an important difference between function declarations and class declarations is that while functions can be called in code that appears before they are defined, classes must be defined before they can be constructed.

3. How would you describe a constructor and contextual “this” to a non-technical friend?

   The constructor method is a special method for creating and initializing an object created with a class and the contextual this in the instance of the new object created from the class constructor.

### [Using Express Routing](https://expressjs.com/en/guide/routing.html)

1. Within Express, what does routing refer to?

   Routing refers to how an application’s endpoints (URIs) respond to client requests.

2. What is the difference between a route path and a route method?

   A route method is derived from one of the HTTP methods, and is attached to an instance of the express class and route paths define the endpoints at which requests can be made.

3. When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?

   With multiple callback functions, it is important to provide next as an argument to the callback function and then call next() within the body of the function to hand off control to the next callback.

### [Express Routing](https://expressjs.com/en/guide/routing.html)

1. What is an Express Router?

   Express Router is a class to create modular, mountable route handlers. A Router instance is a complete middleware and routing system; for this reason, it is often referred to as a “mini-app”.

2. By what mean do we initialize express.Router() in an express server?

   A router object is an isolated instance of middleware and routes. You can think of it as a “mini-application,” capable only of performing middleware and routing functions.

3. What do we use route middleware for?

   We use route middleware to perform function on a specific route.

### Reflection

Express make building a server with nodejs quick and simple.
