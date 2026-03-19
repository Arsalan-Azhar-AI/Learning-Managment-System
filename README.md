

# Learning Management System (LMS)

**Overview:**
A web-based **Learning Management System (LMS)** built using **PHP** and **MySQL**. This project simulates a basic online learning platform, allowing instructors to manage courses and students to enroll and access course content. It demonstrates database-driven content management, user roles, and session-based access control.

---

## Features

* **User Roles:**

  * **Instructor/Admin:** Can create, edit, and manage courses, modules, and resources.
  * **Student:** Can register, enroll in courses, and view course materials.

* **Course Management:** Add, update, and delete courses or learning modules.

* **Student Enrollment:** Enroll in courses, track progress, and access course resources.

* **Dynamic Content:** All pages interact with the MySQL database for real-time updates.

* **Authentication:** Secure login system with role-based access control using PHP sessions.

---

## Technologies Used

* **Backend:** PHP
* **Database:** MySQL
* **Frontend:** HTML, CSS, Bootstrap
* **Session Management:** PHP sessions for secure authentication

---

## Setup Instructions

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Arsalan-Azhar-AI/Learning-Managment-System.git
   ```

2. **Database Setup:**

   * Create a database (e.g., `lms_db`).
   * Create tables such as:

     * `users` (id, username, password, role)
     * `courses` (id, title, description, instructor_id)
     * `enrollments` (student_id, course_id, progress)
   * Adjust the database connection settings in the PHP files to match your server credentials.

3. **Run the Application:**

   * Place files in your PHP server directory (e.g., XAMPP `htdocs`).
   * Access `index.php` in your browser.
   * Register or log in depending on your role. Explore course management and enrollment features.

---

## Usage

* **Instructor/Admin:**

  * Log in → Access the dashboard → Add/Edit/Delete courses → Manage enrolled students.

* **Student:**

  * Log in → Browse available courses → Enroll → Access course content.

---
