Apologies for the confusion earlier! Here's the updated **README** reflecting that your backend is **Spring Boot** and the frontend is **React.js**. I've made sure to fix it accordingly:

---

# Employee Management System

A comprehensive **Employee Management System** designed to streamline employee management processes, including tracking employee data, attendance, leaves, and salaries. The system is built to provide an easy-to-use interface for managing employee records and administrative tasks.

---

## Features

- **Employee Records Management**: Add, update, and delete employee records easily.
- **Attendance Tracking**: Log daily attendance and track employee presence.
- **Role Management**: Assign different roles with specific permissions (Admin, Manager, Employee).
- **Leave Management**: Track and manage employee leave requests and approvals.
- **Department & Salary Management**: Organize employees by departments and manage salaries.
- **Analytics & Reports**: Generate reports on employee performance, attendance, and leaves.
- **Responsive Design**: Built to be mobile-friendly for HR teams to manage employee data on the go.

---

## Tech Stack

- **Frontend**: 
  - React.js
  - React-Bootstrap
  
- **Backend**: 
  - Spring Boot
  
- **Database**: 
  - MongoDB
  
- **Authentication**: 
  - JWT (JSON Web Token)
  
- **Version Control**: 
  - Git

---

## Setup Instructions

To get the project running locally, follow these steps:

### 1. Clone the repository

```bash
git clone https://github.com/Aman0474/Employee-Management-System.git
cd Employee-Management-System
```

### 2. Install Dependencies

#### For Backend (Spring Boot):

1. Navigate to the **`ems-backend`** directory:

   ```bash
   cd ems-backend
   ```

2. Install backend dependencies by running:

   ```bash
   ./mvnw clean install
   ```

3. Configure your environment variables. Create a `application.properties` file (or `application.yml`) in the **`src/main/resources`** directory:

   ```properties
   spring.data.mongodb.uri=mongodb://localhost:27017/employee_system
   jwt.secret=your_jwt_secret_key
   server.port=8080
   ```

#### For Frontend (React):

1. Navigate to the **`ems-frontend`** directory:

   ```bash
   cd ../ems-frontend
   ```

2. Install frontend dependencies:

   ```bash
   npm install
   ```

---

### 3. Start the Application

#### For Backend (Spring Boot):

1. In the **`ems-backend`** directory, run:

   ```bash
   ./mvnw spring-boot:run
   ```
   or
   /mvn run dev
   ```

   This will start the backend server on `http://localhost:8080`.

#### For Frontend (React):

1. In the **`ems-frontend`** directory, run:

   ```bash
   npm start
   ```

   This will start the frontend on `http://localhost:3000`.

---

### 4. Open the Application

Once both the frontend and backend are running, open your browser and go to `http://localhost:3000` to access the Employee Management System.

---



### End of README

---

This should be a correct representation of your **Spring Boot** backend and **React.js** frontend setup. Let me know if you'd like any further changes!
