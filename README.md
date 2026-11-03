# 🎓 Student Database Management System

A full-stack Student Database Management System developed using **Node.js, Express.js, MySQL, HTML, CSS, and JavaScript**. This project helps manage student records, view course information, and generate academic reports through a simple web interface.

## 🚀 Features

### Student Management
- Add new student records.
- View all student details.
- Update student addresses.
- Delete student records.
- Search and filter displayed data.

### Course Management
- View available courses.
- Retrieve course information from MySQL.

### Academic Reports
- Generate student-course reports.
- Display enrollment details.
- View internal marks, external marks, total marks, and grades.
- Combine information using SQL JOIN operations.

## 🛠️ Technologies Used

| Category | Technologies |
|---|---|
| Frontend | HTML5, CSS3, JavaScript |
| Backend | Node.js, Express.js |
| Database | MySQL |
| Packages | mysql2, cors |
| Tools | VS Code, Git, GitHub |

## 📂 Project Structure

```text
student_database_management_system/
│
├── public/
│   └── index.html
│
├── server.js
├── package.json
├── package-lock.json
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/student-database-management-system.git
```

### 2. Open the Project Folder

```bash
cd student-database-management-system
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Configure MySQL Database

Create a MySQL database named:

```sql
CREATE DATABASE student_management_db;
```

Create the required tables: `students`, `courses`, `enrollments`, and `marks`, with the columns referenced in the SQL queries in `server.js`.

Configure your MySQL connection in `server.js` using your local database credentials. Do not upload passwords or other secrets to GitHub.

### 5. Start the Application

```bash
npm start
```

### 6. Open in Browser

```text
http://localhost:3000
```

## 🔗 API Endpoints

### Student APIs

| Method | Endpoint | Description |
|---|---|---|
| GET | `/students` | Display all students |
| POST | `/students` | Add a new student |
| PUT | `/students/:id` | Update student address using ID |
| PUT | `/students/rollno/:roll_no` | Update address using roll number |
| DELETE | `/students/:id` | Delete student using ID |
| DELETE | `/students/rollno/:roll_no` | Delete student using roll number |

### Course API

| Method | Endpoint | Description |
|---|---|---|
| GET | `/courses` | Display available courses |

### Report API

| Method | Endpoint | Description |
|---|---|---|
| GET | `/report` | Generate student academic reports |

## 📚 Database Concepts Demonstrated

- Relational Database Management
- Primary Keys and Foreign Keys
- SQL Queries
- JOIN Operations
- CRUD Operations
- Student and Course Relationships
- Academic Record Management

## 🎯 Learning Outcomes

- Understanding full-stack web development.
- Connecting Node.js applications with MySQL.
- Implementing REST API endpoints.
- Performing database CRUD operations.
- Working with relational database concepts.
- Displaying database records dynamically on a webpage.

## 👨‍💻 Author

**Sweedal Dsouza**

- GitHub: https://github.com/Sweedal313
- LinkedIn: https://www.linkedin.com/in/sweedal-dsouza-235bb8424
- Portfolio: https://sweedals-portfolio.netlify.app/

---

⭐ If you find this project useful, feel free to explore the repository!
