# Spring Security Auth API (Final Project)

This project demonstrates basic user authentication using Spring Boot and JWT (JSON Web Tokens).

## 🔐 Features
- Register new user
- Login with username and password
- Password hashing with BCrypt
- PostgreSQL database integration
- Role-based route protection
- Spring Security configuration
- Swagger UI ready (can be added)

## 📁 Project Structure
- `controller` — REST endpoints
- `service` — Business logic
- `repository` — JPA interface to DB
- `entity` — User entity class
- `dto` — Login and register request models
- `config` — Spring Security setup

## 🛠 How to Run
1. Update your DB config in `src/main/resources/application.properties`
2. Run using:
   ```bash
   mvn clean install
   mvn spring-boot:run
