Team-Task-Management-System
A full-stack Role-Based Task Management System built with NestJS (Backend) and Next.js (Frontend). The application allows administrators to manage users, assign tasks, set priorities, verify completion, and monitor analytics through an admin dashboard. Users can view assigned tasks, track priorities, and mark tasks as completed.

This project demonstrates JWT authentication, role-based access control, task management, and dashboard analytics in a modern full-stack architecture.

Project Overview
This system is designed for team collaboration and task management.

Admin users have full control over tasks and users, while normal users can only manage tasks assigned to them. The system includes analytics to monitor task progress and completion.

Features
Authentication
User Registration
User Login
JWT Authentication
Role-Based Access Control (Admin / User)
Admin Features
Admin Dashboard
View dashboard statistics
Create and assign tasks to users
Set task priority (Low / Medium / High)
Verify completed tasks
Delete tasks
View task creator
Manage users
Delete users (admin accounts protected)
User Features
View assigned tasks
See task priority
Mark tasks as completed
Track task status
Tech Stack
Frontend
Next.js
React
Axios
Tailwind CSS
Backend
NestJS
TypeORM
PostgreSQL
JWT Authentication
Passport.js
Project Structure
project-root
│
├── backend
│   ├── src
│   │   ├── auth
│   │   │   ├── auth.controller.ts
│   │   │   ├── auth.service.ts
│   │   │   └── jwt.strategy.ts
│   │   │
│   │   ├── users
│   │   │   ├── user.entity.ts
│   │   │   ├── users.controller.ts
│   │   │   └── users.service.ts
│   │   │
│   │   ├── tasks
│   │   │   ├── task.entity.ts
│   │   │   ├── tasks.controller.ts
│   │   │   └── tasks.service.ts
│   │   │
│   │   └── main.ts
│
├── frontend
│   ├── pages
│   │   ├── admin.js
│   │   ├── dashboard.js
│   │   ├── login.js
│   │   ├── register.js
│   │   └── components
│   │       └── Navbar.js
│
└── README.md
Installation Guide
Clone Repository
git clone https://github.com/Hashim-stack/Nestjs-Nextjs_Team_Task_Manager.git
Backend Setup
Navigate to backend folder:

cd backend
Install dependencies:

npm install
Create .env file:

DATABASE_HOST=localhost
DATABASE_PORT=5432
DATABASE_USER=postgres
DATABASE_PASSWORD=yourpassword
DATABASE_NAME=taskmanager
JWT_SECRET=secretKey
Start backend server:

npm run start:dev
Backend will run on:

http://localhost:3001
Frontend Setup
Navigate to frontend folder:

cd frontend
Install dependencies:

npm install
Run development server:

npm run dev
Frontend will run on:

http://localhost:3000
API Endpoints
Authentication
POST /auth/register
POST /auth/login
Tasks
GET /tasks
POST /tasks
PUT /tasks/:id
PUT /tasks/:id/complete
PUT /tasks/:id/priority
DELETE /tasks/:id
GET /tasks/stats
Users
GET /users
DELETE /users/:id
Dashboard Analytics
The admin dashboard provides analytics including:

Total Tasks
Completed Tasks
Pending Tasks
These statistics update automatically when tasks are completed or created.


