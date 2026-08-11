# E-Commerce REST API

A RESTful e-commerce backend built with Spring Boot, featuring product management with image upload support.

## Tech Stack
- Java, Spring Boot
- Spring Data JPA
- H2 Database (development)
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
2. Open in IntelliJ IDEA
3. Run EcomProjApplication.java
4. Test endpoints using Postman

## Status
In Progress - adding Spring Security/JWT, MySQL, and deployment