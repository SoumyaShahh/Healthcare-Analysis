# 🏥 Healthcare Analytics Dashboard Project


> A Business Intelligence project leveraging a star schema data warehouse and powerful visualizations to provide healthcare administrators, clinicians, and insurance providers with actionable insights into patient profiles, billing trends, and resource planning.

---

## 📌 Project Overview

This academic project analyzes a **1M-record** healthcare dataset using Power BI and SQL Server. We built a star schema warehouse, developed ETL pipelines, and explored key insights. KPIs tracked include patient distribution, doctor performance, billing trends, and treatment success rates.
These insights help optimize operations, improve care quality, and refine healthcare strategies.

---

##  Key Components

### 1. Data Warehouse Design using **Microsoft Visio**
- **Star Schema** model
  - **Fact Table**: `HospitalEncounterFact`
  - **Dimension Tables**: `Patient`, `Hospital`, `Insurance Provider`
- **Grain**: One row per patient encounter

### 2. ETL Workflow

![ETL Workflow](https://github.com/SoumyaShahh/Healthcare-Analysis/blob/main/screenshots/etl.png)

- Built using **SSIS** (SQL Server Integration Services)
- Source: Excel Dataset → Destination: SQL Server Data Warehouse
- Included:
  - Data Cleaning & Preprocessing
  - Outlier Detection
  - Data Normalization
  - One-hot Encoding

### 3. Data Analysis & Visualization
- Tools: **Power BI**, **SQL Server**, **Excel**
### 📊 Power BI Features Included

- **Hierarchical drill-downs** for multi-level data exploration  
- **Interactive slicers** by gender, age, hospital, and condition  
- **Custom KPIs** built using DAX expressions  
- **Cross-filtering** across visuals for dynamic insights  
- **Dual-axis** and **tree map** visualizations for trend and category analysis  


### 4. Predictive Modeling
- Model predicted:
  - **Billing Amount**
  - **Length of Stay**
- Techniques: Regression models on historical patient and treatment data

---

## 📊 Dashboard Highlights

Key Performance Indicators:
  - Patient Overview by Condition & City:
    
    ![Dashboard Preview](https://github.com/SoumyaShahh/Healthcare-Analysis/blob/main/screenshots/Dashboard%201.png)
    
  - Doctor Performance & Cost Insights:
    
    ![Dashboard Preview](https://github.com/SoumyaShahh/Healthcare-Analysis/blob/main/screenshots/Dashboard%202.png)
    
  - Patient Journey Breakdown:
    
    ![Dashboard Preview](https://github.com/SoumyaShahh/Healthcare-Analysis/blob/main/screenshots/Dashboard%203.png)
    
  - Billing and Admission Trends:
    
    ![Dashboard Preview](https://github.com/SoumyaShahh/Healthcare-Analysis/blob/main/screenshots/Dashboard%204.png)
    
  - Insurance & Payment Analytics:
    
    ![Dashboard Preview](https://github.com/SoumyaShahh/Healthcare-Analysis/blob/main/screenshots/Dashboard%205.png)

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
