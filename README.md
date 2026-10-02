# WeCare Hospital Management System

A responsive MERN-based Hospital Management System with role-based authentication, patient records, doctor profiles, appointment booking, dashboard analytics, and secure database integration using MongoDB.

## Tech Stack

- **Frontend:** React + TypeScript, Vite, Tailwind CSS
- **Backend:** Node.js, Express
- **Database:** MongoDB (Mongoose)
- **Auth:** JWT-based authentication

## Run Locally

**Prerequisites:** Node.js (v18+)

1. Install dependencies:
   ```bash
   npm install
   ```
2. Create a `.env` file in the project root (see `.env.example` for reference) and add your MongoDB connection string and JWT secret:
   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
   NODE_ENV=development
   PORT=3000
   ```
3. Run the app:
   ```bash
   npm run dev
   ```
4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Features

- Department listings with detailed information
- Doctor/specialist profiles
- Patient appointment booking system
- User authentication (patients & admin)
- Admin dashboard for managing doctors, departments, and appointments
