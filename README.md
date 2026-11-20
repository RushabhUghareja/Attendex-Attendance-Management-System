# Attendex – Attendance Management System

Attendex is a Java-based attendance management system for teachers. It provides a login page, dashboard, lecture-wise attendance management, student records, and attendance status tracking.

## Project contents

The original project archive is `AttendanceSystem-attendex.zip`. It contains the Maven project, Java servlet source files, JSP views, CSS, and the MySQL database script.

## Screenshots

### Login page

![Attendex login page](screenshots/login.png)

### Dashboard

![Attendex dashboard](screenshots/dashboard.png)

## Technology stack

- Java Servlets and JSP
- Maven
- Spring JDBC
- MySQL
- HTML and CSS

## Setup

1. Extract `AttendanceSystem-attendex.zip`.
2. Import the `AttendanceSystem` folder as a Maven project in your Java IDE.
3. Create the MySQL database by running `AttendanceSystem/database/attendance_db.sql`.
4. Check the database connection settings in `Dao.java` and update them for your local MySQL setup.
5. Build and deploy the web application to a compatible servlet container.

## Demo login

- Username: `teacher1`
- Password: `teacher123`

> Change demo credentials and local database settings before using this project outside a demo environment.

## License

No license specified.