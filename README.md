Appointy – Doctor Appointment Booking System


A full-stack MERN application for booking and managing doctor appointments with role-based authentication and simulated online payments.

🚀 Key Features

User authentication (JWT-based)

Doctor listing & availability management

Appointment booking & cancellation

Admin dashboard

Role-based access control

Payment simulation (Demo Mode for deployment)

🛠 Tech Stack

Frontend: React (Vite), Axios, Context API
Backend: Node.js, Express.js
Database: MongoDB (Mongoose)
Authentication: JWT

⚙️ Installation
Backend
cd backend
npm install
npm run server

Create .env:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
CURRENCY=INR
Frontend
cd frontend
npm install
npm run dev
📌 Notes

Payment gateway integration replaced with Demo Mode for easy deployment.

Designed to demonstrate full-stack architecture, REST APIs, authentication, and database design.
