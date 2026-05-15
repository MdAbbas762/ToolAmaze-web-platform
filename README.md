# 🚀 ToolAmaze

A modern full-stack web platform for accessing and managing premium digital tools through role-based dashboards.

ToolAmaze allows admins to manage tools and assign them to users, while users can access their assigned tools through a clean and responsive interface.

---

## 📌 Overview

ToolAmaze is developed as a full-stack web application focused on:

- User & Admin Authentication
- Tool Management
- Role-Based Access
- Dashboard Systems
- REST API Integration
- Responsive UI Design

The project demonstrates practical implementation of frontend, backend, and database integration using modern web technologies.

---

# ✨ Features

## 👤 Authentication System
- User Registration
- User Login
- Admin Login
- Role-Based Redirection

## 🛠️ Tool Management
- Add New Tools
- Delete Tools
- Assign Tools to Users
- View Available Tools

## 📊 Dashboards
### Admin Dashboard
- Manage Users
- Manage Tools
- Assign Tools
- Platform Overview

### User Dashboard
- View Assigned Tools
- Search Tools
- Access Tool Links

## 📱 UI & UX
- Responsive Design
- Modern Layout
- Sidebar Navigation
- Search Functionality
- Clean Dashboard Interface

---

# 🧑‍💻 Tech Stack

## Frontend
- React.js
- Vite
- React Router DOM
- Bootstrap
- JavaScript
- CSS

## Backend
- Node.js
- Express.js

## Database
- MySQL

---

# 📂 Project Structure

```bash
ToolAmaze/
│
├── backend/
│   ├── server.js
│   └── package.json
│
├── public/
│   └── images/
│
├── src/
│   ├── components/
│   ├── pages/
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
│
├── package.json
└── vite.config.js
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/ToolAmaze.git
cd ToolAmaze
```

---

## 2️⃣ Install Frontend Dependencies

```bash
npm install
```

---

## 3️⃣ Install Backend Dependencies

```bash
cd backend
npm install
```

---

# 🗄️ Database Configuration

Create a MySQL database:

```sql
CREATE DATABASE ai_tools_db;
```

Update database credentials inside:

```bash
backend/server.js
```

Example configuration:

```javascript
const db = mysql.createConnection({
  host: "localhost",
  user: "root",
  password: "",
  database: "ai_tools_db"
});
```

---

# ▶️ Running the Project

## Start Backend Server

```bash
cd backend
node server.js
```

Backend will run on:

```bash
http://localhost:5000
```

---

## Start Frontend

```bash
npm run dev
```

Frontend will run on:

```bash
http://localhost:5173
```

---

# 🌐 Application Routes

| Route        | Description       |
|--------------|-------------------|
| `/`          | Home Page         |
| `/pricing`   | Pricing Page      |
| `/contact`   | Contact Page      |
| `/register`  | Registration Page |
| `/login`     | Login Page        |
| `/dashboard` | User Dashboard    |
| `/admin`     | Admin Dashboard   |

---

# 📌 Core Functionalities

## 🔐 Authentication Flow
- Users can create accounts and log in.
- Admin and user roles are handled separately.
- Users are redirected based on their role after login.

## 🛠️ Tool Assignment System
- Admins can assign tools to specific users.
- Users can only access tools assigned to them.

## 🔎 Search Functionality
- Users can search tools by name or category directly from the dashboard.

## 📡 REST API Integration
The frontend communicates with the backend using REST APIs for:
- Authentication
- User Management
- Tool Management
- Tool Assignment

---

# 🚧 Future Improvements

- Payment Gateway Integration
- Subscription System
- Better Security & Validation
- Cloud Deployment