# E-Commerce REST API

A RESTful e-commerce backend built with Spring Boot, featuring product management with image upload support.

## Tech Stack
- Java, Spring Boot
- Spring Data JPA
- MySQL Database
- Lombok

## Features
- Full CRUD operations for products
- Image upload and retrieval per product
- Clean layered architecture (Controller → Service → Repository)
- RESTful API design tested with Postman

## API Endpoints
| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /api/products | Get all products |
| GET | /api/product/{id} | Get product by ID |
| POST | /api/product | Add new product (with image) |
| PUT | /api/product/{id} | Update product (with image) |
| DELETE | /api/product/{id} | Delete product |
| GET | /api/product/{id}/image | Get product image |

## How to Run
1. Clone the repo
2. Create a MySQL database:
```sql
   CREATE DATABASE ecommerce_db;
```
3. Copy `src/main/resources/application.properties.example` to `src/main/resources/application.properties`
4. Set the `DB_PASSWORD` environment variable to your MySQL root password
5. Open in IntelliJ IDEA
6. Run EcomProjApplication.java
7. Test endpoints using Postman

## Status
In Progress - adding Spring Security/JWT and deployment