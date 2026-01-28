# 🚆 Train Ticket Booking Application

A **console-based Java application** that simulates a real-world **train ticket booking system**.  
Users can sign up, log in, search trains, view seat availability, book tickets, and manage bookings.

---

## 📌 Features

- 👤 **User Authentication**
  - Sign up and login functionality
  - Password hashing for basic security

- 🔍 **Train Search**
  - Search trains by source and destination
  - View station-wise timings

- 💺 **Seat Management**
  - View seat layout of selected trains
  - Book seats by selecting row and column
  - Prevents double booking

- 📄 **Booking Management**
  - View all bookings for a user
  - Cancel existing bookings

- 💾 **Data Persistence**
  - Uses JSON files for storing users and train data
  - Jackson used for serialization/deserialization

---

## 🛠️ Tech Stack

- **Language:** Java 17
- **Build Tool:** Gradle
- **Libraries:**
  - Jackson (JSON handling)
  - Lombok (boilerplate code reduction)
