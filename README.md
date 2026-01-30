# Pharmacy Management System

A menu-driven **Pharmacy Management System** developed using **Java, JDBC, and MySQL**.  
This project helps manage suppliers, medicines, expiry details, and basic inventory operations.

---

## 📌 Features
- Add supplier details
- Add medicine details
- View all medicines
- View expired medicines
- Delete medicine
- MySQL database integration using JDBC

---

## 🛠️ Technologies Used
- Java (JDK 17)
- JDBC
- MySQL
- Eclipse IDE

---

## 🗄️ Database Details
**Database Name:** `pharmacydb`

### Tables:
- `suppliers`
- `medicines`
- `sales`

---

## ▶️ How to Run the Project
1. Import the project into **Eclipse**
2. Add **MySQL Connector JAR** to build path
3. Create database and tables in MySQL
4. Update database credentials in `DBConnection.java`
5. Run `Main.java


📁Project Structure

PharmacyManagementSystem
├── src
│   └── com
│       └── pharmacy
│           ├── dto
│           │   ├── MedicineDTO.jaStructureupplierDTO.java
│           │   └── SalesDTO.java
│           ├── dao
│           │   ├── MedicineDAO.java
│           │   ├── SupplierDAO.java
│           │   ├── SalesDAO.java
│           │   ├── MedicineDAOImpl.java
│           │   ├── SupplierDAOImpl.java
│           │   └── SalesDAOImpl.java
│           ├── service
│           │   ├── MedicineService.java
│           │   ├── SupplierService.java
│           │   └── SalesService.java
│           ├── util
│           │   └── DBConnection.java
│           └── main
│               └── Main.java
├── database
│   └── pharmacydb.sql
├── README.md
└── src.zip (for GitHub upload)
        
