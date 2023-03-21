## Overview

This is a basic Express.js server that provides a CRUD (Create, Read, Update, Delete) API for products using a MongoDB database. The server allows clients to perform HTTP operations on the products and manage them.

## Features

-   `GET /products` - retrieves all products from the database
-   `GET /products/:id` - retrieves a single product by ID
-   `POST /products` - creates a new product
-   `PUT /products/:id` - updates an existing product by ID
-   `DELETE /products/:id` - deletes a product by ID

## Installation

To run this server, you must have Node.js and MongoDB installed on your machine. Here are the steps to follow:

1.  Clone this repository to your local machine.
2.  Navigate to the root directory of the project in the terminal.
3.  Install the dependencies by running `npm install`.
4.  In the `index.js` file, replace `ENTER_YOUR_TOKEN` with a valid MongoDB connection URI.
5.  Start the server by running `npm start`.

The server should now be running on `http://localhost:3000`.

## Dependencies

This project has the following dependencies:

-   `express` - for building the server and handling HTTP requests
-   `mongoose` - for interacting with the MongoDB database
