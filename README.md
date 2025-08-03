# Online-Bus-Ticket-Booking-System
This is my CDAC Project
# 🚌 Online Bus Ticket Booking System (Ticket Trial)

A full-stack web application that allows users to book bus tickets online with seat availability, secure payments, and admin controls for route and schedule management.

---

## 📄 Project Overview

The **Online Bus Ticket Booking System** simplifies the process of bus reservations by providing a user-friendly interface for customers and powerful admin tools for operators. It ensures secure authentication, real-time seat tracking, and seamless booking.

---

## 🧰 Tech Stack

### 🖥 Frontend:
- React.js
- Axios
- React Router DOM

### 🔙 Backend:
- Spring Boot
- Spring Security with JWT
- Spring Data JPA
- MySQL

### 🔐 Authentication:
- JSON Web Tokens (JWT)
- Role-based access (User/Admin)

---

## ✨ Features

### ✅ User Features:
- Browse available buses and routes
- View seat availability
- Book tickets with seat selection
- View booking history
- Secure login and registration

### 🛠️ Admin Features:
- Add/update/delete buses, routes, and schedules
- Manage bookings and users
- View all transactions

---

## 🚀 How to Run This Project

### 1. Clone the repository
git clone https://github.com/Aniket0504-hub/Online-Bus-Ticket-Booking-System.git

<br>
## 2. Backend Setup (Spring Boot)
Java 17+, Maven, and MySQL required.

Update src/main/resources/application.properties:spring.datasource.url=jdbc:mysql://localhost:3306/bus_booking_db
spring.datasource.username=your_mysql_username
spring.datasource.password=your_mysql_password

git clone https://github.com/Aniket0504-hub/Online-Bus-Ticket-Booking-System.git
cd online-bus-ticket-booking
<br>
Create the database:CREATE DATABASE bus_booking_db;

<br>
Run the Spring Boot app:
./mvnw spring-boot:run

<br>
##3. Frontend Setup (React)
Node.js and npm required.
cd frontend
npm install
npm start

##
4. Access the App
React Frontend:  http://localhost:5173/

Spring Boot API: http://localhost:8080

<br>
🔒 JWT Authentication Flow
User logs in → JWT token is generated.

Token is stored in browser (usually in localStorage).

On every request, the token is sent in the Authorization header:

Authorization: Bearer <token>

<br>
##
📂 Folder Structure
online-bus-ticket-booking/
│
├── backend/                # Spring Boot backend
│   └── src/main/java/
│
├── frontend/               # React frontend
│   └── src/
│
└── README.md


<br>
Backend validates the token and grants access.

##📬 Contact
Name: Aniket Tukaram

Email: [your-email@example.com]

LinkedIn: linkedin.com/in/your-profile

