# 🎓 Comprehensive College Management System (CMS)

A robust, full-stack **College Management System** built with the **MERN stack** (MongoDB, Express.js, React, Node.js). This platform is designed to automate and streamline core administrative, academic, and communication processes, providing a centralized and efficient solution for all college stakeholders.

## 🚀 Key Features and Role-Based Access

The system implements strict **Role-Based Access Control (RBAC)**, offering tailored functionalities for **Admin**, **Faculty**, and **Student** users.

### 👤 Admin Features
The centralized hub for complete institutional control:

* **User Management:**
    * Manage **faculty accounts** with detailed profiles and emergency contacts.
    * Manage **student accounts** with enrollment numbers and academic details.
* **Academic Management:**
    * Manage **academic branches** and departments.
    * Handle **subject/course management** by semester and branch.
* **Information Sharing:**
    * **Generate and manage notices** for students and faculty.
    * **Upload and manage timetables** by branch and semester.
* **System Maintenance:**
    * Profile management and password updates.

### 👨‍🏫 Faculty Features
Tools to manage classes, academic resources, and student data:

* **Profile Management:**
    * View and manage personal profile with emergency contacts, credentials, and password updates.
* **Resource Management:**
    * **Upload and manage study materials** (notes, assignments, syllabus).
    * Filter and organize materials by subject, semester, and type.
    * Upload and manage timetables for their branches.
* **Student Interaction:**
    * **Search and view student information** by enrollment, name, or semester.
    * View and respond to notices.

### 🧑‍🎓 Student Features
An organized portal for academic life and communication:

* **Personal Data:**
    * View personal profile and academic details.
    * Update profile information and password.
* **Access & Download:**
    * **Access study materials** filtered by subject and type.
    * View class timetables with a download option.
    * Access notices and announcements.

---

## 💻 Tech Stack

This project leverages the power of the JavaScript ecosystem with the MERN stack.

| Category | Technology | Purpose |
| :--- | :--- | :--- |
| **Frontend** | **React.js** | Building a fast, responsive, and dynamic user interface. |
| **Backend** | **Node.js, Express.js** | Creating a scalable and robust RESTful API server. |
| **Database** | **MongoDB** | Flexible, document-based storage for all institutional data. |
| **Authentication** | **JWT (JSON Web Tokens)** | Securing API routes and ensuring role-based access control. |

---

## ⚙️ Setup and Installation

### Prerequisites
* Node.js (LTS recommended)
* npm
* MongoDB (Local or Cloud Instance)

### Steps

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/YourUsername/YourRepoName.git](https://github.com/YourUsername/YourRepoName.git)
    cd YourRepoName
    ```

2.  **Install Dependencies:**
    ```bash
    # Install backend dependencies
    cd backend
    npm install

    # Install frontend dependencies
    cd ../frontend
    npm install
    ```

3.  **Configure Environment Variables:**
    * Create a `.env` file in the `backend` directory for your `MONGO_URI`, `JWT_SECRET`, and `PORT`.
    * Create a `.env` file in the `frontend` directory for your API base URL.

4.  **Run the Application:**
    Open two terminals.

    **Terminal 1 (Backend):**
    ```bash
    cd backend
    npm start # Or 'npm run dev'
    ```

    **Terminal 2 (Frontend):**
    ```bash
    cd frontend
    npm run dev # Or 'npm start'
    ```
The application should now be live on `http://localhost:3000`.
