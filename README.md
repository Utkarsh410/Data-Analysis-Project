📊 ##Data Warehouse & Analytics: Medallion Architecture Project

🚀 ###Project Overview
This project demonstrates a robust, end-to-end Data Warehouse solution built on MS SQL Server. Moving from raw CSV sources (ERP & CRM) to a refined Gold Layer, I implemented the Medallion Architecture to ensure data integrity, scalability, and high-performance analytics.

As an Aerospace Engineer transitioning into Data, I applied a "Safety-Critical" mindset to data quality—ensuring that every transformation is documented, tested, and optimized for business decision-making.

🏗️ ###Data Architecture
The project follows a tiered approach to transform raw data into business intelligence:

Bronze Layer (Raw): Ingestion of disparate CSV files from ERP and CRM systems into SQL Server.

Silver Layer (Cleaned): Data deduplication, handling null values, and normalizing formats (Date/Currency).

Gold Layer (Curated): A high-performance Star Schema optimized for analytical queries and BI tools.

🖼️ ###High-Level Architecture
🔍 ###Exploratory Data Analysis (EDA) & Insights
Beyond the engineering, I conducted deep-dive analysis to extract value from the data:

Customer Behavior: Segmented CRM data to identify high-value demographics and purchasing patterns.

Product Performance: Analyzed sales trends to pinpoint top-performing categories and seasonal fluctuations.

Data Integrity Reports: Created SQL scripts to identify "Orphaned Records" between the ERP and CRM systems during the integration phase.

📂 ###Repository Structure
Bash
data-warehouse-project/
├── datasets/           # Raw ERP & CRM CSV files
├── docs/               # Architecture diagrams (.drawio) & Data Catalog
├── scripts/
│   ├── bronze/         # DDL scripts for raw data ingestion
│   ├── silver/         # DML scripts for cleaning & standardization
│   └── gold/           # Final Fact & Dimension table creation (Star Schema)
├── tests/              # Data quality & validation scripts
└── README.md           # Project documentation
🛠️ ###Technical Stack
Database: Microsoft SQL Server (MS SQL)

Language: T-SQL (Advanced Joins, CTEs, Window Functions, Stored Procedures)

Modeling: Star Schema (Fact & Dimension Tables)

Tools: Draw.io (Architecture Design), Git/GitHub (Version Control)

🏁 ###How to Run This Project
Clone the Repo: git clone https://github.com/Utkarsh410/Data-Analysis-Project.git

Environment: Open SQL Server Management Studio (SSMS).

Execution Order:

Run all scripts in /scripts/bronze/ to create the landing zone.

Execute /scripts/silver/ to clean and unify the data.

Execute /scripts/gold/ to build the final analytical layer.

🌟 ###About Me
Utkarsh Chaudhari Aerospace Engineer | Aspiring Data Analyst I specialize in transforming complex, fragmented datasets into structured, reliable assets. My engineering background provides a unique perspective on process optimization and analytical rigor.

🔗 LinkedIn 🔗 Notion Portfolio
