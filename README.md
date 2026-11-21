# 🚀 TeamPulse – Smart Team Availability Tracker

TeamPulse is a smart team availability and collaboration platform that helps teams track member availability and monitor real-time status. It makes team coordination easier with live updates and a centralized dashboard.

## ✨ Features

- 👤 User Registration and Login
- 🔐 Secure Authentication using JWT
- 🟢 Track Team Members' Availability
- ⚡ Real-Time Updates using Socket.IO
- 📊 Team Dashboard
- 🗂️ MongoDB Database Integration
- 📱 Modern and Responsive User Interface

## 🛠️ Tech Stack

**Frontend**
- React.js
- Vite
- CSS

**Backend**
- Node.js
- Express.js
- Socket.IO

**Database**
- MongoDB
- Mongoose

**Authentication**
- JSON Web Token (JWT)

## 📁 Project Structure

```text
TeamPulse/
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── App.jsx
│   ├── package.json
│   └── .env.example
│
├── backend/
│   ├── models/
│   ├── middleware/
│   ├── routes/
│   ├── server.js
│   ├── seed.js
│   ├── package.json
│   └── .env.example
│
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd TeamPulse
```

### 2. Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file inside the backend folder:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
CLIENT_URL=http://localhost:5173
```

Run the backend:

```bash
npm run dev
```

### 3. Frontend Setup

Open another terminal:

```bash
cd frontend
npm install
```

Create a `.env` file inside the frontend folder:

```env
VITE_API_URL=http://localhost:5000
```

Start the frontend:

```bash
npm run dev
```

### 4. Open the Application

```text
http://localhost:5173
```

## 🔒 Environment Variables

Never upload your actual `.env` files, MongoDB credentials, or JWT secrets to GitHub.

Use `.env.example` files to show the required environment variables.

## 🎯 Project Goal

The main goal of TeamPulse is to simplify team availability tracking and improve collaboration through real-time updates.

## 👩‍💻 Developer

**Madhumitha S**

Information Technology Student | Aspiring Full-Stack Developer

---

⭐ If you find this project interesting, consider giving it a star!
