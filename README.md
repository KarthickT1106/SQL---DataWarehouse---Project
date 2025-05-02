# 📊 Data Warehouse Integration Project
This project focuses on integrating CRM and ERP data into a data warehouse for further analysis. It handles sales, customer, and product data, transforming raw data into a structured format for Exploratory Data Analysis (EDA).

---
## 🏗️ Data Architecture

The data architecture for this project follows Medallion Architecture **Bronze**, **Silver**, and **Gold** layers:
![DWH Architecture drawio](https://github.com/user-attachments/assets/aeca247b-2cac-4e18-b304-0ee59ec6423a)

1. **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2. **Silver Layer**: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3. **Gold Layer**: Houses business-ready data modeled into a star schema required for reporting and analytics.
---
## 📖 Project Overview

This project involves:

1. **Data Architecture**: Designing a Modern Data Warehouse Using Medallion Architecture **Bronze**, **Silver**, and **Gold** layers.
2. **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse.
3. **Data Modeling**: Developing fact and dimension tables optimized for analytical queries.

---
## 🚀 Project Requirements

### Building the Data Warehouse (Data Engineering)

#### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

#### Specifications
- **Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality**: Cleanse and resolve data quality issues prior to analysis.
- **Integration**: Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Scope**: Focus on the latest dataset only; historization of data is not required.
- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.

---
## 📖 Data Integration
This picture easily understand how tables are integrated.
![data modelling drawio](https://github.com/user-attachments/assets/80dc3b97-f6be-46a9-be70-6df68ed37a84)

---

## 📖 Data Flow
This picture easily understand how data are flow from one level to next level.
![data_flow](https://github.com/user-attachments/assets/73bb46ec-7d64-49d5-b2bb-4fd7ef655761)


---

## ➡️ Next Step

👉 “The data has been cleaned and organized; the next step is to perform exploratory data analysis (EDA) and create visualizations for insights.





