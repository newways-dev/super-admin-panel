# 🎯 Super Admin Panel

<div align="center">

![React](https://img.shields.io/badge/React-17.0.2-61DAFB?style=for-the-badge&logo=react&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-9.6.0-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Redux](https://img.shields.io/badge/Redux-4.1.2-764ABC?style=for-the-badge&logo=redux&logoColor=white)
![CoreUI](https://img.shields.io/badge/CoreUI-4.1.0-6F42C1?style=for-the-badge&logo=bootstrap&logoColor=white)

**A modern, full-featured admin panel built with React and Firebase**

*This project was developed as a simple learning assignment for a freelance client*

[Features](#-features) • [Tech Stack](#-tech-stack) • [Installation](#-installation) • [Usage](#-usage)

</div>

---

## 📖 About

Super Admin Panel is a comprehensive administrative dashboard designed to manage companies, employees, job positions, and contracts. The application features a dual-role system supporting both **Administrator** and **Company** user types, each with distinct permissions and functionalities.

This project was created as a learning exercise for a freelance assignment, demonstrating modern React development practices, state management with Redux, and Firebase integration for backend services.

---

## ✨ Features

### 🔐 Authentication & Authorization
- Secure login/registration system
- Role-based access control (Admin/Company)
- Protected routes with authentication guards

### 👨‍💼 Admin Features
- **Company Management**: Create, view, edit, and manage company profiles
- **Contract Templates**: Design and manage reusable contract templates
- **Job Management**: Create and manage job positions across the platform
- **Template System**: Build custom contract templates for different use cases

### 🏢 Company Features
- **Employee Management**: Add, edit, and manage employee records
- **Company Settings**: Configure company profile and preferences
- **Job Selection**: Browse and select available job positions
- **Contract Creation**: Generate contracts for employees using templates

### 🎨 User Experience
- Modern, responsive UI built with CoreUI
- Intuitive navigation and sidebar menu
- Clean, professional design
- Smooth user interactions

---

## 🛠 Tech Stack

### Frontend
<div align="center">

| Category | Technology | Version |
|----------|-----------|---------|
| **Framework** | ![React](https://img.shields.io/badge/React-17.0.2-61DAFB?logo=react&logoColor=white) | 17.0.2 |
| **UI Library** | ![CoreUI](https://img.shields.io/badge/CoreUI-4.1.0-6F42C1?logo=bootstrap&logoColor=white) | 4.1.0 |
| **State Management** | ![Redux](https://img.shields.io/badge/Redux_Toolkit-1.6.2-764ABC?logo=redux&logoColor=white) | 1.6.2 |
| **Routing** | ![React Router](https://img.shields.io/badge/React_Router-5.3.0-CA4245?logo=react-router&logoColor=white) | 5.3.0 |
| **Styling** | ![SASS](https://img.shields.io/badge/SASS-1.43.5-CC6699?logo=sass&logoColor=white) | 1.43.5 |
| **Charts** | ![Chart.js](https://img.shields.io/badge/Chart.js-3.6.0-FF6384?logo=chart.js&logoColor=white) | 3.6.0 |

</div>

### Backend & Services
<div align="center">

| Service | Technology | Version |
|---------|-----------|---------|
| **Database** | ![Firebase](https://img.shields.io/badge/Firebase_Firestore-9.6.0-FFCA28?logo=firebase&logoColor=black) | 9.6.0 |
| **Storage** | ![Firebase Storage](https://img.shields.io/badge/Firebase_Storage-9.6.0-FFCA28?logo=firebase&logoColor=black) | 9.6.0 |
| **Authentication** | ![Firebase Auth](https://img.shields.io/badge/Firebase_Auth-9.6.0-FFCA28?logo=firebase&logoColor=black) | 9.6.0 |

</div>

### Development Tools
<div align="center">

![Node.js](https://img.shields.io/badge/Node.js-≥10-339933?logo=node.js&logoColor=white)
![NPM](https://img.shields.io/badge/NPM-≥6-CB3837?logo=npm&logoColor=white)
![ESLint](https://img.shields.io/badge/ESLint-7.32.0-4B32C3?logo=eslint&logoColor=white)
![Prettier](https://img.shields.io/badge/Prettier-2.5.0-F7B93E?logo=prettier&logoColor=black)

</div>

---

## 📁 Project Structure

```
super-admin-panel/
├── public/                 # Static assets
├── src/
│   ├── components/        # Reusable UI components
│   │   ├── AppHeader/     # Header component
│   │   ├── AppSidebar/    # Sidebar navigation
│   │   └── ...
│   ├── views/             # Page components
│   │   ├── pages/
│   │   │   ├── admin/     # Admin-specific pages
│   │   │   │   ├── Companies.jsx
│   │   │   │   ├── AddCompany.jsx
│   │   │   │   ├── ContractTemplates.jsx
│   │   │   │   ├── JobList.jsx
│   │   │   │   └── ...
│   │   │   ├── company/   # Company-specific pages
│   │   │   │   ├── EmployeesList.jsx
│   │   │   │   ├── AddEmployee.jsx
│   │   │   │   ├── CompanySettings.jsx
│   │   │   │   └── ...
│   │   │   └── login/     # Authentication pages
│   │   └── ...
│   ├── redux/             # Redux store and slices
│   │   ├── store.js
│   │   └── slices/
│   │       └── userSlice.js
│   ├── firebase.js        # Firebase configuration
│   ├── routes.js          # Route definitions
│   ├── App.js             # Main app component
│   └── scss/              # Stylesheets
└── package.json
```

## 💻 Usage

### Test Credentials

#### Admin Account
```
Email: admin@gmail.com
Password: 123456
```

#### Company Account
```
Email: pepsi@gmail.com
Password: 123456
```

## 🎯 Key Features Breakdown

### Admin Dashboard
- **Companies Management**: Full CRUD operations for company entities
- **Contract Templates**: Create and manage reusable contract templates
- **Job Positions**: Create, view, and manage job listings
- **Template Builder**: Visual interface for creating contract templates

### Company Dashboard
- **Employee Management**: Add, edit, and manage employee information
- **Company Profile**: Update company settings and details
- **Job Selection**: Browse and select from available job positions
- **Contract Generation**: Create employee contracts using templates

---

## 🔒 Security

- Firebase Authentication for secure user management
- Role-based access control (RBAC)
- Protected routes with authentication guards
- Environment variables for sensitive configuration

---

