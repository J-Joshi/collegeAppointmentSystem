# College Appointment System

## Overview

The College Appointment System is a Node.js-based application that allows students to book appointments with professors based on their availability. The system provides functionality for user registration, login, setting availability, booking appointments, and canceling appointments.

---

## Features

- **User Registration**: Students and professors can register with unique roles.
- **Login**: Secure authentication with JWT.
- **Set Availability**: Professors can define their available time slots.
- **Book Appointments**: Students can view available slots and book appointments.
- **Cancel Appointments**: Appointments can be canceled by either the professor or the student.
- **Role-Based Access**: Access control for professor-specific and student-specific operations.

---

## Tech Stack

- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Testing**: Supertest for E2E testing
- **Utilities**: Mongoose (for database modeling), bcrypt (for password hashing)

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/J-Joshi/collegeAppointmentSystem.git
   cd collegeAppointmentSystem
