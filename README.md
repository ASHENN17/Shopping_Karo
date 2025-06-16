# 🛒 Shopping Karo – Full Stack E-commerce Platform

**Shopping Karo** is a full-stack e-commerce web application that includes:

- 🧑‍💼 **Admin Panel** (React + Tailwind)
- 🛍️ **User Frontend** (React or HTML/CSS/JS)
- 🔙 **Backend API** (Node.js + Express + MongoDB or SQL)

---

## 📦 Tech Stack

| Layer         | Tech Used                          |
|---------------|------------------------------------|
| Admin Panel   | React, Vite, Tailwind CSS          |
| User Frontend | React / HTML, CSS, JavaScript      |
| Backend       | Node.js, Express.js, MongoDB (or SQL) |
| Auth          | JWT, bcrypt                        |
| APIs          | RESTful APIs                       |

---

## 📁 Folder Structure

Shopping Karo/
├── admin/ # React Admin Panel (Vite + Tailwind)
├── frontend/ # Customer-facing site (React or HTML/CSS/JS)
└── backend/ # Express API with DB

---
Features
Product listing and management

User authentication & authorization

Cart & checkout

Admin dashboard for managing orders, users, inventory

Toast notifications & error handling

## 🚀 Getting Started

### 🔧 Backend Setup


cd backend
npm install
# Create .env file with DB_URI, JWT_SECRET, etc.
npm run dev

Frontend Setup 

cd frontend
npm install
npm run dev


Admin Panel Setup

cd admin
npm install
npm run dev

Scripts
Folder	       Script	         Description
backend	       npm run dev	   Starts Express server
frontend       npm run dev	   Starts User frontend
admin          npm run dev	   Starts Admin Panel (Vite)

nvironment Variables
Create a .env file in both admin/ and backend/ folders. Example:

For Backend

PORT=5000
DB_URI=mongodb://localhost:27017/shoppingkaro
JWT_SECRET=your_jwt_secret

License
This project is licensed under the (Shopping-Karo) License.

Author
Developed by Ashish Pandey
Connect on LinkedIn or GitHub for collaboration.

----
