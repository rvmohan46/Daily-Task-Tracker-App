# Daily-Task-Tracker-App
# 📝 Daily Task Tracker App

A simple and responsive full stack web application that helps users manage their daily tasks. Built using **MERN Stack** (MongoDB, Express, React, Node.js), with user authentication and clean UI.

---

## 🚀 Features

- 🔐 User Signup / Login / Logout (JWT Authentication)
- ➕ Add tasks
- ✅ Mark tasks as completed
- ❌ Delete tasks
- 📱 Responsive design (Mobile & Desktop)
- 🌙 Optional: Dark Mode Toggle

---

## 🛠️ Tech Stack

**Frontend**  
- React  
- Tailwind CSS / Plain CSS  
- Axios  

**Backend**  
- Node.js  
- Express.js  
- MongoDB with Mongoose  
- JSON Web Tokens (JWT)  
- bcrypt (for password hashing)  
- dotenv (for environment variables)

---

## 📂 Folder Structure

task-tracker/
│
├── client/ # React Frontend
│ ├── public/
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ └── App.js
│
├── server/ # Express Backend
│ ├── models/ # Mongoose models
│ ├── routes/ # API routes
│ ├── controllers/ # Logic for routes
│ ├── middleware/ # Auth middleware
│ └── server.js
│
└── .env # Store DB_URI and JWT_SECRET


---

## ⚙️ Installation & Running Locally

### 🔧 Prerequisites
- Node.js and npm installed
- MongoDB local or cloud (MongoDB Atlas)
  
### 🖥️ Clone the repository
```bash
git clone https://github.com/your-username/task-tracker.git
cd task-tracker
cd server
npm install
# Add .env with the following:
# MONGO_URI=your_mongo_uri
# JWT_SECRET=your_jwt_secret
npm start

cd client
npm install
npm start
