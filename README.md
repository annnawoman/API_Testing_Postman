##Overview 
API testing using Postman 

## Features

### 1. Authorization
- **Endpoints**:
  - `POST /auth/login` - Authenticate users and generate tokens.
- **Description**: 
  - The authorization section handles user authentication
  - 
### 2. Cart Management
- **Endpoints**:
  - `GET /api/carts/user/{{userId}}` - Retrieve user cart.
  - `POST /api/carts/add` - Add products to the cart.
  - `DELETE /api/carts/{{cartIdToDelete}}` - Remove products from the cart.
- **Description**:
  - This section of the API allows users to manage their shopping cart. Users can add items to the cart, view the items, and remove items as needed.

### 3. Product Management
- **Endpoints**:
  - `GET /products` - List all products.
  - 'GET /products/{{id}}
  - `POST /products/add` - Add a new product 
  - `PUT /products/{{id}}` - Update an existing product 
  - `DELETE /products/{{id}}` - Delete a product 
- **Description**:
  - Product management includes endpoints for listing products, adding new products, and modifying or deleting existing products.
 
### 4. Error Handling
- **Endpoints**:
  - `PUT /products/{{id}} - Invalid data
  - 'DELETE /products/{{id}} - Non existing product

### 4. Exploratory Testing 
- **Endpoints**:
  - 'GET /products?search=phone - Product with different query parameters 
  - 'GET /products/id - Non exisiting product
  - 'Post /products/add - Special characters

### 5. User Stories 
- User able to view, edit, add and delete previously created product

## How to Run

1. Clone the repository:
   ```bash
   git clone <repository-url>
