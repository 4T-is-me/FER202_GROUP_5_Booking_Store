# Online Book Store Management System (OBSM)

**Final Project - FER202 - SE1909**  
**FPT University**

---

## 📋 Project Overview

A full-featured **Online Book Store Management System** that allows customers to browse and purchase books online, while providing administrators with powerful tools to manage inventory, orders, users, and categories.

The system is built using **modern JavaScript (ES6+)** on the backend with a clean Client-Server architecture.

---

## 👥 Group 5 Members

| Student ID   | Full Name                  |
|--------------|----------------------------|
| CE200008     | Nguyễn An Bình             |
| CE191027     | Tô Thị Thảo Trang          |
| CE190492     | Nguyễn Hữu Lập             |
| CE191422     | Đặng Hữu Thạnh             |
| CE191088     | Trần Ngọc Linh Đang        |

**Mentor:** ThanhNG

---

## 🛠️ Technology Stack

### Backend (Server)
- **Language**: JavaScript (ES6+)
- **Runtime**: Node.js
- **Architecture**: RESTful API

### Frontend (Client)
- **Framework**: React.js
- **HTTP Client**: Axios

### Database
- **Type**: JSON Database (File-based)

---

## 🏗️ System Architecture

The system follows a **Client-Server** model:

- **Frontend** (React.js) communicates with the **Backend** via Axios.
- **Backend** (Node.js + ES6+) handles all business logic, authentication, validation, and database operations.
- Data is stored in JSON files and synchronized in real-time.

---

## ✨ Key Features

### Customer Side
- Book browsing & searching (title, author, genre)
- Detailed book view
- Category filtering
- Shopping Cart (add, update, remove)
- User registration, login, and profile management
- Smooth checkout process

### Admin Side
- **Book Management** (Full CRUD)
- **Category Management** (CRUD + status control)
- **User Management** (Account control & history)
- **Order Management** (Lifecycle tracking: Pending → Processing → Shipping → Delivered)
- **Dashboard** with statistics (Total books, revenue, stock alerts)

---

## 📌 Business Logic & Rules

- Stock validation before placing orders
- Automatic stock deduction on order confirmation
- Auto-restock when order is cancelled
- Revenue calculated only from **Delivered** orders
- Final order states (Delivered / Cancelled) are locked

---

---

## 🚀 How to Run

1. Clone the repository
git clone https://github.com/4T-is-me/FER202_GROUP_5_Booking_Store.git


2. Install Dependencies
npm install

3. Start Frontend
npm run dev

4. Start JSON Server
npm run server
