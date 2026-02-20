🏥 Appointy – Doctor Appointment Booking System (Demo Mode)

A full-stack MERN application for booking doctor appointments with authentication, admin/doctor management, and simulated online payments (Demo Mode).

⚠️ Note: Payment gateway is currently in Demo Mode (Razorpay removed for deployment purposes).

🚀 Features
👤 User

Register / Login

Browse doctors

Book appointments

View appointment history

Online payment (Demo Mode)

Cancel appointments

👨‍⚕️ Doctor

Login

View appointments

Update availability

Manage profile

🛠️ Admin

Add new doctors

Manage all appointments

View platform statistics

🛠️ Tech Stack
Frontend

React (Vite)

Axios

React Router

Context API

CSS

Backend

Node.js

Express.js

MongoDB

Mongoose

JWT Authentication

💳 Payment System

Originally integrated with Razorpay.

For deployment/demo purposes:

Razorpay SDK removed

Backend payment APIs simulate success

Appointments are marked as paid automatically

This allows the project to run without KYC or API keys.

📁 Project Structure
Appointy/
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── server.js
│
├── frontend/
│   ├── src/
│   ├── pages/
│   ├── components/
│   ├── main.jsx
│
└── README.md

Create a .env file inside backend:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
CURRENCY=INR
3️⃣ Frontend Setup
cd frontend
npm install
npm run dev
🌐 Deployment

Frontend can be deployed on:

Vercel

Netlify

Backend can be deployed on:

Render

Railway

Since payment is in Demo Mode, no payment gateway configuration is required.

🎯 Purpose of Project

This project demonstrates:

Full-stack MERN architecture

REST API integration

Authentication & authorization

Role-based dashboards

Database design

Deployment readiness

📌 Future Improvements

Re-enable Razorpay/Stripe integration

Add email notifications

Add appointment reminders

Improve UI responsiveness

Add payment history tracking
