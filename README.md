# Pure Planet
## Introduction

This project is the frontend part of an application, providing users with the ability to browse products, add them to the cart, and proceed to checkout.

## Project Description

Our online nursery website offers a comprehensive platform for purchasing your favorite trees and plants. Users can browse through an extensive product listing, utilize search and filtering options to find specific items, and manage their carts for a streamlined shopping experience. The checkout process is secure and straightforward, incorporating online payments.

## Key Features

-- **Browse a list of products**
- **Search for products by name or category**
- **Filter products by various criteria**
- **Add products to the cart**
- **View cart details**
- **Proceed to checkout**
- **Place an order**
- **Add, Edit or Delete product**

## Technology Stack

- **Backend**: Node.js, Express.js
- **Database**: MongoDB, Mongoose
- **Validation**: Zod
- **Other**: TypeScript, ES6+

## Setting Up and Using the Application

### Prerequisites

- Node.js (>=14.x)
- npm or yarn
- MongoDB

### Installation

1. **Clone the repository**:

   ```sh
   https://github.com/kazirauf/pure-planet-server
   ```

2. **Install dependencies**:

   ```sh
   npm install
   ```

3. **Set up environment variables**:
   Create a `.env` file in the root directory and add the following variables:

   ```
   NODE_ENV=development
   PORT=5000
   DATABASE_URL=your mongodb URI

   ```

4. **Run the application**:
   ```sh
   npm run start:dev
   ```

### Usage

Once the server is running, you can use the following endpoints:

### API Endpoints

- **POST /api/v1/create-product**: Create new product
- **GET /api/v1**: Get all products
- **GET /api/v1/:id**: Get single product
- **DELETE /api/v1/delete-product**: Delete a product
- **PUT /api/v1/update-product**: Update a product
- **POST /api/v1/check-availability**: Check availability of a product
- **POST /api/v1/create-order**: Create order
