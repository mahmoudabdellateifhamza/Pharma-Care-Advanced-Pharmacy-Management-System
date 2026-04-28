# Pharma-Care-Advanced-Pharmacy-Management-System
Advanced full stack Pharmacy Management System with POS, inventory control, customer tracking, supplier management, and real time analytics. Built using Node.js, Express, SQLite, and Vanilla JS with clean REST APIs and scalable architecture, simulating real world pharmacy operations.

# 💊 PharmaCare Pro — Advanced Pharmacy Management System

🚀 A full-stack, production-style **Pharmacy Management System** designed to handle real-world pharmacy operations including **Point of Sale (POS), inventory management, customer tracking, supplier management, and advanced analytics**.

The system is built using a **scalable client-server architecture** with clean REST APIs and a lightweight database for high performance.

---

## 🎥 Demo

### 🔹 Full System Walkthrough

<!-- ضع هنا لينك الفيديو

 

### 🔹 POS System Preview

<!-- ضع GIF هنا -->

---

## 🧠 Project Overview

PharmaCare Pro simulates a real-world pharmacy environment by integrating all core operations into a single platform:

* Sales processing (POS)
* Inventory & stock management
* Customer & supplier tracking
* Order lifecycle management
* Real-time analytics dashboard

The system is designed with **separation of concerns** to ensure scalability, maintainability, and performance.

---

## ✨ Key Features

### 🛒 Point of Sale (POS)

* Add products to cart with dynamic quantity control
* Real-time stock validation before checkout
* Automatic invoice generation
* QR Code support for receipt verification

---

### 📦 Inventory & Product Management

* Full CRUD operations for products
* Category-based organization
* Low stock alerts system
* Pricing and stock tracking

---

### 👥 Customer Management

* Manage customer profiles
* Track total spending and visit history
* View customer-specific orders
* Advanced search functionality

---

### 🧾 Order Management

* Create and manage orders
* Store complete order history
* Support multiple payment methods (Cash / Card / Insurance)
* Automatic stock updates after each sale

---

### 📊 Reports & Analytics

* Total revenue tracking
* Sales by category
* Payment method breakdown
* Order status distribution
* Top-selling products
* Top customers
* Daily sales trends (Chart.js)

---

### 🚚 Supplier Management

* Supplier database management
* Delivery tracking
* Supplier performance & rating system

---

### 👤 User Management

* Role-based system (Admin / Cashier)
* Full CRUD operations

---

### ⚙️ Settings

* Pharmacy information (Name, License, Contact)
* Tax configuration
* Used dynamically in invoice generation

---

## 🏗️ System Architecture


The system follows a **Client-Server Architecture**:

* **Frontend**: HTML, CSS, Vanilla JavaScript
* **Backend**: Node.js + Express.js
* **Database**: SQLite

### 🔄 Data Flow

1. Frontend communicates via Fetch API
2. Backend processes requests (Express)
3. SQLite handles data storage
4. JSON responses update UI dynamically (no reloads)

---

## 🗄️ Database Design

### 📊 ERD Diagram

![ERD](docs/erd.png)

### 🧩 Database Schema

<img width="1095" height="756" alt="Screenshot 2026-04-25 201919" src="https://github.com/user-attachments/assets/ddfa12db-664f-48a4-b11d-f06015803a9d" />


### 🔗 Relationships

* Each **Order** is linked to a specific Customer
* Each **Order** contains multiple Products via Order Items
* Each **Product** belongs to a Category

### 🧠 Design Notes

* Relational database model ensures **data integrity**
* Use of primary & foreign keys enforces relationships
* Optimized to reduce redundancy and improve query performance

---

## 🛠️ Tech Stack

### 🎨 Frontend

* HTML5
* CSS3
* Vanilla JavaScript
* Chart.js
* Font Awesome

### ⚙️ Backend

* Node.js
* Express.js

### 🗃️ Database

* SQLite (Local database)

---

## 📁 Project Structure

```
Pharmacy-System/
│── server.js          # Backend API (Express)
│── pharmacy.db        # SQLite Database
│── index.html         # Frontend UI
│── package.json       # Dependencies
│── docs/              # Documentation (ERD, Screenshots)
```

---

## 🔌 REST API Endpoints

### 📦 Products

* GET `/api/products`
* POST `/api/products`
* PUT `/api/products/:id`
* DELETE `/api/products/:id`

### 🧾 Orders

* GET `/api/orders`
* POST `/api/orders`
* GET `/api/orders/:orderId/items`

### 👥 Customers

* GET `/api/customers`
* POST `/api/customers`
* PUT `/api/customers/:id`
* DELETE `/api/customers/:id`

### 📊 Reports

* GET `/api/reports`
* GET `/api/stats`

### 🚚 Suppliers

* GET `/api/suppliers`
* POST `/api/suppliers`
* PUT `/api/suppliers/:id`
* DELETE `/api/suppliers/:id`

### 👤 Users

* GET `/api/users`
* POST `/api/users`
* PUT `/api/users/:id`
* DELETE `/api/users/:id`

### ⚙️ Settings

* GET `/api/settings`
* POST `/api/settings`

---

## ▶️ Getting Started

### 1️⃣ Install dependencies

```bash
npm install
```

### 2️⃣ Run the server

```bash
node server.js
```

### 3️⃣ Open in browser

```
http://localhost:3000
```

---

## 📈 Key Highlights

* Real-time analytics dashboard
* Clean and scalable REST API
* Lightweight and fast SQLite database
* Automatic stock updates after sales
* Modular and maintainable code structure

---

## 🔮 Future Improvements

* Authentication & Authorization (JWT)
* Multi-user login system
* Cloud database (PostgreSQL / MongoDB)
* Deployment (Render / Railway / Vercel)
* Mobile responsiveness enhancements

---

## 👨‍💻 Author

**Mahmoud Abdellateif Hamza**


---
