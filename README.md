
# Airline Management System ✈️

A Java-based desktop application (Swing or CLI) for managing flights, customers, bookings, and boarding passes with backend storage using JDBC/MySQL.

---

## 🚀 Project Features

### ✈️ Flight Management
- Add new flights with attributes: Flight ID, Airline, Source, Destination, Date, Seat Availability.
- Update or delete flight records.
- View all current flights and their details.

### 👤 Customer & Booking Module
- Register new customers (Name, Email, Passport No, Contact).
- Search and view existing customer profiles.
- Book flights by entering passenger details.
- Generate and view ticket information automatically.

### 🎟 Booking Cancellation
- Cancel booked tickets using Booking ID or Passenger details.
- Update seat availability upon cancellation.

### 🧾 Boarding Pass & Payment
- Generate printable boarding pass for successful bookings.
- Calculate and record ticket payments.

---

## 🧰 Tech Stack

- **Backend**: Java (Swing-based UI or console menus)  
- **Database**: MySQL (via JDBC)  
- **Front-end**: Java Swing (GUI) or plain Java console interface  
- **Data Modeling**: Object-oriented classes like `Flight`, `Customer`, `Booking`, `BoardingPass`

---

🔍 Sample User Flow
-Start the application
-Register Customer → Enter personal data
-Add Flight → Set flight schedules and seat count
-Book Ticket → Select customer & flight, generate booking
-View Ticket & Boarding Pass → Display booking details
-Cancel Ticket → Free up seats and delete booking
-View All Flights or Bookings → Summary lists

---

📂 Project Structure

src/
 ├─ model/              – Entity classes (Flight, Customer, Booking)
 ├─ dao/                – JDBC operations for CRUD on each entity
 ├─ service/            – Business logic for booking and seat tracking
 ├─ ui/                 – Main UI: console menu or Swing frames
 ├─ util/               – Database configuration and connection helper
Main.java               – Entry point for launching the app
schema.sql              – SQL script to initialize tables

---

🧠 What I Learned
-Implemented CRUD operations with JDBC and MySQL
-Designed modular classes and applied OOP principles
-Handled input validation, edge cases, and user prompts
-Enabled ticket booking and cancellation logic with seat tracking
-Created interactive UI using Java Swing or console menus

---

## 📧 Contact

For any questions or collaboration:
- **GitHub**: @PrakharS524  
- **Email**: prakhars2202@gmail.com  

---

Thank you for checking out the project!  
