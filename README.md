## Contact Management App
A full-stack web application built with Node.js, Express, and MongoDB to manage contacts with user authentication. 
This project demonstrates RESTful API development, CRUD operations, JWT-based security, and MongoDB integration using Mongoose.

## Features
* User registration and login with JWT authentication
* Secure password hashing
* CRUD operations for managing contacts (Create, Read, Update, Delete)
* Protected routes for authenticated users only
* MongoDB database integration with Mongoose schemas
* Error handling middleware
* RESTful API conventions

## Tech Stack
* Backend: Node.js, Express.js
* Database: MongoDB, Mongoose
* Authentication: JSON Web Tokens (JWT)
* Testing: Thunder Client (for API testing)
* Middleware: Express Async Handler, Custom Error Handling

# API Endpoints
## User Routes
* POST /api/users/register - Register a new user
* POST /api/users/login - Login and receive JWT token
* GET /api/users/current - Get current logged-in user (protected)

## Contact Routes (Protected)
* GET /api/contacts - Get all contacts for the logged-in user
* POST /api/contacts - Create a new contact
* GET /api/contacts/:id - Get a specific contact by ID
* PUT /api/contacts/:id - Update a contact by ID
* DELETE /api/contacts/:id - Delete a contact by ID
