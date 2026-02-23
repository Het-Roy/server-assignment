#  E-Commerce Product API

A simple REST API built using **Node.js** and **Express.js** to manage products using an in-memory JSON database.  
Supports **GET, POST, and PUT** operations.

💫GitHub Repo:
https://github.com/Het-Roy/server-assignment/tree/main/server-02

💫Postman Documentation:
https://documenter.getpostman.com/view/50871368/2sBXcGCeTS

💫Render Deployment:
https://server-assignment-2-7bee.onrender.com/
 
## Features
  
### GET Routes
- Get all products → `GET /products`
- Get product by ID → `GET /products/:id`
- Get products by category → `GET /products/category/:categoryName`

### POST Route
- Add new product → `POST /products`

### PUT Routes
- Update full product → `PUT /products/:id`
- Update stock → `PUT /products/:id/stock`
- Update price → `PUT /products/:id/price`
