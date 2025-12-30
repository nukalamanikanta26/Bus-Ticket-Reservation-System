# 📌 Project Overview

The Simple Bus Ticket Management System is a web-based backend application designed to automate the process of managing bus journeys and ticket bookings. It replaces traditional manual and offline booking methods with a centralized digital system that enables users to view available bus journeys, book tickets, and cancel bookings efficiently.

This project is developed using Java, Spring Boot, REST APIs, and MySQL, focusing on fundamental backend development concepts. It is suitable for academic projects, beginners, and learning real-world CRUD-based backend systems.

# 📝 Abstract

The Simple Bus Ticket Management System simplifies the management of bus journeys and ticket reservations through a centralized web application. Users can view available bus journeys based on source, destination, date, and time, and perform basic ticket booking and cancellation operations.

All operations are handled using RESTful APIs, ensuring smooth client-server communication. The system automates manual booking processes, reduces human effort, improves data accuracy, and demonstrates core backend development concepts using Spring Boot and MySQL.

# 🔄 Existing System

In the existing system, bus ticket booking and cancellation are mostly handled manually or through offline methods. Customers must visit bus counters or contact agents to inquire about schedules, seat availability, and bookings.

# ❌ Limitations of Existing System

Time-consuming manual processes

High chance of human errors

No centralized database

Difficulty in tracking booking records

Poor user experience

Lack of data transparency and consistency

# 🚀 Proposed System

The proposed Simple Bus Ticket Management System automates the entire process using a web-based application.

# ✅ Key Advantages

Online bus journey viewing

Easy ticket booking and cancellation

Centralized MySQL database

Reduced manual work

Improved accuracy and efficiency

Beginner-friendly REST API architecture

Administrators can manage bus journey details, while users can book and cancel tickets seamlessly.

# 🧩 Modules
1. Bus Management Module

Manage bus journey details

Source and destination

Journey date and time

2. Ticket Booking Module

Book tickets for available journeys

Store passenger and booking details

3. Ticket Cancellation Module

Cancel booked tickets

Update booking status

4. Booking Management Module

View and track all bookings

Maintain booking history

5. Database Module

Store bus and booking data securely

Uses MySQL relational database

6. API Testing Module

Test APIs using Postman

Validate booking, cancellation, and retrieval operations

# 🛠️ Tech Stack
Layer	- Technology
Backend -	Java, Spring Boot
API -	RESTful APIs
Database- MySQL
Server -	Embedded Apache Tomcat
Tools -	IntelliJ IDEA, Postman,Visual Studio Code, MySQL Workbench
Browser -	Chrome
# 💻 Software Requirements

# Operating System: Windows 10 / Linux

# Backend: Java, Spring Boot

# Database: MySQL

# Web Server: Embedded Apache Tomcat

# IDE: VisualStudio Code / IntelliJ IDEA

# API Testing: Postman

# Browser: Google Chrome / Mozilla Firefox

# 🖥️ Hardware Requirements

# Processor: Intel Core i3 or higher

# RAM: Minimum 4 GB

# Hard Disk: Minimum 250 GB

# Internet Connection: Required

# Input Devices: Keyboard, Mouse

# Output Device: Monitor


# simple-bus-ticket-management-system Structure
│
├── controller
│   ├── BusController.java
│   └── BookingController.java
│
├── service
│   ├── BusService.java
│   └── BookingService.java
│
├── repository
│   ├── BusRepository.java
│   └── BookingRepository.java
│
├── entity
│   ├── Bus.java
│   └── Booking.java
│
├── application.properties
└── SimpleBusTicketManagementApplication.java


# 🔗 API Endpoints (Sample)
# Bus APIs

POST /api/buses → Add bus journey

GET /api/buses → Get all journeys

# Booking APIs

POST /api/bookings → Book ticket

GET /api/bookings → View all bookings

# ⚙️ How to Run the Project

Clone the repository

git clone https://github.com/your-username/simple-bus-ticket-management-system.git


Open the project in Eclipse or IntelliJ IDEA

Configure MySQL database in application.properties

Run the Spring Boot application

# Test APIs using Postman
🎯 Learning Outcomes

Understanding Spring Boot project structure

Creating RESTful APIs

CRUD operations using JPA & MySQL

API testing using Postman

Backend project workflow

# 👨‍💻 Author

# Manikanta Nukala
Backend Developer | Java | Spring Boot

DELETE /api/bookings/{id} → Cancel booking
