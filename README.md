# Hospital Management System

A simple **Java-based Hospital Management System** project that helps manage patients, doctors, and appointments.  
This project is built using **Java, JDBC, and MySQL**.

---

## 🚀 Features
- Add, update, and delete patient records  
- Manage doctor information  
- Book and cancel appointments  
- Database integration with JDBC  

---

## 🛠️ Tech Stack
- Java  
- JDBC  
- MySQL  
- IntelliJ IDEA  

---

## 📂 Database Schema (ER Model)
The system uses a relational database with the following main tables:

- **Patients** (`patient_id`, `name`, `age`, `gender`, `address`, `contact`)  
- **Doctors** (`doctor_id`, `name`, `specialization`, `contact`)  
- **Appointments** (`appointment_id`, `patient_id`, `doctor_id`, `date`, `time`)  

---
📖 Future Improvements

Add a GUI interface ( Swing / Web-based).

Role-based access for Admin, Doctor, and Receptionist.

Generate patient reports and billing system.

