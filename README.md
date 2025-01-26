# Basic E-Commerce Application

A simple e-commerce web application developed using **Spring Boot**. This application provides basic features such as product listing, cart management, user registration, and order processing. It is designed to give a simple view of how an e-commerce system can be implemented using the Spring Boot framework.

## Features

- **Product Listing**: Display a list of products with basic details like name, description, and price.
- **Cart Management**: Users can add items to their cart, view their cart, and update quantities.
- **User Authentication**: Basic user authentication to register, log in, and manage accounts.
- **Order Processing**: Users can place orders for items in their cart.
- **Admin Panel**: An administrative interface to manage products and view orders (Optional).
  
## Technologies Used

- **Spring Boot**: Backend framework used for developing the application.
- **Spring Data JPA**: For database interaction using JPA repositories.
- **Thymeleaf**: Server-side templating engine for rendering web pages.
- **MySQL**: Relational database to store user, product, and order data..
- **Bootstrap**: For frontend styling.
- **Maven**: Dependency management and build tool.

Build the project using Maven:
mvn clean install

Run the application:
mvn spring-boot:run
