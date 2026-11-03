# 🎓 Student Management System

## 📌 Overview

The **Student Management System** is a full-stack web application developed using Node.js, Express.js, MySQL, HTML, CSS, and JavaScript.

The system is designed to simplify student record management by providing a centralized platform to manage student details, course information, enrollments, and academic reports through a user-friendly web interface.

It demonstrates the practical implementation of database management concepts, relational database design, SQL queries, and full-stack web development.

---

# 🚀 Features

- 👨‍🎓 Student Record Management
- 📚 Course Management
- 📝 Student Enrollment Management
- 📊 Academic Reports Generation
- 🔄 Complete CRUD Operations
- 🔗 SQL Joins and Relational Queries
- 🗄️ MySQL Database Integration
- ⚡ Data Validation and Error Handling
- 🌐 User-Friendly Web Interface

---

# 🛠️ Technologies Used

## Frontend
- HTML5
- CSS3
- JavaScript (ES6)

## Backend
- Node.js
- Express.js

## Database
- MySQL

## Libraries
- Express
- MySQL2
- CORS

---

# 🧩 System Architecture

The application consists of multiple modules that work together to manage student and academic information efficiently.

## Modules

### 1. Student Management Module
- Add new student records
- View all registered students
- Update student information
- Delete student records
- Maintain personal and academic details

### 2. Course Management Module
- View available courses
- Manage course information
- Maintain the course catalog
- Store course details in the MySQL database

### 3. Enrollment Management Module
- Maintain student-course relationships
- Manage enrollment information
- Track semester and academic year details

### 4. Academic Reports Module
- Generate student-course reports
- Display enrollment information
- View marks and grades
- Generate consolidated reports using SQL JOIN operations

### 5. Database Management Module
- Perform Create, Read, Update, and Delete (CRUD) operations
- Maintain primary key and foreign key relationships
- Execute SQL queries and joins
- Manage relational database records

---

# 📂 Project Structure

```text
student-management-app/
│
├── public/
│   └── index.html
│
├── server.js
├── package.json
├── package-lock.json
└── node_modules/
```

---

# 🗄️ Database Design

The system uses a relational database with the following entities:

### 1. Students
Stores student information:
- Student ID
- Roll Number
- Name
- Gender
- Date of Birth
- Phone Number
- Email
- Address
- Admission Year

### 2. Courses
Stores course information:
- Course ID
- Course Code
- Course Name
- Credits
- Department

### 3. Enrollments
Maps students to courses:
- Enrollment ID
- Student ID
- Course ID
- Semester
- Academic Year

### 4. Marks
Stores academic performance:
- Internal Marks
- External Marks
- Total Marks
- Grade

---

# 🔗 API Endpoints

## Student APIs

| Method | Endpoint | Description |
|---|---|---|
| GET | `/students` | Get all students |
| POST | `/students` | Add a new student |
| PUT | `/students/:id` | Update student details |
| DELETE | `/students/:id` | Delete student record |

## Course APIs

| Method | Endpoint | Description |
|---|---|---|
| GET | `/courses` | Get all courses |

## Report APIs

| Method | Endpoint | Description |
|---|---|---|
| GET | `/report` | Generate student report |

---

# ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/student-management-system.git
```

### 2. Navigate to the Project Folder

```bash
cd student-management-app
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Configure the Database

Update your MySQL credentials in `server.js`:

```javascript
const db = mysql.createConnection({
    host: "localhost",
    user: "root",
    password: "YOUR_PASSWORD",
    database: "student_management_db"
});
```

Make sure the MySQL database and required tables are created before running the application.

### 5. Run the Application

```bash
npm start
```

### 6. Open in Browser

```text
http://localhost:3000
```

---

# 🎯 Learning Outcomes

This project demonstrates practical knowledge of:

- Relational Database Design
- SQL Query Writing
- Database Normalization
- REST API Development
- Full-Stack Development
- CRUD Operations
- MySQL Integration with Node.js
- Frontend and Backend Communication
- Data Validation and Error Handling

---

# 📈 Future Enhancements

- Student Authentication
- Admin Dashboard
- Role-Based Access Control
- Attendance Management
- Fee Management
- PDF Report Generation
- Search and Filter Functionality
- Responsive Mobile Application

---

# ✅ Conclusion

The **Student Management System** provides a centralized solution for managing student records, course information, enrollments, and academic reports.

By integrating Node.js, Express.js, and MySQL, the application demonstrates how relational database concepts and full-stack web technologies can be used to develop practical management solutions.

Overall, this project highlights the implementation of database operations, SQL joins, REST APIs, and efficient academic data management.

---

# 👨‍💻 Author

**Sweedal Dsouza**

- GitHub: https://github.com/Sweedal313
- Portfolio: https://sweedals-portfolio.netlify.app/

*Student Management System developed as an academic DBMS project to demonstrate practical implementation of relational database concepts, SQL operations, joins, and full-stack web development.*

⭐ If you find this project useful, consider giving the repository a star!
