# 🚀 Employee Management System (Spring Boot)

## 📌 Overview
A production-ready backend project built using Spring Boot to manage Employees and Departments through REST APIs.  
This project showcases real-world backend development skills like CRUD operations, REST API design, database integration, and clean architecture.

---

## 🛠️ Tech Stack
- Java 17  
- Spring Boot  
- Spring Data JPA  
- PostgreSQL  
- Maven  
- Lombok  

---

## 🔥 Features
- ✅ Employee CRUD APIs  
- ✅ Department Management  
- ✅ One-to-Many Relationship (Department → Employees)  
- ✅ Pagination Support  
- ✅ Input Validation  
- ✅ Global Exception Handling  

---

## 🧠 Project Architecture
controller → service → repository → entity → database

---

## 📊 Database Design

### Employee Table
- id (Primary Key)
- name  
- email  
- salary  
- department_id (Foreign Key)

### Department Table
- id (Primary Key)
- name  

👉 Relationship: One Department → Many Employees

---

## 🔗 API Endpoints

### 👨‍💼 Employee APIs
- POST /employees → Add Employee  
- GET /employees → Get All Employees  
- GET /employees/{id} → Get Employee by ID  
- PUT /employees/{id} → Update Employee  
- DELETE /employees/{id} → Delete Employee  
- GET /employees?page=0&size=5 → Pagination  

### 🏢 Department APIs
- POST /departments → Add Department  
- GET /departments → Get All  
- GET /departments/{id} → Get by ID  
- DELETE /departments/{id} → Delete  

---

## ⚙️ Setup Instructions

### 1️⃣ Clone Repository
git clone https://github.com/avinashgond/ems-project.git

### 2️⃣ Configure Database (application.properties)
spring.datasource.url=jdbc:postgresql://localhost:5432/emsdb  
spring.datasource.username=postgres  
spring.datasource.password=postgres  
spring.datasource.driver-class-name=org.postgresql.Driver  

spring.jpa.hibernate.ddl-auto=update  
spring.jpa.show-sql=true  

### 3️⃣ Run Application
mvn spring-boot:run

---

## 🎯 Purpose
This project is built for learning, practice, and preparing for Java Backend Developer roles.

---

## 💪 Author
Avinash Gond  
(Java Backend Developer 🚀)

---

## ⭐ Support
If you like this project, give it a ⭐ on GitHub!
