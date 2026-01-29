# Hospital Management System

**Java + MySQL Based Desktop Application**

A full-featured **Hospital Management System (HMS)** developed using **Java (Swing) and MySQL** to automate and manage core hospital operations such as patient records, doctor management, appointment scheduling, and billing.

This project demonstrates practical implementation of **Core Java, JDBC, database design, and modular system architecture** for solving real-world healthcare management problems.

---

## Problem Statement

Traditional hospital systems rely heavily on paperwork and manual processes, which lead to:

* Data redundancy
* Record mismanagement
* Appointment scheduling conflicts
* Billing errors
* Time-consuming administration

This system digitizes hospital operations to improve **efficiency, accuracy, and data security**.

---

## Project Objectives

* Automate hospital administrative tasks
* Maintain structured patient & doctor records
* Simplify appointment management
* Generate accurate billing
* Reduce human errors and paperwork
* Provide centralized data storage

---

## Technology Stack

| Layer                     | Technology Used               |
| ------------------------- | ----------------------------- |
| **Frontend**              | Java Swing / AWT              |
| **Backend Logic**         | Core Java                     |
| **Database**              | MySQL                         |
| **Database Connectivity** | JDBC                          |
| **IDE**                   | IntelliJ                      |

---

## System Architecture

The system follows a **3-layer architecture**:

1. **Presentation Layer** – Java Swing GUI
2. **Business Logic Layer** – Core Java classes
3. **Data Access Layer** – JDBC + MySQL

This separation ensures maintainability and scalability.

---

## System Modules

### 1. Admin Module

* Add / Update / Delete doctors
* Manage hospital staff
* View system reports
* Monitor hospital data

### 2. Doctor Module

* View assigned patients
* Update diagnosis and prescriptions
* Manage appointment schedules

### 3. Patient Module

* Patient registration
* Store personal and medical details
* View treatment history

### 4. Appointment Module

* Book new appointments
* Cancel or reschedule appointments
* Assign doctor & time slot
* Prevent double-booking

### 5. Billing Module

* Generate hospital bills
* Add consultation & treatment charges
* Payment tracking

---

##  Database Design

### Main Tables

| Table Name     | Description                     |
| -------------- | ------------------------------- |
| `patients`     | Patient personal & medical data |
| `doctors`      | Doctor details & specialization |
| `appointments` | Appointment scheduling records  |
| `billing`      | Patient billing information     |
| `admin`        | System admin login              |
| `staff`        | Hospital staff records          |

### Relationships

* **One Doctor → Many Patients**
* **One Patient → Multiple Appointments**
* **One Appointment → One Bill**

---

## Key Features

✔ User-friendly interface
✔ Secure login authentication
✔ Real-time database updates
✔ Centralized hospital data
✔ Fast appointment scheduling
✔ Reduced manual errors
✔ Easy record search and retrieval

---

## Installation & Setup

1. Install **Java JDK 8+**
2. Install **MySQL Server**
3. Import the provided database `.sql` file into MySQL
4. Open the project in your IDE
5. Configure DB credentials in the JDBC connection file
6. Run the main Java class

---

## System Requirements

**Hardware**

* Processor: i3 or higher
* RAM: 4GB+
* Storage: 500MB free

**Software**

* Windows OS
* Java JDK 8+
* MySQL Server

---

## Testing

The system was tested for:

* Login authentication
* Data insertion & retrieval
* Appointment scheduling conflicts
* Billing accuracy
* Database connectivity

All modules were validated successfully.

---

## Future Enhancements

* Web-based version
* Mobile app integration
* Cloud database hosting
* Online patient portal
* E-prescription system
* AI-based health analytics

---

## Developed By

**Mohd Suleman Siddiqui**
B.Tech – Computer Science Engineering

---

## Conclusion

The Hospital Management System effectively demonstrates how **Java and MySQL** can be used to build a real-world software solution that improves hospital workflow, data accuracy, and administrative efficiency.
