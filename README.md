# sql-data-warehouse-project
Building a modern data warehouse with SQL Server, including ETL processes, data modeling, and analytics.
------------------------------
Data Architecture
------------------------------
The data architecture for this project follows Medallion Architecture Bronze, Silver, and Gold layers:
![image](https://github.com/user-attachments/assets/e2d77492-02ec-4942-84d5-1ee4d7e34731)

Bronze Layer: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
Silver Layer: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
Gold Layer: Houses business-ready data modeled into a star schema required for reporting and analytics.

-------------------------------
Project Overview
-------------------------------
This project involves:

 1. Data Architecture: Designing a Modern Data Warehouse Using Medallion Architecture Bronze, Silver, and Gold layers.
 2. ETL Pipelines: Extracting, transforming, and loading data from source systems into the warehouse.
 3. Data Modeling: Developing fact and dimension tables optimized for analytical queries.
 4. Analytics & Reporting: Creating SQL-based reports and dashboards for actionable insights.
