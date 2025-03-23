# 🏥 Healthcare Analytics Dashboard Project

![Dashboard Preview](https://github.com/SoumyaShahh/Healthcare-Analysis/blob/main/screenshots/Dashboard%201.png)

> A Business Intelligence project leveraging a star schema data warehouse and powerful visualizations to provide healthcare administrators, clinicians, and insurance providers with actionable insights into patient profiles, billing trends, and resource planning.

---

## 📌 Project Overview

This project was developed as part of an academic course and focuses on analyzing a comprehensive **healthcare dataset** through the lens of business intelligence. We designed a **star schema-based data warehouse**, implemented ETL pipelines, and performed data analysis and visual exploration using Power BI and SQL Server to uncover insights into hospital operations, patient demographics, treatment outcomes, and financial performance.

---

## 🧩 Key Components

### 1. Data Warehouse Design using **Microsoft Visio**
- **Star Schema** model
  - 🧮 **Fact Table**: `HospitalEncounterFact`
  - 🧩 **Dimension Tables**: `Patient`, `Hospital`, `Insurance Provider`
- **Grain**: One row per patient encounter

### 2. ETL Workflow
- Built using **SSIS** (SQL Server Integration Services)
- Source: Excel Dataset → Destination: SQL Server Data Warehouse
- Included:
  - Data Cleaning & Preprocessing
  - Outlier Detection
  - Data Normalization
  - One-hot Encoding

### 3. Data Analysis & Visualization
- Tools: **Power BI**, **SQL Server**, **BigQuery**
- Sample insights:
  

### 4. Predictive Modeling
- Model predicted:
  - **Billing Amount**
  - **Length of Stay**
- Techniques: Regression models on historical patient and treatment data

---

## 📊 Dashboard Highlights

Key Performance Indicators:
  - Top-performing doctors by recovery rate: ![Dashboard Preview](https://github.com/SoumyaShahh/Healthcare-Analysis/blob/main/screenshots/Dashboard%202.png)
  - Cost of treatment per doctor:  ![Dashboard Preview]()
  - Financial contributions by insurance providers: ![Dashboard Preview](https://github.com/SoumyaShahh/Healthcare-Analysis/blob/main/screenshots/Dashboard%205.png)
  - Billing patterns over time: ![Dashboard Preview]()

---

## 🧠 Business Implications

- **Hospital Planning**: Improved infrastructure and workload distribution
- **Insurance Providers**: Financial insight by region/condition
- **Patients**: Estimated treatment costs and doctor success rates
- **Policy Makers**: Identifying city-level medical hotspots

---

## 🛠 Tech Stack

- **ETL**: SSIS, Apache Spark, Python
- **Database**: SQL Server, BigQuery
- **Modeling**: Power BI, Excel
- **Tools**: AWS, SSMS, Visual Studio, Power Query

---

```
