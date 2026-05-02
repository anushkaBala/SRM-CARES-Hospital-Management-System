# 🏥 MedlyPharma Hospital Management System

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient:4A154B,00D4FF&height=300&section=header&text=MedlyPharma&fontSize=90" width="100%" />
</p>

<div align="center">

[![MERN Stack](https://img.shields.io/badge/MERN-Stack-4A154B?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev/)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)
[![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)
[![Stars](https://img.shields.io/github/stars/anushkaBala/SRM-CARES-Hospital-Management-System?style=for-the-badge)](https://github.com/anushkaBala/SRM-CARES-Hospital-Management-System/stargazers)
[![Forks](https://img.shields.io/github/forks/anushkaBala/SRM-CARES-Hospital-Management-System?style=for-the-badge)](https://github.com/anushkaBala/SRM-CARES-Hospital-Management-System/network)

*A comprehensive Hospital Management System built with the powerful MERN Stack*

**[📹 Project Overview](#)** · **[📺 Code Explanation](#)** · **[🚀 Live Demo](#)** · **[🤝 Contributing](#)** · **[📌 Issues](#)**

</div>

---

## ✨ Features at a Glance

| 🔐 **Authentication** | 📅 **Appointments** | 👨‍⚕️ **Doctors** | 💬 **Messaging** |
|:---:|:---:|:---:|:---:|
| JWT-based | Seamless Scheduling | Profile Management | Contact System |
| Role-based Access | Booking & Tracking | Availability | Real-time Updates |

| 🏥 **Patients** | 📊 **Dashboard** | 🔔 **Notifications** | 📱 **Responsive** |
|:---:|:---:|:---:|:---:|
| Portal Access | Analytics & Controls | Status Updates | Mobile-friendly |

---

## 🛠️ Tech Stack

### Frontend ⚡

|<img src="https://skillicons.dev/icons?i=react,vite,css,html,js"/>&#8205;|
|:---:|
| **React** · **Vite** · **CSS3** · **HTML5** · **JavaScript** |

### Backend 🖥️

|<img src="https://skillicons.dev/icons?i=nodejs,express,mongodb,js"/>&#8205;|
|:---:|
| **Node.js** · **Express** · **MongoDB** · **JavaScript** |

### Development Tools 🔧

|<img src="https://skillicons.dev/icons?i=git,vscode,npm,postman"/>&#8205;|
|:---:|
| **Git** · **VS Code** · **npm** · **Postman** |

---

## 📁 Project Architecture

```
medlypharma-hms/
│
├── 🚀 backend/                    # Node.js Express API
│   ├── 📂 controller/             # Business logic handlers
│   │   ├── appointmentController.js
│   │   ├── dashboardController.js
│   │   ├── messageController.js
│   │   └── userController.js
│   │
│   ├── 📂 database/               # Database connections
│   │   └── dbConnection.js
│   │
│   ├── 📂 middlewares/           # Custom middleware
│   │   ├── auth.js               # JWT authentication
│   │   ├── catchAsyncErrors.js   # Error handling
│   │   ├── error.js             # Error middleware
│   │   ├── rateLimiter.js       # Rate limiting
│   │   └── roleMiddleware.js    # Role-based access
│   │
│   ├── 📂 models/                # Mongoose schemas
│   │   ├── appointmentSchema.js
│   │   ├── billingSchema.js
│   │   ├── messageSchema.js
│   │   └── userSchema.js
│   │
│   ├── 📂 router/                # API route definitions
│   │   ├── adminRouter.js
│   │   ├── appointmentRouter.js
│   │   ├── billingRouter.js
│   │   ├── dashboardRouter.js
│   │   ├── messageRouter.js
│   │   └── userRouter.js
│   │
│   ├── 📂 scripts/               # Bootstrap & setup scripts
│   │   ├── bootstrapAdmin.js
│   │   └── createAdmin.js
│   │
│   ├── 📂 tests/                 # Integration tests
│   │   └── integration/
│   │       └── auth-and-guard-routes.test.js
│   │
│   ├── 📂 utils/                 # Utility functions
│   │   ├── constants.js
│   │   └── jwtToken.js
│   │
│   ├── 📄 app.js                 # Express app configuration
│   ├── 📄 server.js              # Server entry point
│   └── 📄 package.json           # Dependencies
│
├── 💻 frontend/                  # React Vite Application
│   ├── 📂 public/                # Static assets & images
│   │   ├── departments/
│   │   │   ├── cardio.jpg
│   │   │   ├── derma.jpg
│   │   │   ├── ent.jpg
│   │   │   ├── neuro.jpg
│   │   │   ├── onco.jpg
│   │   │   ├── ortho.jpg
│   │   │   ├── pedia.jpg
│   │   │   ├── radio.jpg
│   │   │   └── therapy.jpg
│   │   ├── about.png
│   │   ├── contact.png
│   │   ├── hero.png
│   │   ├── logo.png
│   │   ├── services.png
│   │   ├── signin.png
│   │   ├── signupheader.png
│   │   └── Vector.png
│   │
│   ├── 📂 src/                   # Source code
│   │   ├── 📂 api/              # API client
│   │   │   └── client.js
│   │   │
│   │   ├── 📂 components/        # Reusable components
│   │   │   ├── AppointmentForm.jsx
│   │   │   ├── Biography.jsx
│   │   │   ├── Departments.jsx
│   │   │   ├── Footer.jsx
│   │   │   └── Hero.jsx
│   │   │
│   │   ├── 📂 Pages/             # Page components
│   │   │
│   │   ├── 📂 tests/            # Frontend tests
│   │   │
│   │   ├── 📂 utils/            # Utility functions
│   │   │
│   │   ├── 📄 App.css          # Global styles
│   │   ├── 📄 App.jsx          # Main component
│   │   ├── 📄 context.js      # React context
│   │   └── 📄 main.jsx        # Entry point
│   │
│   ├── 📄 package.json          # Dependencies
│   ├── 📄 vite.config.js       # Vite configuration
│   └── 📄 vitest.config.js    # Vitest configuration
│
├── 📄 docs/                     # Documentation
│   └── button-validation-matrix.md
│
├── 📄 .gitignore                # Git ignore rules
└── 📄 README.md                # This file
```

---

## 🚦 Getting Started

### Prerequisites

Ensure you have the following installed:

|<div align="center">📦</div>|Version|Description|
|:---|:---:|:---|
|🟢 **Node.js**|18+|JavaScript runtime|
|📦 **npm**|9+|Package manager|
|🍃 **MongoDB**|Latest|Database server|

### ⚡ Quick Start

```bash
# 1️⃣ Clone the repository
git clone https://github.com/anushkaBala/SRM-CARES-Hospital-Management-System.git
cd SRM-CARES-Hospital-Management-System

# 2️⃣ Install backend dependencies
cd backend
npm install

# 3️⃣ Install frontend dependencies
cd ../frontend
npm install

# 4️⃣ Configure environment
# Create backend/config.env with required variables

# 5️⃣ Run MongoDB
mongod

# 6️⃣ Start backend (Terminal 1)
cd backend
npm run dev

# 7️⃣ Start frontend (Terminal 2)
cd frontend
npm run dev
```

---

## ⚙️ Environment Configuration

### Backend Configuration

Create `backend/config.env`:

```env
# Server
PORT=4000

# Database
MONGO_URI=mongodb://127.0.0.1:27017
MONGO_DB_NAME=MERN_STACK_HOSPITAL_MANAGEMENT_SYSTEM_DEPLOYED

# JWT
JWT_SECRET_KEY=your_super_secret_key
JWT_EXPIRES=7d
COOKIE_EXPIRE=604800

# CORS
FRONTEND_URL_ONE=http://localhost:5173
FRONTEND_URL_TWO=http://localhost:5174

# Settings
APPOINTMENT_ALLOW_UNKNOWN_DOCTOR=true
```

### Frontend Environment (Optional)

Create `frontend/.env`:

```env
VITE_API_URL=http://localhost:4000/api/v1
VITE_APPOINTMENT_ALLOW_UNKNOWN_DOCTOR=true
```

---

## 🔌 API Endpoints

### Authentication

| Method | Endpoint | Description | Access |
|:---:|:---|:---|:---:|
|� POST|`/api/v1/auth/register`|Register new user|Public|
|� POST|`/api/v1/auth/login`|User login|Public|
|� GET|`/api/v1/auth/logout`|User logout|Private|
|� GET|`/api/v1/auth/me`|Get current user|Private|

### Appointments

| Method | Endpoint | Description | Access |
|:---:|:---|:---|:---:|
|� POST|`/api/v1/appointments`|Create appointment|Patient|
|� GET|`/api/v1/appointments`|Get all appointments|Admin/Doctor|
|� GET|`/api/v1/appointments/:id`|Get by ID|Private|
|� PUT|`/api/v1/appointments/:id`|Update appointment|Private|
|� DELETE|`/api/v1/appointments/:id`|Cancel appointment|Patient/Admin|

### Users

| Method | Endpoint | Description | Access |
|:---:|:---|:---|:---:|
|� GET|`/api/v1/users`|Get all users|Admin|
|� GET|`/api/v1/users/:id`|Get user by ID|Private|
|� PUT|`/api/v1/users/:id`|Update user|Private|
|� DELETE|`/api/v1/users/:id`|Delete user|Admin|

### Messages

| Method | Endpoint | Description | Access |
|:---:|:---|:---|:---:|
|� POST|`/api/v1/messages`|Send message|Public|
|� GET|`/api/v1/messages`|Get all messages|Admin|
|� DELETE|`/api/v1/messages/:id`|Delete message|Admin|

---

## 🔑 Default Credentials

After bootstrap, use:

| Role | Email | Password |
|:---:|:---|:---:|
|👑 **Admin**|`admin@hms.local`|`Admin@12345`|

> ⚠️ **Security Note:** Change the default password immediately after first login!

---

## 📸 Screenshots

|<img src="frontend/public/hero.png" width="400"/>|<img src="frontend/public/signin.png" width="400"/>|
|:---:|:---:|
|🏠 Home Page|🔐 Login Page|

|<img src="frontend/public/signupheader.png" width="400"/>|<img src="frontend/public/departments/cardio.jpg" width="400"/>|
|:---:|:---:|
|📅 Appointments|🏥 Departments|

---

## 🤝 Contributing

Contributions make the open-source community great! Here's how you can help:

1. 🍴 **Fork** the repository
2. 🔀 **Create** your feature branch (`git checkout -b feature/AmazingFeature`)
3. 💾 **Commit** your changes (`git commit -m 'Add AmazingFeature'`)
4. 📤 **Push** to the branch (`git push origin feature/AmazingFeature`)
5. 🔃 **Open** a Pull Request

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 🙏 Acknowledgments

- 🎓 **Smartbridge** for the opportunity
- 📚 **MedlyPharma** for institutional support
- 🌍 Open source community

---

## 📞 Contact

|<div align="center">👨‍💻</div>|
|:---:|
|**Developer**: Anushka Bala|
|**GitHub**: [anushkaBala](https://github.com/anushkaBala)|
|**Email**: anushka.bala@example.com|

---

<div align="center">

### 💙 Show Your Support

[![Stars](https://img.shields.io/github/stars/anushkaBala/SRM-CARES-Hospital-Management-System?style=social)](https://github.com/anushkaBala/SRM-CARES-Hospital-Management-System/stargazers)
[![Forks](https://img.shields.io/github/forks/anushkaBala/SRM-CARES-Hospital-Management-System?style=social)](https://github.com/anushkaBala/SRM-CARES-Hospital-Management-System/network)

Give a ⭐️ if this project helped you!

**[🔝 Back to Top](#)**

---

© 2024 MedlyPharma - Hospital Management System | Built with ❤️ using MERN Stack

</div>
