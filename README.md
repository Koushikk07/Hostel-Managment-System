# Hostel Management System 🏨

A robust, full-stack web application designed to streamline hostel administration, student registrations, and room allocations.

---

## Features

- **User Authentication:** Secure login and registration system for students and admins.
- **Room Management:** Real-time tracking of room availability and allocation.
- **Automated Notifications:** Built-in middleware for handling system alerts.
- **Database Backups:** Integrated script for periodic MySQL data redundancy.
- **Responsive UI:** Optimized for both desktop and mobile views.

## Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript (ES6+)
- **Backend:** Node.js, Express.js
- **Database:** MySQL
- **Security:** Password hashing and environment-based configuration.

## Project Structure

├── middleware/ # Custom request filters (Auth, Logging)
├── routes/ # API endpoints and page routing
├── public/ # Static assets (Images, CSS, Client JS)
├── notifications/ # Notification logic
├── db.js # Database connection configuration
├── server.js # Main entry point of the application
└── hostel_db.sql # Database schema and initial data

Installation & Setup
Clone the repository:

Bash
git clone [https://github.com/Koushikk07/Hostel_Managment_System.git](https://github.com/Koushikk07/Hostel_Managment_System.git)
cd Hostel_Managment_System
Install dependencies:

npm install
Database Configuration:

Import hostel_db.sql into your local MySQL server.

Create a .env file based on .env.example.

Update the credentials (DB_USER, DB_PASS, DB_NAME).

Run the application:

npm start

Security Note
This project uses environment variables to manage sensitive data. Ensure your .env file is never committed to version control.

---
