# CRUD API with Laravel

This project is a basic CRUD API created with Laravel to manage a resource called "Product".

## Requirements

- PHP >= 8.1
- Composer
- MySQL

## Installation

1. Clone this repository:

    ```sh
    git clone https://github.com/ArielOrellana/product-api-rest.git
    cd product-api-rest
    ```

2. Install Composer dependencies:

    ```sh
    composer install
    ```

3. Configure your `.env` file:

    Copy the `.env.example` file and rename it to `.env`.

4. Generate the application key:

    ```sh
    php artisan key:generate
    ```

5. Run migrations to create the tables in the database:

    ```sh
    php artisan migrate
    ```

## Usage

1. Start the Laravel development server:

    ```sh
    php artisan serve
    ```

2. You can now make HTTP requests to your API. The base URL will be `http://127.0.0.1:8000/api/products`.

### Endpoints

- **GET /api/products**: Retrieve all products.
- **POST /api/products**: Create a new product.
- **GET /api/products/{id}**: Retrieve a specific product by ID.
- **PUT /api/products/{id}**: Update a specific product by ID.
- **DELETE /api/products/{id}**: Delete a specific product by ID.

