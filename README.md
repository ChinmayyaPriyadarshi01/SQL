📌 Hospital Management System – SQL Project

A complete database system built using MySQL to manage hospital operations such as patient records, doctor details, appointments, admissions, prescriptions, billing, and more.

✅ Project Overview

The Hospital Management System is designed to store, manage, and retrieve all hospital-related information efficiently.
This SQL-based project helps automate hospital operations like:

Managing patient information

Managing doctors & departments

Scheduling appointments

Handling admissions & room allocation

Storing prescriptions & medicines

Generating bills

Tracking staff details

🗂️ Database Structure

The system consists of the following tables:

Table Name	Purpose
Department	Stores hospital department details
Doctor	Contains doctor info & specialization
Patient	Stores patient personal details
Room	Information about rooms (types, charges)
Admission	Patient admission & discharge records
Appointment	Doctor–patient appointment scheduling
Medicine	Medicine inventory & pricing
Prescription	Prescription details from doctors
Prescription_Medicine	Mapping prescriptions to medicines
Bill	Patient billing details
Staff	Non-doctor hospital employees
🏗️ Features Included

✔ Patient registration
✔ Doctor & department management
✔ Appointment scheduling
✔ Room allocation & tracking (Occupied / Free)
✔ Admission & discharge handling
✔ Medicine storage & prescription system
✔ Bill generation with due/paid amounts
✔ Staff records
✔ Sample queries for reports

🛠️ Technologies Used

MySQL – Database

SQL – Schema & queries

Workbench / phpMyAdmin / Terminal – Execution

📥 How to Use
1️⃣ Install MySQL

Make sure MySQL is installed on your system.

2️⃣ Create the Database

Copy and run the full SQL script (hospital_management.sql) in your MySQL Workbench or terminal.

3️⃣ Insert Sample Data

The script includes sample data for testing:

Patients

Doctors

Rooms

Appointments

Admissions

Medicines

Billing

4️⃣ Run Sample Queries

Some useful queries included:

List all doctors with departments

View upcoming appointments

Check room occupancy

View patient prescriptions

Unpaid bill report

📊 Reports You Can Generate

Patients admitted currently

Department-wise doctor list

Doctor-wise appointments

Medicine usage records

Outstanding bills

Room availability

Daily appointment schedule

🧩 ER Diagram (Simple Explanation)

Entities:
Patient, Doctor, Department, Appointment, Admission, Room, Prescription, Medicine, Bill, Staff

Key Relationships:

Department → Doctor (1-to-many)

Doctor ↔ Patient (appointments)

Patient ↔ Room (admissions)

Prescription ↔ Medicine (many-to-many)

Patient → Bill (1-to-many)

🎯 Purpose of the Project

This project demonstrates:

SQL database design

Normalized table creation

Use of primary & foreign keys

Use of JOINs, constraints, and triggers

Real-world hospital workflows

It is suitable for:

College project

Internship project

Company SQL assignment

Portfolio demonstration
