# 🛒 Full Stack Billing Software

A Full Stack Billing Software developed using **React.js**, **Spring Boot**, and **MySQL**. The application enables administrators to manage categories, products, users, and customer orders while providing a secure authentication system and a responsive user interface.

## 🚀 Features

- User Authentication using JWT
- Spring Security Integration
- Admin Dashboard
- Category Management
- Product/Item Management
- Customer Order Management
- Billing & Invoice Generation
- Image Upload Integration using AWS S3
- Razorpay Payment Gateway Integration
- Responsive React Frontend
- RESTful API Architecture

---

## 🛠️ Tech Stack

### Frontend
- React.js
- JavaScript
- HTML5
- CSS3
- Axios
- React Router

### Backend
- Java
- Spring Boot
- Spring Security
- Spring Data JPA
- JWT Authentication
- Maven

### Database
- MySQL

### Cloud & Payment
- AWS S3
- Razorpay

### Tools
- IntelliJ IDEA
- VS Code
- Postman
- MySQL Workbench
- Git
- GitHub

---

## 📂 Project Structure

```
Billing-Software
│
├── client/                 # React Frontend
├── billingsoftware/        # Spring Boot Backend
├── billing_app.sql         # Database Script
└── README.md
```

---

## 🔐 Authentication Flow

1. User enters email and password.
2. Spring Security authenticates the user.
3. Password is verified using BCrypt.
4. JWT Token is generated.
5. Token is returned to the frontend.
6. Protected APIs are accessed using the JWT token.

---

## 🗄️ Database Tables

- tbl_users
- tbl_category
- tbl_items
- tbl_orders
- tbl_order_items

---

## 🌟 Key Features

- Secure Login & Authentication
- Category CRUD Operations
- Product CRUD Operations
- Shopping Cart
- Order Processing
- Invoice Generation
- Dashboard Analytics
- Cloud Image Storage
- Payment Integration

---

## 📌 REST APIs

- Login API
- User Management API
- Category API
- Item API
- Order API
- Payment API

---

## 📸 Screenshots

> Screenshots will be added soon.

---

## 🔮 Future Enhancements

- Barcode Scanner
- GST Invoice Support
- PDF Invoice Generation
- Email Notifications
- Inventory Alerts
- Sales Analytics Dashboard

---

## 👩‍💻 Author

**N M Tanusha**

B.Tech – Computer Science Engineering

CMR University

---

## ⭐ Note

This project was developed as part of a learning journey in Full Stack Java Development and demonstrates practical implementation of React.js, Spring Boot, MySQL, JWT Authentication, REST APIs, AWS S3 integration, and Razorpay payment integration.
