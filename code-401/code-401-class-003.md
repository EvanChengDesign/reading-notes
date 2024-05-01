 **Reading Notes | 1 MAY 2024**

# Class 003

## **Questions & Answers**  
### JavaScript and Express Concepts

1. **Classes:** Classes are a template for creating **objects**.
2. **Class Declaration Hoisting:** No, a class declaration cannot be hoisted like functions. They must be declared before they are used.
3. **Constructor and Contextual "this":** A constructor is a special function in a class for setting up new objects, and "this" refers to the object where the code is currently being executed. Imagine it as setting up a new smartphone where "this" represents whichever phone is being set up.
4. **Express Routing:** Within Express, routing refers to determining how an application responds to a client's request to a particular endpoint, which is a URI (or path) and a specific HTTP request method (GET, POST, etc.).
5. **Route Path vs. Route Method:** A route path is the part of the URL that determines where the request should be sent, while a route method is an HTTP method used for the request, such as GET, POST, or DELETE.
6. **Using 'next' in Route Handlers:** It is appropriate to add `next` as a parameter to a route handler to continue the middleware chain. If `next` is passed, you must call `next()` to pass control to the next middleware function; otherwise, the request will hang.

#### Express Router

7. **Express Router:** An Express Router is a mini application capable of performing middleware and routing functions. It is essentially a modular, mountable route handler.
8. **Initializing Express.Router():** In an Express server, `express.Router()` is initialized by requiring the Express module and then calling `Router()` on it, like so: `const router = express.Router();`.
9. **Purpose of Route Middleware:** Route middleware is used to process requests, make modifications to request and response objects, end the request-response cycle, and call the next middleware function in the stack.
10. **What are your learning goals after reading and reviewing the class README?**
My learning goal focuses on a deeper understanding of Express Routing, and applying these concepts in building RESTful APIs with Express.js. 