# 🎬 Movie Rental Data Warehouse

## 📖 Overview
This project focuses on designing and building a **Hybrid Data Warehouse Model** for a Movie Rental business using an existing OLTP database schema.

The original OLTP database handles daily operations such as:
- Customer management
- Film inventory
- Rentals and payments
- Store and staff operations

Since OLTP systems are not optimized for analytics, this project transforms operational data into a data warehouse structure that supports reporting and business analysis.

---

# 🎯 Project Objectives
- Analyze the Movie Rental OLTP schema
- Design a **Hybrid Dimensional Model**
- Build ETL pipelines using Python
- Create analytical structures for reporting and insights

---

# 🏗️ Data Warehouse Design

The project uses a **Hybrid Schema Design** combining:
- Star Schema concepts
- Snowflake Schema normalization where needed

### 📊 Fact Tables
- `fact_rental_film`
- `fact_rental_customer`
- `fact_payment`

### 🧩 Dimension Tables
- `dim_customer`
- `dim_film`
- `dim_category`
- `dim_store`
- `dim_staff`
- `dim_date`

### 🔗 Bridge Table
- `bridge_film_category`

---

# ⚙️ ETL Process

The ETL pipeline was implemented using Python.

### 🔹 Extract
Data is extracted from the Sakila OLTP database.

### 🔹 Transform
Data is cleaned, transformed, and organized into dimensional structures.

### 🔹 Load
Processed data is loaded into the Movie Rental Data Warehouse.

---

# 🛠️ Technologies Used
- Python
- Pandas
- SQLAlchemy
- MySQL
- ETL Processes
- Dimensional Modeling

---

# 📈 Business Insights Supported
The data warehouse enables:
- Revenue analysis
- Rental trend analysis
- Customer behavior analysis
- Film popularity tracking
- Store performance evaluation

---

# 🚀 Project Outcome
A scalable Hybrid Data Warehouse model that supports analytical reporting and business intelligence for the Movie Rental system.

---

# 👩‍💻 Author
SARA OTHMAN
TASNEEM ASHOUR
BERLANTI MASALHA
