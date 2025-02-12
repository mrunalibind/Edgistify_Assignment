# Edgistify Assignment

## Introduction
An E-commerce project where users can buy products, it has a user authentication, product section, cart, and checkout functionality.

## Project Type
Frontend | Backend | Fullstack

## Deplolyed App
Frontend: https://edgistify-frontend.onrender.com
Backend: https://edgistify-backend-oh53.onrender.com

## Directory Structure
Edgistify_Assignment/
├─ Backend/
├─ Frontend/
│  ├─ ...

## Video Walkthrough of the project
[Video Walkthrough] (https://drive.google.com/file/d/1bVUwGaktogpoJzFoLrk0s4txzEorbYmc/view?usp=sharing)


## Video Walkthrough of the codebase
Attach a very short video walkthough of codebase [ 1 - 5 minutes ]

## Features
List out the key features of your application.

- User Registration with express-validator
- User Login
- Product Section
- Cart Page
- Checkout Form

## design decisions or assumptions
List your design desissions & assumptions

## Installation & Getting started
For Backend: 
```bash
cd Backend 
npm install
npm run dev
```
For Frontend: 
```bash
cd Frontend
cd my-app
npm install
npm run dev
```

## Usage
Provide instructions and examples on how to use your project.
When you open the deployed frontend, you'll see a registration form requiring a full name, a valid email, and a password (minimum 8 characters). Validation is handled in the backend using express-validator. After successful login, you're redirected to the product page, where you can add items to your cart. In the cart, you'll see the added products and can proceed to checkout by entering your shipping address. Product availability and quantity are validated in the backend with proper error handling.


Include screenshots as necessary.

## Credentials
Provide user credentials for autheticated pages

## APIs Used
If your application relies on external APIs, document them and include any necessary links or references.

## API Endpoints
In case of Backend Applications provide a list of your API endpoints, methods, brief descriptions, and examples of request/response.

POST /api/user/register - user registeration
POST /api/user/login - user login

GET /api/product/getProducts - to get Products

POST /api/cart/addProductToCart - Click on Add to cart button, product will be added to cart
GET /api/cart/getCartProduct - to get product added by user in the cart

POST /api/order/placeOrder - Order placed successfully after submitting checkout form.


## Technology Stack
List and provide a brief overview of the technologies used in the project.

- Node.js
- Express.js
- MongoDB
- React
- Other libraries/modules
