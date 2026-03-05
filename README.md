# Dynamic To-Do List Application

## 📌 Project Description

This project is a **Dynamic To-Do List Web Application** developed using **HTML, CSS, JavaScript, Node.js, Express, and SQLite**.
The application allows users to manage daily tasks efficiently. Users can add, edit, delete, and mark tasks as completed.
All tasks are stored in a database so that they remain available even after refreshing the page.

---

## 🎯 Aim

To build a dynamic To-Do List web application and integrate it with a **database-backed backend** to store tasks permanently using CRUD operations.

---

## ✨ Features

* Add new tasks
* Edit existing tasks
* Delete tasks
* Mark tasks as completed
* Task priority selection (Low / Medium / High)
* Filter tasks (All / Active / Completed)
* Task counter (Completed / Total)
* Tasks stored permanently in database

---

## 🛠 Technologies Used

### Frontend

* HTML
* CSS
* JavaScript

### Backend

* Node.js
* Express.js

### Database

* SQLite

---

## 📂 Project Folder Structure

dynamic_todo_list
│
├── frontend
│   ├── index.html
│   ├── style.css
│   └── script.js
│
└── backend
├── server.js
├── package.json
└── db.sqlite

---

## 🗄 Database Schema

Table: **tasks**

| Column    | Type     | Description               |
| --------- | -------- | ------------------------- |
| id        | INTEGER  | Primary Key               |
| title     | TEXT     | Task title                |
| priority  | TEXT     | Low / Medium / High       |
| isDone    | INTEGER  | 0 = Active, 1 = Completed |
| createdAt | DATETIME | Task creation time        |

---

## 🔗 API Endpoints

GET /tasks
→ Fetch all tasks

POST /tasks
→ Add new task

PUT /tasks/:id
→ Update task title or priority

PATCH /tasks/:id/status
→ Toggle completed status

DELETE /tasks/:id
→ Delete a task

---

## ▶️ How to Run the Project

### Step 1: Install Node.js

Make sure Node.js is installed on your system.

### Step 2: Install dependencies

Open terminal inside the **backend** folder and run:

npm install

### Step 3: Start server

node server.js

### Step 4: Open frontend

Open **frontend/index.html** in your browser.

---

## 📸 Screenshots

Include screenshots of:

* Task added
* Task edited
* Task marked completed
* Tasks persisted after refresh

---

## 📚 Learning Outcomes

* Build responsive UI using HTML and CSS
* Implement CRUD operations with JavaScript
* Work with REST APIs
* Connect frontend with backend
* Store data using SQLite database

---

## 👨‍💻 Author

**Shivam**
