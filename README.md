# 🏥 SRM CARES - Hospital Management System

<div align="center">

![MERN Stack](https://img.shields.io/badge/MERN-Stack-4A154B?style=for-the-badge&logo=mongodb&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

*A comprehensive Hospital Management System built with MERN Stack*

**[🔴 Project Overview Video](#)** | **[🔵 Code Explanation Video](#)** | **[📚 Documentation](#)** | **[🚀 Live Demo](#)**

---

## 📋 Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Environment Setup](#environment-setup)
- [How to Run](#how-to-run)
- [Default Credentials](#default-credentials)
- [API Endpoints](#api-endpoints)
- [Screenshots](#screenshots)
- [Video Tutorials](#video-tutorials)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## 📖 About the Project

**SRM CARES Hospital Management System** is a comprehensive web-based application designed to streamline hospital operations. Built with the MERN Stack (MongoDB, Express, React, Node.js), this system provides efficient management of appointments, patient records, doctor schedules, and administrative tasks.

### 🎯 Project Objectives

- 📅 **Appointment Management** - Seamless scheduling and tracking of patient appointments
- 👨‍⚕️ **Doctor Portal** - Easy access for doctors to view and manage their schedules
- 🏠 **Patient Portal** - User-friendly interface for patients to book appointments
- 📊 **Admin Dashboard** - Comprehensive controls for hospital administrators
- 💬 **Messaging System** - Efficient communication between patients and staff

---

## ✨ Features

### 🔑 Key Features

| Feature | Description |
|--------|-------------|
| 🔐 **Authentication** | Secure JWT-based login with role-based access control |
| 📅 **Appointments** | Create, view, update, and cancel appointments |
| 👨‍⚕️ **Doctor Management** | Add, update, and manage doctor profiles |
| 🏥 **Patient Management** | Patient registration and record management |
| 📊 **Admin Dashboard** | Comprehensive analytics and control panel |
| 💬 **Messaging** | Contact form and message management |
| 🔔 **Notifications** | Real-time appointment status updates |
| 📱 **Responsive Design** | Works seamlessly on desktop and mobile devices |

### 👥 User Roles

- **Patient** - Book appointments, view medical history
- **Doctor** - Manage appointments, update patient records
- **Admin** - Full system control and analytics

---

## 🛠 Tech Stack

### Frontend

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) React
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) Vite
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=flat-square&logo=react-router&logoColor=white) React Router
![Axios](https://img.shields.io/badge/Axios-5A29F4?style=flat-square&logo=axios&logoColor=white) Axios
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) CSS3

### Backend

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white) Node.js
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) Express
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) MongoDB
![Mongoose](https://img.shields.io/badge/Mongoose-880000?style=flat-square&logo=mongoose&logoColor=white) Mongoose
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=json-web-tokens&logoColor=white) JWT

### Development Tools

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) Git
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white) VS Code
![npm](https://img.shields.io/badge/npm-CB3837?style=flat-square&logo=npm&logoColor=white) npm

---

## 📁 Project Structure

```
SRM-CARES-Hospital-Management-System/
├── 📂 backend/                    # Node.js Express API
│   ├── 📂 controller/            # Route controllers
│   ├── 📂 database/              # Database connection
│   ├── 📂 middlewares/           # Custom middleware
│   ├── 📂 models/                # Mongoose schemas
│   ├── 📂 router/                # API routes
│   ├── 📂 scripts/               # Bootstrap scripts
│   ├── 📂 tests/                 # Integration tests
│   ├── 📂 utils/                 # Utility functions
│   ├── 📄 app.js                 # Express app configuration
│   ├── 📄 server.js              # Server entry point
│   └── 📄 package.json           # Backend dependencies
│
├── 📂 frontend/                   # React Vite Application
│   ├── 📂 public/                # Static assets
│   ├── 📂 src/
│   │   ├── 📂 api/               # API client
│   │   ├── 📂 components/        # Reusable components
│   │   ├── 📂 Pages/            # Page components
│   │   ├── 📂 tests/             # Frontend tests
│   │   ├── 📂 utils/             # Utility functions
│   │   ├── 📄 App.jsx            # Main app component
│   │   ├── 📄 context.js         # React context
│   │   └── 📄 main.jsx           # Entry point
│   └── 📄 package.json           # Frontend dependencies
│
├── 📂 docs/                      # Documentation
│   └── 📄 button-validation-matrix.md
│
├── 📄 .gitignore                 # Git ignore rules
└── 📄 README.md                 # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites

Before running the project, ensure you have the following installed:

| Requirement | Version | Description |
|-------------|---------|-------------|
| 🟢 **Node.js** | 18+ | JavaScript runtime |
| 📦 **npm** | 9+ | Package manager |
| 🍃 **MongoDB** | Latest | Database server |

### 💻 Installation Steps

#### 1️⃣ Clone the Repository

```bash
git clone https://github.com/anushkaBala/SRM-CARES-Hospital-Management-System.git
cd SRM-CARES-Hospital-Management-System
```

#### 2️⃣ Install Backend Dependencies

```bash
cd backend
npm install
```

#### 3️⃣ Install Frontend Dependencies

```bash
cd ../frontend
npm install
```

---

## ⚙️ Environment Setup

### Backend Configuration

Create a `config.env` file in the `backend` directory:

```env
# Server Configuration
PORT=4000

# Database Configuration
MONGO_URI=mongodb://127.0.0.1:27017
MONGO_DB_NAME=MERN_STACK_HOSPITAL_MANAGEMENT_SYSTEM_DEPLOYED

# JWT Configuration
JWT_SECRET_KEY=your_super_secret_key
JWT_EXPIRES=7d

# Cookie Configuration
COOKIE_EXPIRE=604800

# Frontend URLs
FRONTEND_URL_ONE=http://localhost:5173
FRONTEND_URL_TWO=http://localhost:5174

# Appointment Settings
APPOINTMENT_ALLOW_UNKNOWN_DOCTOR=true
```

### Frontend Environment (Optional)

Create a `.env` file in the `frontend` directory:

```env
VITE_API_URL=http://localhost:4000/api/v1
VITE_APPOINTMENT_ALLOW_UNKNOWN_DOCTOR=true
```

---

## 🏃 How to Run

### Step 1: Start MongoDB

```bash
mongod
```

> 💡 **Tip:** Make sure MongoDB is running on `mongodb://127.0.0.1:27017`

### Step 2: Start the Backend Server

```bash
cd backend
npm run dev
```

The backend will run at: **http://localhost:4000**

### Step 3: Start the Frontend

```bash
cd frontend
npm run dev
```

The frontend will run at: **http://localhost:5173**

---

## 🔑 Default Credentials

After running the bootstrap script, use these credentials:

| Role | Email | Password |
|------|-------|----------|
| 👑 **Admin** | admin@hms.local | Admin@12345 |

> ⚠️ **Security Note:** Change the default admin password after first login!

---

## 🔌 API Endpoints

### Authentication Routes

| Method | Endpoint | Description | Access |
|--------|----------|-------------|--------|
| POST | `/api/v1/auth/register` | Register new user | Public |
| POST | `/api/v1/auth/login` | User login | Public |
| GET | `/api/v1/auth/logout` | User logout | Private |
| GET | `/api/v1/auth/me` | Get current user | Private |

### Appointment Routes

| Method | Endpoint | Description | Access |
|--------|----------|-------------|--------|
| POST | `/api/v1/appointments` | Create appointment | Patient |
| GET | `/api/v1/appointments` | Get all appointments | Admin/Doctor |
| GET | `/api/v1/appointments/:id` | Get appointment by ID | Private |
| PUT | `/api/v1/appointments/:id` | Update appointment | Private |
| DELETE | `/api/v1/appointments/:id` | Cancel appointment | Patient/Admin |

### User Routes

| Method | Endpoint | Description | Access |
|--------|----------|-------------|--------|
| GET | `/api/v1/users` | Get all users | Admin |
| GET | `/api/v1/users/:id` | Get user by ID | Private |
| PUT | `/api/v1/users/:id` | Update user | Private |
| DELETE | `/api/v1/users/:id` | Delete user | Admin |

### Message Routes

| Method | Endpoint | Description | Access |
|--------|----------|-------------|--------|
| POST | `/api/v1/messages` | Send message | Public |
| GET | `/api/v1/messages` | Get all messages | Admin |
| DELETE | `/api/v1/messages/:id` | Delete message | Admin |

---

## 📸 Screenshots

### 🏠 Home Page
![Home Page](frontend/public/hero.png)

### 🔐 Login Page
![Login](frontend/public/signin.png)

### 📅 Appointment Page
![Appointments](frontend/public/signupheader.png)

### 🏥 Departments
![Departments](frontend/public/departments/)

---

## 🎬 Video Tutorials

### 🔴 Project Overview Video
> 📹 **Link will be added soon** - Check back later for the project overview video demonstration.

### 🔵 Code Explanation Video
> 📹 **Link will be added soon** - Check back later for the code explanation video.

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License** - see the LICENSE file for details.

---

## 📞 Contact

### 👨‍💻 Developer

- **Name:** Anushka Bala
- **GitHub:** [anushkaBala](https://github.com/anushkaBala)
- **Email:** anushka.bala@example.com

### 📚 Project Links

- **Repository:** [https://github.com/anushkaBala/SRM-CARES-Hospital-Management-System](https://github.com/anushkaBala/SRM-CARES-Hospital-Management-System)
- **Issues:** [https://github.com/anushkaBala/SRM-CARES-Hospital-Management-System/issues](https://github.com/anushkaBala/SRM-CARES-Hospital-Management-System/issues)

---

## 🙏 Acknowledgments

- 🎓 **Smartbridge** for the opportunity to work on this project
- 📚 **SRM Institute of Science and Technology** for academic support
- 🌍 Open source community for providing excellent tools and libraries

---

<div align="center">

### ⭐ Show your support

Give a ⭐️ if this project helped you!

**[🔝 Back to Top](#)**

---

© 2024 SRM CARES - Hospital Management System | Built with ❤️ using MERN Stack
