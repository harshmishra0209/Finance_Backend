# Finance Backend System

A robust and secure Financial Management Backend built using **Spring Boot**. This system handles user authentication, financial transactions, and account management with industry-standard security practices.

## 🚀 Features
* **User Authentication:** Secure Login and Registration using **JWT (JSON Web Tokens)**.
* **Security:** Role-based access control with **Spring Security**.
* **Financial Operations:** Manage transactions, balances, and account details.
* **RESTful Architecture:** Clean and scalable API endpoints.
* **Database Management:** Integrated with **MySQL** using Spring Data JPA.

## 🛠️ Tech Stack
* **Java** (JDK 17 or higher)
* **Spring Boot** (Web, Security, Data JPA)
* **JSON Web Token (JWT)** for secure Auth
* **MySQL** Database
* **Maven** for Dependency Management

## 📂 Project Structure
```text
src/main/java/com/finance
├── config          # Security and JWT configurations
├── controller      # REST API Endpoints
├── dto             # Data Transfer Objects
├── entity          # Database Models
├── repository      # JPA Repositories
├── service         # Business Logic
└── security        # Custom Auth Filters & Detail Services

 Setup & Installation:
git clone [https://github.com/harshmishra0209/Finance_Backend.git](https://github.com/harshmishra0209/Finance_Backend.git)


Database Configuration:
spring.datasource.url=jdbc:mysql://localhost:3306/finance_db
spring.datasource.username=your_username
spring.datasource.password=your_password


Run the application:
mvn spring-boot:run


Key API Endpoints:
POST /api/auth/signup - Register a new user
POST /api/auth/login - Authenticate user & get JWT token
GET /api/accounts/balance - (Protected) Check account balance
POST /api/transactions - (Protected) Make a new transaction

