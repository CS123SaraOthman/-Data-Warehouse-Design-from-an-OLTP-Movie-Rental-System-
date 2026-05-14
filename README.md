# 🎬 Movie Rental Data Warehouse

## 📖 Overview
This project presents the design and implementation of a **Data Warehouse** for a Movie Rental business based on an existing OLTP database schema.

The original OLTP system is designed for day-to-day transactions such as:
- Managing customers
- Processing rentals and payments
- Handling film inventory
- Managing stores and staff

To support analytical reporting and business intelligence, the operational data was transformed into a **Dimensional Data Warehouse Model** using ETL processes.

---

# 🎯 Project Objectives
- Analyze the OLTP movie rental schema
- Design a scalable **Star Schema**
- Create fact and dimension tables
- Build ETL pipelines using Python
- Support analytical queries and reporting

---

# 🏗️ Data Warehouse Architecture

## ⭐ Fact Tables
- `fact_rental_film`
- `fact_rental_customer`
- `fact_payment`

## 🧩 Dimension Tables
- `dim_customer`
- `dim_film`
- `dim_category`
- `dim_store`
- `dim_staff`
- `dim_date`

## 🔗 Bridge Table
- `bridge_film_category`

---

# ⚙️ ETL Pipeline

The ETL process was developed using **Python**, `Pandas`, and `SQLAlchemy`.

### 🔹 Extract
Data is extracted from the Sakila OLTP database.

### 🔹 Transform
Data is cleaned, merged, transformed, and organized into dimensional structures.

### 🔹 Load
Processed data is loaded into the Data Warehouse tables in MySQL.

---

# 🛠️ Technologies Used
- Python
- Pandas
- SQLAlchemy
- MySQL
- Dimensional Modeling
- ETL Processes

---

# 📊 Business Analysis Capabilities
The Data Warehouse supports analysis such as:
- Rental trends over time
- Revenue analysis
- Customer behavior insights
- Film popularity tracking
- Store performance evaluation

---

# 🚀 Project Outcome
This project demonstrates how transactional data can be transformed into a structured analytical system that supports reporting, business intelligence, and data-driven decision making.
