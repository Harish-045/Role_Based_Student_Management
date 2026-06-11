# 🎓 Student Management System

A Spring Boot web application designed to manage students, teachers, and courses efficiently with role-based access control. The system provides a structured way to perform CRUD operations and manage academic data using a layered backend architecture.

---

## 🚀 Features

- 👨‍🎓 Manage students, teachers, and courses  
- 🔐 Role-based authentication (Admin, Student, Teacher)  
- ➕ Add, update, and delete records  
- 📋 Enroll and manage courses for students  
- 📊 View student details, grades, and assignments  
- 🛡️ Secure backend using Spring Security  

---

## 🏗️ Architecture

Follows layered architecture:

Controller → Service → Repository → Database  

---

## 🛠️ Technologies Used

- Java  
- Spring Boot  
- Spring MVC  
- Spring Security  
- Spring Data JPA / Hibernate  
- MySQL  
- Maven  

---

spring.datasource.url=jdbc:mysql://localhost:3306/your_db
spring.datasource.username=root
spring.datasource.password=your_password

## 📌 Modules

### 👨‍💼 Admin
- Manage students, teachers, and courses  
- Enroll students into courses  
- View system statistics  

### 🎓 Student
- View enrolled courses  
- Check assignments and grades  

### 👨‍🏫 Teacher
- Create assignments  
- Evaluate student performance  

---

## ⚙️ API Overview

- `GET /students` → Get all students  
- `POST /students` → Add new student  
- `PUT /students/{id}` → Update student  
- `DELETE /students/{id}` → Delete student  
- `GET /courses` → Get courses  

---

## 📦 Setup Instructions

```bash
git clone https://github.com/Harish-045/Student-Management-System.git
cd Student-Management-System
