# Zoom-App-Clone

A **Zoom-like video conferencing app** built with the **MERN Stack**. Supports **real-time video calls, chat, and screen sharing** with secure authentication.

---

## 🚀 Features
- Real-time **video/audio calls** using **WebRTC + Socket.io**  
- **Chat & Screen Sharing** during meetings  
- **JWT + Bcrypt** for secure login & role-based access  
- **RESTful APIs** with Express.js & Mongoose  
- **Responsive UI** built with React + Tailwind CSS  
- **CORS & HTTP status handling** for secure API communication  

---

## 🛠️ Tech Stack
**Frontend:** React, Tailwind CSS  
**Backend:** Node.js, Express.js  
**Database:** MongoDB + Mongoose  
**Real-time:** WebRTC, Socket.io  
**Auth:** JWT, Bcrypt  

---

## ⚙️ Setup
git clone https://github.com/abhay-0907/zoom-clone.git
cd zoom-clone

# Install client
cd client && npm install

# Install server
cd ../server && npm install

# Create .env in server/:
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret

# Run:
cd server && npm run dev   # backend
cd client && npm start     # frontend
