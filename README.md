# 📊 Data Warehouse & Analytics: Medallion Architecture Project

## 🚀 Project Overview
This project demonstrates a comprehensive, end-to-end Data Warehouse solution built on **MS SQL Server**. Utilizing the **Medallion Architecture**, I transformed raw, fragmented data from ERP and CRM systems into a high-performance analytical environment.

As an **Aerospace Engineer transitioning to Data Analytics**, I built this project with a focus on structural integrity, precision, and actionable insights.

---

## 🏗️ Data Architecture
The project is structured into three distinct layers to ensure a "single source of truth":

* **Bronze Layer (Raw)**: Direct ingestion of CSV datasets into SQL Server.
* **Silver Layer (Cleaned)**: Standardization of data types, deduplication, and handling of missing values.
* **Gold Layer (Curated)**: A **Star Schema** consisting of Fact and Dimension tables, optimized for complex analytical joins.

### 🖼️ High-Level Architecture
![High Level Architecture](https://github.com/user-attachments/assets/e08927cb-ae6e-411c-b23b-e91c44d59ed1)

---

## 🔍 Exploratory Data Analysis (EDA) & Business Insights
The project goes beyond ETL to deliver business value through SQL-driven analytics:

### **1. Data Profiling & Cleaning (EDA)**
* Identified and resolved data quality issues (e.g., null handling in CRM records).
* Validated referential integrity between ERP sales records and CRM customer profiles.

### **2. Business Intelligence (BI)**
* **Customer Behavior**: Segmented customers based on purchasing patterns and geographic data.
* **Product Performance**: Analyzed top-grossing products and seasonal sales trends.
* **Strategic Metrics**: Calculated Year-over-Year (YoY) growth and profit margins using T-SQL window functions.

---

## 📂 Repository Structure
```bash
data-warehouse-project/
├── datasets/           # Raw ERP & CRM CSV files
├── docs/               # Architecture diagrams, Data Catalog, & Naming Conventions
├── scripts/
│   ├── bronze/         # SQL scripts for raw data loading
│   ├── silver/         # Transformation & cleaning logic
│   └── gold/           # Analytical Star Schema & Business Views
├── tests/              # Data validation and quality check scripts
└── README.md           # Project documentation
