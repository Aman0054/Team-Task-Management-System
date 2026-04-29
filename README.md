# 🚀 Team Task Management System

A full-stack **Task Management Web Application** built using **Next.js (Frontend)** and **NestJS (Backend)**.
This system allows users to manage tasks efficiently with authentication and role-based features.

---

## 📌 Features

* 🔐 User Authentication (Login/Register)
* 📋 Task Creation & Management
* 👤 Role-based Access (Admin/User)
* 📊 Dashboard Overview
* 🔄 Real-time API Integration
* 🎨 Responsive UI (Next.js + Tailwind CSS)

---

## 🏗️ Project Structure

```
Team Task Management System
│
├── Nestjs-Nextjs_Team_Task_Manager-main
│   ├── backend     # NestJS API
│   ├── frontend    # Next.js UI
│
└── README.md
```

---

## ⚙️ Tech Stack

### Frontend:

* Next.js
* React.js
* Axios
* Tailwind CSS

### Backend:

* NestJS
* Node.js
* Express.js

### Others:

* REST API
* JWT Authentication

---

## 🚀 Getting Started

### 🔹 Prerequisites

Make sure you have installed:

* Node.js (v16 or above)
* npm or yarn
* VS Code (recommended)

---

## ▶️ Run Frontend

```bash
cd Nestjs-Nextjs_Team_Task_Manager-main/frontend
npm install
npm run dev
```

👉 Open in browser:
http://localhost:3000

---

## ▶️ Run Backend

```bash
cd Nestjs-Nextjs_Team_Task_Manager-main/backend
npm install
npm run start:dev
```

👉 Backend runs on:
http://localhost:3001

---

## 🔗 API Endpoints (Sample)

| Method | Endpoint    | Description     |
| ------ | ----------- | --------------- |
| GET    | /tasks      | Get all tasks   |
| POST   | /tasks      | Create new task |
| GET    | /users      | Get users       |
| POST   | /auth/login | Login user      |

---

## 🔐 Authentication

* Uses JWT Token-based authentication
* Token stored in browser localStorage
* Protected routes require valid token

---

## ⚠️ Important Notes

* Backend must be running for API data to load
* If backend is not running → frontend may show empty data or errors
* Ensure correct API base URL (`http://localhost:3001`)

---

## 🧪 Testing the App

1. Start backend server
2. Start frontend server
3. Open browser
4. Register a new user
5. Login and manage tasks

---

## ❌ Common Issues

### Axios Network Error

👉 Ensure backend is running on correct port

### Port Already in Use

```bash
npm run dev -- -p 3002
```

### Node Modules Missing

```bash
npm install
```

---

## 📸 Screens (Optional)

* Login Page
* Dashboard
* Admin Panel

(Add screenshots here if needed)

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork the repository and submit a pull request.

---

## 📄 License

This project is for educational purposes.

---

## 👨‍💻 Author

Developed by **Aman Kumar**

---

## ⭐ Acknowledgements

* Next.js Documentation
* NestJS Documentation
* Open Source Community

---

