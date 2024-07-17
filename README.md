# E-commerce 


## Description

Internet retail, also known as e-commerce, plays a significant role within the electronics industry, as it empowers businesses and consumers alike to conveniently engage in online buying and selling of electronic products. This project involves building the back end for an e-commerce site using Express.js and Sequelize to interact with a PostgreSQL database.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [API Routes](#api-routes)
- [Walkthrough Video](#walkthrough-video)

## Features

- Connect to a PostgreSQL database using Sequelize.
- Create and seed a development database.
- Start the server and sync Sequelize models to the database.
- API routes for categories, products, and tags.
- CRUD operations on categories, products, and tags through API routes.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/seokhh10/E-commerce
   cd E-commerce

2. Install dependencies:   
   ```sh
   npm install

3. Create a .env file in the root directory and add your PostgreSQL credentials:
   ```sh
   DB_NAME='ecommerce_db'
   DB_USER='postgres'
   DB_PASSWORD='your_postgresql_password'

4. Create the database using the schema file:
   ```sh
   psql -U your_postgresql_username -d your_database_name -f db/schema.sql

5. Seed the database with test data:
   ```sh
   npm run seed

6. Start the server:
   ```sh
   npm start

## Usage

Use Insomnia Core or any API testing tool to test the following routes:

- GET /api/categories
- GET /api/products
- GET /api/tags
- POST /api/categories
- POST /api/products
- POST /api/tags
- PUT /api/categories/:id
- PUT /api/products/:id
- PUT /api/tags/:id
- DELETE /api/categories/:id
- DELETE /api/products/:id
- DELETE /api/tags/:id

## API Routes

- GET /api/categories: Returns all categories.
- GET /api/products: Returns all products.
- GET /api/tags: Returns all tags.
- POST /api/categories: Creates a new category.
- POST /api/products: Creates a new product.
- POST /api/tags: Creates a new tag.
- PUT /api/categories/:id: Updates a category by its id.
- PUT /api/products/:id: Updates a product by its id.
- PUT /api/tags/:id: Updates a tag by its id.
- DELETE /api/categories/:id: Deletes a category by its id.
- DELETE /api/products/:id: Deletes a product by its id.
- DELETE /api/tags/:id: Deletes a tag by its id.

## Technologies Used

- Node.js
- Express.js
- PostgreSQL
- Sequelize
- dotenv

# Walkthrough Video

[Link Video](https://drive.google.com/file/d/1dPmUEJfywYMQMzKCXMRLoMFEBg-SwwVb/view)

   