# Products Microservice

This is the Products Microservice for the Products App. It handles all product-related operations.

## Table of Contents

- [Installation](#installation)
- [API Endpoints](#api-endpoints)
- [License](#license)

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/Nest-Microservices-AlexisH/products-microservices.git
   ```
2. Navigate to the project directory:
   ```sh
   cd products-ms
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Create a `.env` file in the root of the project based in env.template file

5. Execute `npm run start:dev` to start the server in development mode

## API Endpoints

- `GET /products` - Retrieve a list of products
- `GET /products/:id` - Retrieve a single product by ID
- `POST /products` - Create a new product
- `PUT /products/:id` - Update a product by ID
- `DELETE /products/:id` - Delete a product by ID

## License

This project is licensed under the MIT License.
