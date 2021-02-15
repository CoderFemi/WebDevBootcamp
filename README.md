# Web Development Bootcamp
## HTML
Revised and completed.
## CSS
Revised, and new concepts learned.
## JAVASCRIPT
* Basic concepts revised.
* Javascript Arrays, Objects and Loops revisited.
* New concepts learned in Functions and Callback Methods.
* DOM manipulation revised and new concepts learned.
* DOM events were properly revised, and fresh concepts such as **event bubbling** and **delegation** learned.
* The ScoreKeeper project was done to practice and combine HTML, CSS and Javascript skills.
* Introduction to asynchronous operations. Revised the use of callbacks and the problem of "*callback hell*".
* Revised the use of `Promises` and `Async-Await`, along with best practices for error handling.
## AJAX AND APIs
* Refreshed the concept of what an API means, with particular focus on Web APIs. 
* Revised the different methods of requests: `XMLHttpRequest` and the `Fetch` API. Learnt how to use the `Axios` library to fetch requests.
* Used Postman to send requests and also built a simple interface for consuming APIs using a form.
## OBJECT ORIENTED PROGRAMMING
* Refreshed the meaning of prototype objects.
* Practiced using `factory functions, constructor functions and classes` to create object instances.
* Learnt how the inadequacy of one method leads to an improvement in how object instances are created.
* Revised the usage of the `extends` keyword and the `super` method when inheriting constructor properties from a parent class.
## TERMINAL USAGE AND CLI COMMANDS
* Learnt the difference between a terminal and the shell.
* Installed the bash shell for Windows.
* Revised the various commands and flags used to navigate through, create and remove directories.
## NODE.js
* Learnt the various uses for node: web servers, games and cross-platform applications.
* Revised the basic usage of the node REPL.
* Revised how to use the `process` object and `argv` to build CLIs.
* Revised the use of the npm module `fs` for creating, reading and writing to the file system.
* Refreshed the concept of creating custom modules using the `require` method and `module.exports`.
* Revised the use of `Express.js` for creating and starting a webserver, listening for and routing requests, and sending responses for client side rendering.
* Learnt more about **Path Parameters** and **Query Strings**.
* Learnt the usage of `EJS` as a view engine for templating, using easy-to-adapt embedded javascript.
* Learnt how to use `partials` as subviews for repeating content across pages.
* Revised how to serve up static assets (including downloaded bootstrap assets) using the public directory.
* Refreshed terminology on RESTful API architecture.
* Practiced on a REST API demo app, creating routes for all CRUD operations.
* Learnt how to use the `method-override` module for `PATCH`, `PUT`  AND `DELETE` http methods.
* Learnt how to use the `redirect` method at the end of a CRUD operation.
## MONGODB
* Revised the major distinction between SQL and NoSQL databases.
* Refreshed through the `MongoDB` installation process.
* Learnt how to use the MongoDB shell to perform CRUD operations.
* Learnt the various operators used to perform more complex database queries.
## Mongoose
* Revised the need for the `Mongoose` library vis-a-vis MongoDB.
* Revised the database connection process.
* Revised creating a `Schema` and hence, a `Model`.
* Revised Schema validations, constraints, Model `instance methods`, Model `static methods` and `virtuals`.
* Learnt the use of Mongoose middleware.
* Learnt how to build a Farm Products website to practice the combined use of Express and Mongoose.

## MORE ADVANCED CONCEPTS IN EXPRESS & MONGOOSE
* Understood in-depth the meaning of `middleware`, as just functions that run inbetween the request and response life cycle (using `express.json()` and `express.static()` as common examples).
* Learnt how to install and use third-party middleware, and also how to create custom middleware functions to perform our own defined actions to certain routes we specify, and to modify the request or response object.
* Learnt the fundamentals of `authentication`, using a simple middleware function, and passing it into specified routes to prevent them from being accessed without credentials.
* Learnt how to install and use `EJS Mate`, a huge improvement on **partials**, for rendering similar content on every page, using a boilerplate.

## YELP CAMP PROJECT
* Created an Express Server and set up a Mongoose connection.
* Created a barebone skeleton for views and routes.
* Created a **seed database** and pre-populated the views with basic seed data.
* Installed ejs-mate and created a boilerplate for all the views, and made partials for headers and footers; linking them to the boilerplate.
* Added bootstrap v5 (update does not use jQuery) javascript scripts and css link to the boilerplate.
* Added a navbar and a footer.
* Positioned the navbar, body and footer using bootstrap flex class attributes, and container classes.
* Added a `bootstrap card` to each item on the landing page, arranging and styling the image, title, location and description of each item.
* Created and styled the *new*, *show* and *edit* views with cards, linking each file contents to the boilerplate view.