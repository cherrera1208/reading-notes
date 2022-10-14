Readings: Express REST API
==========================

Readings
--------

[Review: ES6 Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)

1. Classes are a template for creating _____.
    * objects
2. Can a class declaration be hoisted?
    * no
3. How would you describe a constructor and contextual “this” to a non-technical friend?
    * a standard blueprint for an object. `this` relates to the method in the object that is used to construct the new instance

[Using Express Routing](https://expressjs.com/en/guide/routing.html)

1. Within Express, what does routing refer to?
    * how an application's endpoints (URIs) respond to client requests
2. What is the difference between a route path and a route method?
    * the path is what action is to be performed, e.g GET, POST, etc... and the method is the command that instructs the path to perform its task
3. When is it appropriate to add `next` as a parameter to a route handler and what must you do if `next` has been passed to your middleware as a parameter?
    * when there are multiple callback functions

[Express Routing](https://scotch.io/tutorials/learn-to-use-the-new-router-in-expressjs-4)

1. What is an Express Router?
    * is like a mini-Express app, provides us with routing APIs
2. By what mean do we initialize `express.Router()` in an express server?
    * `app.use()`
3. What do we use route middleware for?
    * `router.use`
