# Online Quiz Application (Backend)

A secure and scalable **Online Quiz Application backend** developed using **Java and Spring Boot**, providing RESTful APIs for quiz management, user authentication, and role-based access control.

---

## 🚀 Features

- User authentication and authorization using **Spring Security & JWT**
- Role-based access control (**Admin / User**)
- Secure password storage using **BCrypt**
- Quiz creation, update, deletion, and retrieval
- User participation and progress tracking
- RESTful API design following **layered architecture**
- Exception handling and input validation

---

## 🛠️ Tech Stack

- **Language:** Java  
- **Framework:** Spring Boot  
- **Security:** Spring Security, JWT, BCrypt  
- **Database:** MySQL 8  
- **ORM:** Spring Data JPA (Hibernate)  
- **Build Tool:** Maven  
- **API Testing:** Postman  

---

## 🧱 Architecture

The application follows a **layered architecture**:


- **Controller:** Handles HTTP requests and responses  
- **Service:** Contains business logic  
- **Repository:** Manages database operations using JPA  

---

## 📌 Modules

### 👤 User Module
- User registration and login
- JWT-based authentication
- Role-based authorization

### 📝 Quiz Module
- Create, update, delete quizzes (Admin only)
- Fetch quizzes for users
- Manage quiz questions and answers

### 📊 User Progress
- Track quiz attempts
- Store user scores and progress

---

## 🔐 Security Implementation

- Passwords are encrypted using **BCrypt**
- Stateless authentication using **JWT tokens**
- Secured endpoints based on user roles
- Token validation for protected APIs

---

## 🗄️ Database Design

- Relational schema designed using **MySQL**
- Entities mapped using **JPA annotations**
- Efficient CRUD operations and query handling

---

## ▶️ How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/mohd-zeeshan77/<repository-name>.git
spring.datasource.url=jdbc:mysql://localhost:3306/quizdb
spring.datasource.username=your_username
spring.datasource.password=your_password
mvn spring-boot:run
