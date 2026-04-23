# Pizza Ordering API

A backend RESTful API for an online pizza ordering system built using ASP.NET Core Web API.

This project simulates a real-world food ordering system and focuses on backend development, database design, and RESTful API principles.

---

## Technologies

- ASP.NET Core Web API
- Entity Framework Core
- SQL Server
- RESTful API Architecture

---

## Features

### Product Management

- Create, update, delete, and view products

### Category Management

- Manage product categories such as Seafood, Beef, Vegetarian

### Shopping Cart

- Add and remove products from cart (business logic)

### Order Management

- Create orders
- View order details
- Process order workflow

---

## API Testing

- All APIs are tested using Postman
- Data format: JSON request and response

---

## Project Structure

- Controllers: Handle HTTP requests and define API endpoints
- Models: Define database entities and data structure
- Data / DbContext: Manage database connection and configuration
- Services: Contain business logic (if applied)

---

## Database Design

- Products table
- Categories table
- Orders table
- Order details table
- (Optional) Users table if authentication is added

---

## Purpose of Project

This project was developed as part of my learning journey in backend development. It helps me understand:

- RESTful API design
- Database relationships (1-N, N-N)
- CRUD operations
- Backend architecture using ASP.NET Core
- Entity Framework Core usage

---

## How to Run Project

Clone repository:
git clone https://github.com/sannie06/pizza-ordering-api

Open project in Visual Studio

Configure connection string in appsettings.json

Run database migration:
update-database

Run project:
dotnet run

---

## Author

Student – Backend Developer (.NET / ASP.NET Core)

---

## Notes

This is a learning project built for practice purposes. Future improvements may include:

- Authentication and authorization (JWT)
- User management system
- Payment integration
- Role-based access control (Admin / Customer)
