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
* Understood in-depth the meaning of Express `middleware`, as just functions that run inbetween the request and response life cycle (using `express.json()` and `express.static()` as common examples).
* Learnt how to install and use third-party middleware, and also how to create custom middleware functions to perform our own defined actions to certain routes we specify, and to modify the request or response object.
* Learnt the fundamentals of `authentication`, using a simple middleware function, and passing it into specified routes to prevent them from being accessed without credentials.
* Learnt how to install and use `EJS Mate`, a huge improvement on **partials**, for rendering similar content on every page, using a boilerplate.
### Error Handling in Express
* Understanding different types of errors: syntax errors, cast errors, reference errors, validation errors, authentication errors, async errors.
* Understand the default error handler Express uses. New instances of Error can be created with our own custom message and status code.
* Learnt how to define a custom error class.
* Learnt how to create error handling middleware: must have four parameters, and be the last in the middleware chain.
* Async errors are handled using the try-catch syntax. A more improved approach, is to wrap the async callback in a wrapper function, and then catch the error on the returned promise.
### Mongoose Relationships
* Explored the type of data relationships: one to few, one to many, one to bajillions.
* In a `one to few relationship`, the child items do not need to be broken into a separate schema, but is usually embedded in the parent.
* In a `one to many relationship`, two separate schemas are defined, and a reference to the child schema id is set in the parent. The populate method is called to retrieve referenced data.
* In a `one to bajillion` relationship, it makes more logical sense to set the reference to the parent in the child schema. The populate method is called to retrieve referenced data.
* In a `two-way relationship`, both parent and child reference each other.
* Learnt rules of thumb to follow when designing schemas. e.g. `denormalisation` (data duplication) might be more efficient when write/read times for certain data sets are very low.
* Learnt how to use `Mongoose middleware` to delete child documents along with the parent document.
* Practiced multi-model relationships with the FarmStand app.
### Express Routing
* Learnt the concept of routing in Express. Used a simple practice file to factor all routes into different files based on which resources need to be accessed, required `express.Router` in the entry file, and used middleware to route different requests to their respective route files. Also learnt the added advantage of using separate middleware for a separate group of routes, using `router.Use`. Also learnt the usage of the parameter `mergeParams: true` when trying to access params in a separate router.
### COOKIES, SESSIONS and FLASH
* Understood how cookies - key-value pairs of strings - are used to store information on the client browser about everytime a request is made to a server. They provide statefulness to HTTP requests. Cookies can be used to personalise the user's browsing session, or for tracking purposes. Learnt the use of an Express middleware `cookie-parser` for signing and verifying cookies to and from a client browser.
* Sessions serve the same purpose as cookies, but information about the client's browsing is saved on a datastore, not on the browser and a cookie is sent with the request to retrieve that information from the store. MemoryStore is a non-persistent store used for development purposes. `express-session` is a tool used as middleware in Express, to save sessions.
* `Flash` is a temporary message displayed to a user before redirecting which is not part of the views template, but is added to the user's session on a particular request. `Express-flash` incorporates this feature into the app.

## AUTHENTICATION AND AUTHORIZATION
* Learnt the difference between both concepts: `authentication` is simply identifying who a client is, and `authorization` is about defining what that user can access after being authenticated.
* Learnt the reasons for not saving text passwords in a database, and best practices available using a `one-way cryptographic hashing function` to store hashed values instead.
* Learnt the meaning of `salting`, which is an extra safeguard taken to ensure that passwords cannot be deciphered. This essentially involves adding a randomly-generated value (salt) to each password before it's hashed, so that it is uniquely different from another password of the same value.
* `Bycrpt` is a package that provides hashing and salting functionality.

## IMAGE UPLOAD
* Learnt how to create a image-upload compatible form using a `multipart/form data` encoded type, instead of the regular urlencoded type used for submitting form data.
* Learnt how to use the `Multer`and `Multer-storage-cloudinary` middleware to upload images to Cloudinary.

## ENVIRONMENT VARIABLES
* Learnt the meaning of environment variables, and their usage in production and development modes.

## MAPBOX
* Learnt the basics of geocoding and the two types - forward geocoding and reverse geocoding.

## SECURITY
* Learnt and understood the implications of *SQL Injection* (Mongo Injection), through which malicious users make unauthorised queries, other than the ones specified by the developer, to manipulate the database. A node package,  `express-mongo-sanitise` is used to prohibit/sanitise the usage of special characters in the request objects.
* Learnt about *cross-site-scripting (XSS)*, where malicious users insert client-side scripts into web pages viewed by other users, mainly targeting information in the users' session. npm module `express-validator` and `sanitize-html` are tools that help to escape html and prevent scripts from being injected. The Joi validation package has to be coded with extensions to be able to perform this function.
* `Helmet` is another robust tool that protects against various malicious attacks. Its Content Security Policy can be configured to restrict fetching of resources/assets only from specified domains.
* Other safeguards for the user's session is to configure the cookie with a different, **distinct name** from the default name, set option **httponly: true**, and **secure: true**, to enable user receive cookies only via http and https.
* Also hide development errors and the stack trace from being sent to the client.

## DEPLOYMENT
* Revised the process of deployment using Heroku CLI, configuring MongoDB Atlas, and setting Heroku environment variables.

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
* Added client-side validation to forms using bootstrap.
* Added server-side validation by installing the `joi` module. A middleware was used to validate all post/put requests.
* Defined a Review schema and created a model, added validation to the review form on both client and server-side, created post and delete routes, as well as the mongoose-defined middleware for removing references from the parent schema when deletion occurs.
* Learnt the usage of `$in` and `$pull` operators for querying the MongoDB database. The latter being distinct, as it works on an array instead of a document/object.
* Refactored the app to use separate routers for the different models/resources.
* Configured the public directory for static assets.
* Configured sessions and flash. A middleware was used to pass in the flash object to `res.locals`. Setup bootstrap alerts to style flash messages, and created a separate partial to show them.
* Installed the `Passport` library, and used its built-in methods to hash passwords, and configure authentication for register, login and logout routes.
* Configured authorisation and permissions for requesting and viewing campground and review resources by defining a middleware.
* Refactored routes with controllers, in line with the MVC concept. 
* Added a third-party CSS file to style clickable star ratings, instead of a range input.
* Installed and required multer, cloudinary and multer-storage-cloudinary. Configured the cloudinary instance, including environment variables, and added it as middleware to the route handler for creating new campgrounds, in order to store the uploaded image links in MongoDB. Updated the show page to use the cloudinary url as image src.
* Added a bootstrap carousel to contain and scroll through uploaded images. Added logic into the show page to show/hide the carousel controls depending on the number of images.
* Added functionality to update and delete images from the database and cloudinary.
* Changed the image input to a bootstrap one, and included a `bs-custom-file-input` script to help with displaying image file names inthe input.
* Added width specifications in the image urls, as per the cloudinary api, to display thumbnails on the show page.
* Installed the mapbox geocoding npm package, and reverse-geocoded the campground location to give latitude and longitude coordinates.
* Updated the post route for creating a campground to save those coordinates to the database.
* Updated the campground location schema to conform to the `geoJson` format for geocoding.
* Added a map to the showpage by including the mapboxGLJS scripts in the boilerplate, and additional javascript.
* Added a cluster map to the campgrounds page by using and tweaking example code from the Mapbox documentation.
* Added further styling to the landing, register and login pages.
* Added security features: installed express-mongo-sanitisise and helmet, and passed them into the app as middleware. Also installed sanitise-html for integration into the existing Joi module to create an extension for security features in the schema.
* Installed connect-mongo, and configured sessions to use the MongoStore instead of the Memorystore.