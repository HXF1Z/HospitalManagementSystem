# 🏥 Hospital Management System (HMS)

**Hospital Management System (HMS)** is a comprehensive, role-based console application designed to streamline patient, doctor, and administrator interactions. Built with core Object-Oriented Programming (OOP) principles, the system automates appointment scheduling and management, ensuring data integrity with persistent storage in an SQLite relational database.

---

## 🚀 Key Features

### 🔐 **Secure Role-Based Access**
- 👨‍👩‍👧‍👦 **Patient Registration**: New users can self-register for a patient account.
- 🔑 **User Authentication**: Secure login for patients, doctors, and administrators.
- 🚪 **Role-Based Dashboards**: Access to specific menus and functionalities based on user role.

### 📅 **Appointment Management**
- 🩺 **Appointment Booking**: Patients can browse available doctors and book appointments.
- 👁️‍🗨️ **Appointment Views**: Patients and doctors can view their personalized appointment schedules.
- ❌ **Appointment Cancellation**: Both patients and doctors can cancel appointments, which automatically frees up the time slot.

### 👨‍⚕️ **Doctor & Patient Management**
- ⏰ **Availability Setting**: Doctors can easily set and manage their available time slots.
- ✏️ **Profile Editing**: Users can update their personal information (e.g., mobile number, email).
- 📝 **Doctor Administration**: Admins can add and remove doctor accounts from the system.

---

## 🏗️ Project Structure

The project follows a clean, organized package structure: 
```
└── src
    └── com
        └── hms
            ├── app
            │   └── HospitalManagementApp.java
            ├── database
            │   └── DatabaseManager.java
            └── model
                ├── Appointment.java
                ├── AvailabilitySlot.java
                ├── Doctor.java
                ├── Patient.java
                └── User.java
```                                                                                                                                                                  
---

## 💾 Database Schema

The system uses **SQLite** for a lightweight and embedded database. The schema is organized into five main tables:

* **USERS**: Stores login credentials and user roles.
* **PATIENTS**: Contains patient-specific demographic data.
* **DOCTORS**: Stores doctor information, including specialty.
* **APPOINTMENTS**: Records all scheduled appointments.
* **AVAILABILITY_SLOTS**: Manages a doctor's available time slots and their booking status.

---

## 🚀 Getting Started

### Prerequisites
- ☕ **Java 8+** (JDK required for compilation)
- 📚 **SQLite JDBC Driver** (included in `lib/` folder)

### Installation
1.  **Clone the repository:**
    ```bash
    git clone https://github.com/HXF1Z/HospitalManagementSystem.git
    ```
2.  **Open in your IDE:** Open the `HospitalManagementSystem` folder with VS Code or IntelliJ IDEA.
3.  **Configure the classpath:** Add the SQLite JDBC driver (`lib/sqlite-jdbc-3.50.3.0.jar`) to your project's classpath.

### Quick Start
1.  **Run `DatabaseManager.java`** once to create the database schema and populate it with test data.
2.  **Run `HospitalManagementApp.java`** to launch the console-based application.

Refer the user manual on documents folder for clear instructions
---

## 🧑‍💻 Team Members

* **MOHAMMED UAHEEL** - @mohduheail (https://github.com/mohduheail)
* **HAFIZ ABDULLA ABDUL RASHEED** - @HXF1Z (https://github.com/HXF1Z)
* **MUHAMMAD FALAH** - @Falah-10 (https://github.com/Falah-10)
* **MOHAMED SHAZWAN** - @shazwaan (https://github.com/shazwaan)

---

## 📄 License

This project is licensed under the **[MIT License]**.

---

<div align="center">
    
**⭐ Star this repository if you find it helpful!**

</div>
