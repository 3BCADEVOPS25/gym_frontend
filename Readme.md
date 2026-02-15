🏋️ Gym Management System – Frontend
🚀 Live Application

🌐 Deployed on Vercel: https://gym-frontend-theta.vercel.app


📌 Project Overview

This is the Frontend of the Gym Management System — a full-stack CRUD application built using React + Vite.

The frontend provides a clean, responsive user interface for managing:

Gym Members

Trainers

Membership Plans

It communicates with a Spring Boot backend using REST APIs.

✨ Features

✅ Add new members

✅ View all members

✅ Update member details

✅ Delete members

✅ Trainer management UI

✅ Membership plan management

✅ Responsive design

✅ API integration with backend

✅ Dockerized deployment

✅ Hosted on Vercel

🛠️ Technologies Used
⚛️ Frontend Stack

React

Vite

JavaScript (ES6+)

HTML5

CSS3

Bootstrap (if used)

🌐 Deployment

Vercel

🐳 Containerization

Docker

Nginx (Production build server)

📂 Project Structure
gym_frontend/
│
├── client/
│   ├── src/
│   ├── public/
│   ├── package.json
│   ├── vite.config.js
│   └── Dockerfile
│
└── README.md

🔌 Backend Connection

Make sure your backend is running at:

http://localhost:8080


Update API base URL inside your frontend if deploying to production:

const API_BASE_URL = "https://your-backend-url.com";

🚀 Running Locally
1️⃣ Install Dependencies
npm install

2️⃣ Start Development Server
npm run dev


Open:

http://localhost:5173

🐳 Running with Docker
Build Docker Image
docker build -t gym-frontend ./client

Run Container
docker run -p 3000:80 gym-frontend


Open:

http://localhost:3000

🌍 Deployment (Vercel)

Push code to GitHub

Import project in Vercel

Select root directory (client folder if needed)

Deploy

🎯 Learning Outcomes

React Component Architecture

API Integration

State Management

Vite Build Optimization

Docker for Frontend
---
