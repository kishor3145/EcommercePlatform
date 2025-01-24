# Ecommerce Platform using Spring Boot and Angular

## Overview
EcommercePlatform is a full-stack application built using Angular for the front-end and Spring Boot for the back-end. The project showcases an online shopping platform where users can browse products, add items to the cart, and complete purchases. The application includes features such as user authentication, product management, and order processing. The project is open-source and hosted on GitHub.

---

## Tech Stack and Tools
- **Front-end**: Angular
- **Back-end**: Spring Boot
- **Database**: MySQL
- **ORM**: Hibernate

---

## Modules
1. **Login & Logout Module**
2. **Admin Module**
3. **Customer Module**
4. **Product Module**
5. **Order Module**
6. **Shopping Cart Module**

---

## Features

### Admin Features
Admins can perform the following operations:
- Add, update, or delete products
- View all customers
- Manage orders

### Customer Features
Customers can perform the following operations:
- Register and login
- Browse products by categories
- Add products to the shopping cart
- Place orders
- View order history

### Product Features
- Display product details
- Show product categories
- Manage product stock levels

---

## Installation & Run

To run this application:
1. Update the database configuration inside the `application.properties` file located in the `src/main/resources` folder.
   ```properties
   server.port=8808 
   spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce_platform 
   spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver 
   spring.datasource.username=your_username_here 
   spring.datasource.password=your_password_here
   ```

2. Build and run the application:
   ```bash
   mvn clean install
   mvn spring-boot:run
   ```

3. Access the application:
   - API Root Endpoint: `https://localhost:8808/`
   - Swagger UI: `https://localhost:8808/swagger-ui/index.html`

---

## created by
@Kishor Darkunde
