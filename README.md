 🏥 Hospital Management Database Project

This project is a relational database system built using SQL to manage hospital operations such as patient records, doctor assignments, appointment scheduling, and billing management.

## 📚 Project Overview

The goal of this project is to design and implement a structured, normalized database to support core healthcare workflows. It includes schema definitions and sample data insertion for demonstration and testing.

---

## 🛠️ Tech Stack

- **Database**: MySQL
- **Languages**: SQL

---

## 📁 Files Included

- `hospital-schema.sql` – SQL script to create all necessary tables with constraints and relationships.
- `hospital-data.sql` – SQL script to insert sample data (patients, doctors, appointments, billing, etc.)

---

## 📐 Features

- ✅ **Normalized Schema**: Implemented proper normalization with primary and foreign key constraints to reduce redundancy.
- ✅ **Modular Tables**: Includes `Patients`, `Doctors`, `Appointments`, `Departments`, `Billing`, and `Medications`.
- ✅ **Sample Data**: Pre-filled realistic hospital data to simulate a working environment.
- ✅ **Query Examples**:
  - Track patient appointments by date or department
  - Generate billing reports per patient or time frame
  - Query doctor availability or specialty-based searches

---

## 🧪 How to Run

1. Open MySQL Workbench or your preferred SQL client.
2. Run `hospital-schema.sql` to create tables.
3. Run `hospital-data.sql` to populate tables with sample data.
4. Use provided queries or write your own to test and explore the database.

---

## 🧠 Use Cases

- Academic database modeling
- Mock backend for hospital management software
- Practice writing SQL joins, subqueries, and aggregations
