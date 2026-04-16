# 🛒 E-Commerce REST API (Node.js)

> A scalable and modular backend system for an e-commerce platform built using Node.js, Express.js, and MongoDB.

---

## 📌 Overview

This project is a **RESTful API for an E-Commerce application** that provides backend services for:

- User authentication & authorization  
- Product management  
- Order processing  

It follows a **clean architecture pattern** using controllers, services, and middleware for better scalability, maintainability, and separation of concerns.

---

## 🚀 Features

### 🔐 Authentication & Authorization
- User Registration & Login  
- JWT-based Authentication  
- Password hashing using bcrypt  
- Protected routes using middleware  

### 👤 User Management
- Get all users  
- Get user by ID  

### 📦 Product Management
- Create product  
- Get all products  
- Get single product  
- Update product  
- Delete product  
- Upload product images  

### 🛒 Order Management
- Create orders  
- Fetch all orders  

### ⚙️ Additional Features
- Input validation  
- Centralized error handling  
- File upload using Multer  
- Environment configuration using dotenv  

---

## 🏗️ Project Structure
├── config/ # Configuration files
├── controllers/ # Route controllers
├── database/ # Database connection
├── middlewares/ # Auth & error middleware
├── models/ # Mongoose schemas
├── routes/ # API routes
├── services/ # Business logic
├── validators/ # Input validation
├── uploads/ # Uploaded images
├── server.js # Entry point
└── package.json


---

## 🛠️ Tech Stack

- **Backend:** Node.js, Express.js  
- **Database:** MongoDB, Mongoose  
- **Authentication:** JWT  
- **Security:** bcrypt  
- **File Upload:** Multer  
- **Environment:** dotenv  

---

## ⚙️ Installation & Setup

1️⃣ Clone Repository

```bash
git clone https://github.com/gauravrajput-2313/ecommerce-rest-apis-node.git
cd ecommerce-rest-apis-node

2️⃣ Install Dependencies
npm install

3️⃣ Setup Environment Variables
PORT=5000
DB_URL=your_mongodb_connection_string
JWT_SECRET=your_secret_key

4️⃣ Run the Application
npm run dev
npm start
