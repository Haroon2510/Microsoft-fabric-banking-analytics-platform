# Microsoft Fabric Banking Analytics & Data Quality Platform

## Project Overview

This project demonstrates an end-to-end Banking Analytics and Data Quality solution built using Microsoft Fabric. The solution follows a Medallion Architecture approach, utilizing Lakehouse, Notebooks, Pipelines, Warehouse, Semantic Models, and Power BI dashboards to transform raw banking data into actionable business insights.

## Business Objective

The objective of this project is to:

* Analyze banking loan portfolios.
* Monitor data quality issues.
* Track customer and loan performance.
* Implement automated data processing workflows.
* Build enterprise-style reporting and analytics dashboards.

---

## Technology Stack

* Microsoft Fabric
* Lakehouse
* Notebook (Python, Pandas, NumPy)
* Data Factory Pipeline
* Warehouse
* SQL
* Semantic Model
* Power BI
* DAX

---

## Architecture

Excel Files
→ Lakehouse Files (Bronze Layer)
→ Notebook Data Transformation
→ Lakehouse Tables (Silver Layer)
→ Pipeline Copy Activity
→ Warehouse
→ Fact & Dimension Tables
→ Semantic Model
→ Power BI Dashboard
→ Automated Refresh

---

## Data Quality Framework

Implemented data validation rules including:

* Missing Customer Name
* Missing Loan Amount
* Duplicate Record
* Leading/Trailing Spaces


Generated:

* DQ Exceptions Table
* DQ Summary Table

---

## Dimensional Model

### Fact Table

FactLoans

### Dimension Tables

* DimCustomer
* DimBank
* DimLoanType
* DimDate

Implemented a Star Schema model to support analytical reporting and KPI calculations.

---

## Key KPIs

* Total Loans
* Total Loan Amount
* Average Interest Rate
* Average Credit Score
* Monthly Income Analysis
* Data Quality Accuracy %
* Loan Portfolio Analysis

---

## Automation

* Fabric Pipelines for data movement.
* Scheduled Semantic Model Refresh.
* Automated reporting workflow.

---

## Key Learnings

* Microsoft Fabric Lakehouse architecture
* Data Quality management
* Data Warehousing concepts
* Dimensional Modeling
* Power BI Semantic Models
* End-to-End Analytics Automation

---

## Screenshots

* Lakehouse: <img width="706" height="271" alt="image" src="https://github.com/user-attachments/assets/754a4c40-ae61-4e40-afad-ef437b736f85" />
* Notebook: <img width="638" height="329" alt="image" src="https://github.com/user-attachments/assets/6b528c56-9de3-48d6-b001-99c23ff172ab" />
* Pipeline: <img width="365" height="428" alt="image" src="https://github.com/user-attachments/assets/e354ca9d-3fa7-4a85-bc9b-cf6e2293e06f" />
             <img width="424" height="398" alt="image" src="https://github.com/user-attachments/assets/cd6cbfee-9ff1-4ed3-aa08-f68749ca6710" />
* Warehouse: <img width="258" height="449" alt="image" src="https://github.com/user-attachments/assets/b1c00802-8ea1-4a33-85ae-8933b6500820" />
* Semantic Model: <img width="616" height="404" alt="image" src="https://github.com/user-attachments/assets/37a31611-db05-4d62-8fed-f49a5bdaa197" />
* Overall Architecture: <img width="511" height="388" alt="image" src="https://github.com/user-attachments/assets/9ecb094d-41ea-442d-9e3d-be35181f41cc" />





## Author

Haroon Ul Rasheed

LinkedIn: https://www.linkedin.com/in/haroon-rasheed-914a49145/

GitHub: https://github.com/Haroon2510
