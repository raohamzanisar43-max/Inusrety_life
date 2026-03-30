# 🛡️ Inusrety Life

A modern full-stack insurance management system built with **TypeScript (Frontend)** and **FastAPI (Backend)**.
This project aims to simplify insurance processes including user management, policy handling, and real-time communication.

---

## 🚀 Features

* 🔐 Secure Authentication (JWT आधारित login/register)
* 👤 User Management System
* 📄 Insurance Policy Management
* 💬 Real-time Chat System (WebSockets)
* 📊 Dashboard-ready APIs
* ⚡ Fast and scalable backend using FastAPI
* 🧠 Clean and modular architecture

---

## 🏗️ Tech Stack

### 🔹 Frontend

* TypeScript
* React (Vite)
* Tailwind CSS

### 🔹 Backend

* FastAPI
* PostgreSQL
* SQLAlchemy
* JWT Authentication
* WebSockets (for real-time chat)

---

## 📁 Project Structure

```
inusrety-life/
│
├── frontend/        # React + TypeScript app
├── backend/         # FastAPI backend
│
├── README.md
└── requirements.txt
```

---

## ⚙️ Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/yourusername/inusrety-life.git
cd inusrety-life
```

---

### 2️⃣ Backend Setup (FastAPI)

```bash
cd backend

python -m venv venv
venv\Scripts\activate   # Windows

pip install -r requirements.txt
uvicorn src.main:app --reload
```

---

### 3️⃣ Frontend Setup (TypeScript)

```bash
cd frontend

npm install
npm run dev
```

---

## 🔑 Environment Variables

Create a `.env` file in backend:

```
DATABASE_URL=your_database_url
SECRET_KEY=your_secret_key
ALGORITHM=HS256
ACCESS_TOKEN_EXPIRE_MINUTES=30
```

---

## 📡 API Documentation

Once server is running, visit:

```
http://127.0.0.1:8000/docs
```

---

## 🚀 Future Improvements

* 🧾 Payment Integration
* 📧 Email Notifications
* 📊 Analytics Dashboard
* 🔔 Push Notifications
* 👥 Role-based Access Control (Admin/User)

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Rao Hamza**
Aspiring Full Stack Developer 🚀
