# Data Warehouse and Analytics Project

This repository showcases an end-to-end data warehouse and analytics solution built using SQL Server.
The goal of this project is to demonstrate modern data engineering fundamentals — from ingesting raw CSV data to designing a star schema, building a warehouse, and generating insights using SQL.

This project was inspired by Baraa Alomari’s SQL Server data warehouse tutorial series, adapted and extended in my own style for learning and portfolio purposes.

---

## Project Overview 

### Building the Data Warehouse (Data Engineering)

The purpose of the project is to build a small but realistic data warehouse suitable for analytical reporting.
It covers:

- Data ingestion
- Data cleaning
- Data transformation
- Data modelling (star schema)
- Analytical SQL queries
- Documentation

This project reflects industry best practices and demonstrates my growing skills in data engineering, SQL, and analytics.

---

### 1. Data Warehouse Development (Data Engineering)

#### Objective

Create a SQL Server–based data warehouse that integrates data from multiple systems and supports analytical reporting.
These insights empower stakeholders with key business metrics, enabling strategic decision-making.

####Key Steps

#### - Data Sources
Two datasets representing an ERP and CRM system, supplied as CSV files.

#### - Data Cleaning & Quality Checks
Handling missing values, correcting data types, resolving inconsistencies, and enforcing referential integrity.

#### - Data Integration
Consolidating both datasets into staging tables, transforming them, and loading them into a dimensional model.

#### - Data Model
Star schema including:

#### - Fact table (Sales)
Dimension tables (Customer, Product, Date, etc.)

#### - Assumptions
 - Only current records are required (no historical tracking).
 - Focus is on analytical readiness rather than operational reporting.

#### - Documentation
ERD diagrams and process notes are provided to support stakeholders and demonstrate understanding of warehouse design.


---

### 2. BI & Analytics (Data Analytics)
#### Objective
Develop SQL queries that generate insights for business stakeholders.

#### Insight Areas

#### - Customer behaviour
Segmentation, repeat purchasing, customer value.

#### - Product performance
Best-selling categories, product profitability, trends.

#### - Sales trends
Time-series analysis, seasonality, regional performance.

The analytics layer demonstrates how the warehouse supports decision-making.

## Licence

This project is licensed under the [MIT License](LICENSE). 
You are free to use, modify and share this project with proper attribution.

## About Me

I'm **David Northey**, working in the pharmaceutical industry with a strong interest in expanding my skills into data engineering, analytics, and cloud data solutions.
This project forms part of my broader learning journey and portfolio.

