# CorticaProject 

## Attendance Management System

### Project Overview:

The Attendance Management System is a web application designed to streamline and manage attendance for students and teachers in an educational institution. This application supports three types of users: 
 Student, Teacher, and Admin, each with specific roles and permissions. The system allows users to register, mark attendance, track attendance history, and allows admins to manage users.

### Prerequisites:
- Before running the application, ensure you have:
- Java Development Kit (JDK): Version 8 or higher.
- Maven: For building the project.
- MySQL: For database integration.
- Postman (optional): For API testing.

## Tech Stack

### Backend:
- Java: Core programming language for backend development.
- Spring Boot: Framework for creating RESTful APIs.
- Hibernate: ORM framework for database interaction.
- MySQL: Relational database for data persistence.
- Spring Security (optional): For securing APIs and authentication.

### Frontend:
- HTML/CSS/JavaScript: For creating responsive UI.
- Bootstrap: Framework for designing responsive layouts.


## Development Tools:

- Eclipse IDE: For development and debugging.
- Maven: For dependency management.
- Postman: For testing APIs.
- MySQL Workbench: For database management.

## Database Configuration
### This project uses MySQL as the database. Update your database credentials in application.properties file:
- spring.datasource.url=jdbc:mysql://localhost:3306/attendance_db
- spring.datasource.username=root
- spring.datasource.password=your_password
- spring.jpa.hibernate.ddl-auto=update
- spring.jpa.database-platform=org.hibernate.dialect.MySQL5InnoDBDialect

### To connect to a remote MySQL database (example configuration):
- spring.datasource.url=jdbc:mysql://sql12.freesqldatabase.com:3306/sql12746297
- spring.datasource.username=sql12746297
- spring.datasource.password=dAYPqtjudU

