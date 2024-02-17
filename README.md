Node.js Application: This code snippet represents a Node.js application.

Express.js Framework: It utilizes the Express.js framework for creating a web server.

Middleware Usage: Utilizes middleware like body-parser and express.static for request body parsing and serving static files respectively.

Routing: Defines separate routes for admin-related functionalities and shop-related functionalities, mounted under specific base paths (/admin and root path for shop routes).

View Engine: Sets up the view engine as EJS (Embedded JavaScript) for rendering dynamic content.

Error Handling: Implements middleware for handling 404 errors, rendering a custom error page if a requested route is not found.

Server Initialization: Starts the server and listens on port 3000.
