# User Management API

REST API built with Java Spring Boot and PostgreSQL, 
implementing full CRUD operations, input validation, error handling, 
and interactive API documentation.

## Tech Stack
- Java 21
- Spring Boot 4.1
- PostgreSQL
- Spring Data JPA
- Spring Validation
- Swagger/OpenAPI
- Maven
- Docker (for deployment)
- Render (hosting)

## Running it locally
You'll need Java 21, Maven, and PostgreSQL installed.

**Set up the database:**

sudo -u postgres psql
CREATE DATABASE userdb;
ALTER USER postgres PASSWORD 'postgres';
\q

Run the app:
mvn spring-boot:run
It starts on port 8080.

