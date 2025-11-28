# hospital-management-ABHISHEK
ASSIGNMENT 3
# Hospital Patient Management System (Python OOP Mini Project)

This is my Unit-3 mini project for the course **Problem Solving with Python**.  
The project manages hospital patients, doctors, and doctor-patient assignments
using Object-Oriented Programming, JSON file handling, and exception handling.

All the data is stored inside a JSON file (`records.json`), and the program runs
as a menu-driven CLI.

---

## 👤 Student Details
**Name:** Abhishek
**Roll No:** 2501060156  
**Program:** BCA (AI & DS)  
**Section:** C  

---

# Project Features

### ✔ Patient Management
- Add new patients  
- Store name, age, disease, and status (Admitted/Discharged)  
- Discharge a patient  
- Search patient by ID  
- View all patients  

### ✔ Doctor Management
- Add doctors  
- Store name, specialization, and doctor ID  
- Search doctor  
- View all doctors  

### ✔ Doctor Assignment System
- Assign doctor to a patient  
- View all current doctor–patient assignments  
- Automatically removes assignment when a patient is discharged  

### ✔ JSON File Storage
- All data saved in `data/records.json`  
- Uses `pathlib` for safe file handling  
- Handles missing files, corrupted JSON, and unexpected errors  

### ✔ CLI Menu
The main menu includes:
1. Add Patient  
2. Add Doctor  
3. Assign Doctor  
4. Search Patient  
5. Search Doctor  
6. View All Patients  
7. View All Doctors  
8. Discharge Patient  
9. View Assignments  
0. Exit  

## 📁 Project Structure

