# 🎬 Netflix ETL Data Pipeline

## 🧑‍💻 Role
**Data Engineer — Netflix Data Pipeline Project**

---

## 🧰 Tech Stack
- **Languages & Tools:** Python, SQL, SQLAlchemy, Pandas, PostgreSQL  
- **Concepts:** ETL, Data Modeling, Data Cleaning, Automation (Cron / Airflow)

---

## 📘 Project Overview
This project demonstrates a complete **ETL (Extract, Transform, Load)** data pipeline built for the **Netflix catalog dataset**.  
It extracts raw Netflix data, transforms it into a clean relational model, and loads it into a PostgreSQL database using Python and SQLAlchemy.

---

## ⚙️ Pipeline Workflow

1. **Extract:**  
   - Collects raw Netflix catalog data from CSV or API sources.  
   - Handles missing values and schema validation.

2. **Transform:**  
   - Cleans and standardizes columns (e.g., date formats, categories, multi-value fields).  
   - Splits data into relational structures using Pandas.  
   - Generates bridge tables for many-to-many relationships (e.g., titles ↔ genres, titles ↔ cast).

3. **Load:**  
   - Uses SQLAlchemy ORM for structured loading into PostgreSQL.  
   - Includes bulk insert optimization and database indexing for performance.  

---

## 🗃️ Database Design
Created a normalized schema with relational tables for:
- **Titles**
- **Genres**
- **Countries**
- **Cast**
- **Crew**
- **Bridge tables** to represent many-to-many relationships.

📊 **Entity Relationship Diagram (ERD):**  
_(You can insert your ERD image here once you upload it to the repo, e.g.)_
```markdown
![ERD Diagram](erd-diagram.png)
