📚 Learning Management System (LMS) – Backend

A scalable backend for a Learning Management System built with Java & Spring Boot, providing RESTful APIs for managing courses, users, enrollments, quizzes, and progress tracking.
Designed with modular architecture, secure authentication, and seamless integration for frontend clients.

✨ Features
👨‍💻 Admin Features

Course Management: Create, update, retrieve, and delete courses (title, description, prerequisites, quizzes).

User Management: Register, update, retrieve, and delete users; assign roles (Student/Instructor).

Quiz & Question Management: Manage quizzes and questions; associate questions with quizzes and quizzes with courses.

🎓 General User Features

Enrollment Management: Enroll in courses, view enrollment history, and monitor progress.

Progress Tracking: Track learning progress and generate progress reports.

Leaderboard: Compare performance with peers through dynamic leaderboards.

⚙️ System Features

Exception Handling: Centralized handling for validation errors, resource not found, and custom exceptions.

Password Security: User credentials stored securely with BCrypt hashing.

RESTful API Design:

Follows REST conventions for CRUD operations.

Uses DTOs for data transfer and clean responses.

Implements proper HTTP status codes & error messages.

CORS enabled for frontend integration.

🗄️ Database Integration

Built with JPA/Hibernate for ORM.

Ensures efficient data access and integrity with MySQL.

🛠️ Tech Stack

Programming Language: Java

Framework: Spring Boot

ORM: Spring Data JPA (Hibernate)

Database: MySQL

Security: BCrypt (Password Hashing)

Utilities: Lombok, Exception Handling, DTOs

API Style: RESTful APIs
