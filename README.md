#  CS Department

### 🧩 Overview

Cs Department is a modern full-stack MERN application that serves as a comprehensive portal for students, featuring institute details, a personalized Dashboard, and an AI Chatbot for academic support.

This project demonstrates:

🎓 Centralized information (Programs, Faculty, FAQs)

🤖 AI-powered student assistance

✉ Gmail-integrated contact system

🔐 Secure MERN stack with a responsive React frontend

---

## 🚀 Setup Instructions

### Clone the Repository
git clone https://github.com/awd136101021/Login-System-with-LocalStorage-and-without-Models---Quiz-1

### Backend Setup
Navigate to the backend folder:
cd backend

*Rename .env.txt to .env*

### Example .env content in backend folder:
# Server Configuration
PORT=5000
# MongoDB Connection
MONGO_URI=mongodb://127.0.0.1:27017/uog_users
# JWT Secret Key (Keep this private!)
JWT_SECRET=YourKey

### Run the backend server:
node server.js
Your backend will start on: http://localhost:5000

### Frontend Setup

Open a new terminal and navigate to the frontend folder:
cd frontend

### Install dependencies:
npm install



### Run the frontend
npm run dev

#### Frontend will be available at:
http://localhost:5173

### 📂 Folder Overview
Folder	                         Description
backend/src/controllers	         Contains all logic for handling routes and API requests
backend/src/routes	             Contains API route definitions for authentication.
backend/src/models	             Mongoose schemas for MongoDB collections
frontend/src/pages	             All main pages like Home, Dashboard, and ContactUs
frontend/src/components	         Reusable UI components such as Header, Footer ,Chatbot etc.

### How It Works

### Authentication Flow
- Users can Sign Up with full validation (name, email, password).
- Passwords are hashed using bcrypt before saving to MongoDB.
- On Sign In, a JWT token is generated and stored in sessionStorage.

### Future Improvements
The services section still needs some modifications for proper data display and a more user-friendly experience.
A Forgot Password feature will be added soon for better user access.

### 🧑‍💻 Author

*Developed by:* Abdullah Tanveer,Insha Fakhar and Anza Imtiaz
