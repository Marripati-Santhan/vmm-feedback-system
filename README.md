# 🏪 Vishal Mega Mart Customer Feedback Management System

A full-stack web application developed to digitally collect, manage, and analyze customer feedback and employee reviews for **Vishal Mega Mart**. This system replaces traditional paper-based feedback forms with a modern, responsive, cloud-hosted solution.

---

## 📌 Project Overview

The **Vishal Mega Mart Customer Feedback Management System** allows customers to:

- Submit store feedback
- Rate employees
- Share suggestions
- Help management improve customer satisfaction

Administrators can securely access a dashboard to monitor customer feedback, employee performance, ratings, and overall store analytics.

---

## ✨ Features

### 👤 Customer Module

- Store feedback submission
- Employee rating & review
- Suggestions section
- Responsive user interface
- Animated homepage
- Recent customer reviews
- Customer satisfaction statistics

### 🔐 Admin Module

- Secure admin login
- Protected dashboard
- View all store feedback
- View employee reviews
- Analytics & statistics
- Recent activities
- Total feedback count
- Average rating calculation

---

## 🛠 Technology Stack

### Frontend

- React.js
- Vite
- Bootstrap 5
- Axios
- React Router DOM
- Framer Motion

### Backend

- Node.js
- Express.js
- REST APIs
- dotenv
- CORS

### Database

- MySQL
- Aiven Cloud Database

### Deployment

- Frontend → Vercel
- Backend → Render
- Database → Aiven Cloud

### Version Control

- Git
- GitHub

---

# 📂 Project Structure

```
VMM-Feedback-System
│
├── Backend
│   ├── config
│   ├── routes
│   ├── server.js
│   └── package.json
│
├── Frontend
│   ├── public
│   ├── src
│   │   ├── assets
│   │   ├── components
│   │   ├── data
│   │   ├── pages
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── package.json
│   └── vite.config.js
│
└── README.md
```

---

# 🏗 System Architecture

```
Customer
      │
      ▼
React Frontend
      │
Axios HTTP Request
      │
      ▼
Express REST API
      │
Node.js
      │
      ▼
MySQL Database (Aiven)
      │
      ▼
JSON Response
      │
      ▼
React User Interface
```

---

# 🔄 Application Flow

```
Customer

↓

Home Page

↓

Store Feedback / Staff Review

↓

Axios API Request

↓

Express Route

↓

MySQL Database

↓

Data Stored

↓

Admin Dashboard

↓

Analytics & Reports
```

---

# 💻 Installation

## Clone Repository

```bash
git clone https://github.com/Marripati-Santhan/vmm-feedback-system.git
```

---

## Frontend Setup

```bash
cd Frontend

npm install

npm run dev
```

Runs at:

```
http://localhost:5173
```

---

## Backend Setup

```bash
cd Backend

npm install

npm start
```

Runs at:

```
http://localhost:5000
```

---

# ⚙ Environment Variables

Create a `.env` file inside the Backend folder.

```env
DB_HOST=your_host

DB_USER=your_user

DB_PASSWORD=your_password

DB_NAME=your_database

PORT=5000
```

---

# 📊 Major Functionalities

✔ Store Feedback

✔ Employee Reviews

✔ Admin Authentication

✔ Dashboard Analytics

✔ Customer Satisfaction Score

✔ Recent Activities

✔ Responsive Design

✔ Cloud Database Integration

✔ REST API Communication

✔ Protected Routes

✔ Modern UI Animations

---

# 🎯 Learning Outcomes

This project demonstrates practical experience with:

- React.js
- Node.js
- Express.js
- REST API Development
- Axios
- MySQL
- Cloud Database
- Authentication
- Full Stack Development
- Responsive Web Design
- Git & GitHub
- Vercel Deployment
- Render Deployment

---

# 🚀 Future Enhancements

- JWT Authentication
- Email Notifications
- Feedback Search
- Advanced Dashboard Filters
- Export Reports (PDF/Excel)
- Role-Based Access Control
- Customer Feedback History
- AI Sentiment Analysis

---

# 👨‍💻 Developer

**Marripati Santhan**

Computer Science & Engineering

Full Stack Java Developer

---

# 📄 License

This project is developed for educational purposes and portfolio demonstration.
