# 📚 Library Management System (MERN Stack)

A full-stack **Library Management System** built using the **MERN** (MongoDB, Express.js, React, Node.js) stack.  
This project was developed as part of the **Full Stack Development using MERN** course by CipherSchools.  
It allows **Librarians** and **Students** to manage books, issue records, and track usage efficiently.

---

## 🚀 Features

### **For Librarians**
- Add new books with title, author, ISBN, and category.
- View all books and their availability.
- Issue books to students.
- View and manage issued books.
- Authentication and role-based access.

### **For Students**
- View all available books.
- See books issued to them.
- Track issue dates and return status.

---

## 🛠️ Tech Stack

**Frontend:**
- React.js
- React Router
- Semantic UI / Custom CSS
- Axios for API calls

**Backend:**
- Node.js
- Express.js
- MongoDB (Mongoose)
- JWT Authentication
- Bcrypt for password hashing

**Other Tools:**
- Git & GitHub for version control
- Vite for frontend build
- Postman for API testing

---

## 📂 Folder Structure

Library-Management-System/

│

├── client/ # Frontend (React)

│ ├── public/ # Static files

│ ├── src/ # React components & pages

│ ├── package.json

│ └── .gitignore

│
├── server/ # Backend (Node.js + Express)

│ ├── models/ # Mongoose models

│ ├── routes/ # API routes

│ ├── controllers/ # Controller logic

│ ├── middleware/ # Authentication middleware

│ ├── server.js # Main server entry

│ ├── package.json

│ └── .gitignore

│

└── README.md



