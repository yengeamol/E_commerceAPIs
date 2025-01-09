# E-Commerce APIs

This is a Spring Boot project that provides a set of REST APIs for an e-commerce platform. The project is designed to manage core functionalities such as product catalog, user management, shopping cart, order processing, and more.

## Features

- **User Management:** Register, login, and manage user profiles with JWT-based authentication.
- **Product Catalog:** CRUD operations for products and categories.
- **Shopping Cart:** Add, update, and remove items from the cart.
- **Order Management:** Place orders and track order history.
- **Inventory Control:** Manage product inventory and stock levels.
- **Search Functionality:** Full-text search capabilities using Elasticsearch.
- **Payment Integration:** Simulate payment processing and order checkout.
- **Real-time Updates:** Server-sent events for real-time notifications.

## Technologies Used

- **Backend:** Spring Boot, Java , Hibernate , JPA
- **Database:** PostgreSQL
- **Search Engine:** Elasticsearch
- **Authentication:** JWT (JSON Web Token)
- **Build Tool:** Maven

## Prerequisites

- Java 11+
- Maven 3+
- Springboot
- PostgreSQL
- Elasticsearch


API Endpoints
User Management:

POST /api/users/register - Register a new user
POST /api/users/login - User login
Product Management:

GET /api/products - Get all products
POST /api/products - Add a new product
PUT /api/products/{id} - Update a product
DELETE /api/products/{id} - Delete a product
Shopping Cart:

GET /api/cart - Get cart items
POST /api/cart - Add item to cart
DELETE /api/cart/{id} - Remove item from cart
Order Management:

POST /api/orders - Place an order
GET /api/orders - Get all orders for a user


Contribution
Contributions are welcome! Please fork the repository and submit a pull request with your changes.
