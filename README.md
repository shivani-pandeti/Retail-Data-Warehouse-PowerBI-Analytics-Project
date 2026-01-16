# 🛒 Retail-Data-Warehouse-PowerBI-Analytics-Project

## 📌 Overview
This project implements an *end-to-end Data Warehouse solution* for a retail *Superstore dataset, covering the complete pipeline from **schema design and ETL processing* to *business intelligence reporting*.

The objective is to transform raw transactional data into a *structured analytical data warehouse* that supports efficient querying, reporting, and decision-making using *SQL and Power BI*.

## 🎯 Project Objectives
•⁠  ⁠Design a scalable *data warehouse schema*  
•⁠  ⁠Implement an ETL pipeline using SQL  
•⁠  ⁠Build fact and dimension tables for analytical querying  
•⁠  ⁠Validate data quality and integrity  
•⁠  ⁠Create interactive dashboards for business insights  


## 🧠 Problem Statement
Operational retail data is often fragmented and not optimized for analytics.  
Direct querying of transactional systems leads to poor performance and limited insight generation.

This project addresses the problem by:
•⁠  ⁠Separating transactional and analytical workloads  
•⁠  ⁠Structuring data using *dimensional modeling*  
•⁠  ⁠Enabling fast, reliable business reporting  


## 🛠️ Tech Stack
•⁠  ⁠*Database & Querying:* SQL  
•⁠  ⁠*Data Modeling:* Star Schema (Facts & Dimensions)  
•⁠  ⁠*ETL:* SQL-based ETL pipeline  
•⁠  ⁠*BI Tool:* Power BI  
•⁠  ⁠*Data Source:* Superstore retail dataset  


## 🗂️ Data Warehouse Architecture

### Schema Design
The warehouse follows a *star schema* with:
•⁠  ⁠*Fact Table:*  
  - Sales metrics (revenue, quantity, profit, discounts)
•⁠  ⁠*Dimension Tables:*  
  - Customer  
  - Product  
  - Time  
  - Geography  
  - Shipping  

This structure enables efficient aggregation and slicing across business dimensions.


## 🔄 ETL Pipeline
The ETL process is implemented step-by-step using SQL scripts:

1.⁠ ⁠*Database & Schema Creation*  
   - Create warehouse schema and base tables  

2.⁠ ⁠*Staging Load*  
   - Load raw data into staging tables  

3.⁠ ⁠*Dimension Build*  
   - Clean, deduplicate, and populate dimension tables  

4.⁠ ⁠*Fact Table Build*  
   - Populate fact tables with transactional measures  

5.⁠ ⁠*Validation Checks*  
   - Data completeness and integrity verification  

6.⁠ ⁠*Final Load*  
   - Load validated data into final warehouse tables  


## 📊 Business Intelligence & Reporting
Power BI dashboards were created on top of the data warehouse to analyze:
•⁠  ⁠Sales and profit trends  
•⁠  ⁠Regional performance  
•⁠  ⁠Customer segmentation  
•⁠  ⁠Product category performance  
•⁠  ⁠Shipping and delivery insights  

These dashboards allow stakeholders to interactively explore retail performance.


## 📈 Key Outcomes
•⁠  ⁠Improved query performance using dimensional modeling  
•⁠  ⁠Clean separation between raw, staging, and analytical layers  
•⁠  ⁠Reliable metrics for executive and operational reporting  
•⁠  ⁠End-to-end demonstration of data warehousing best practices  


## 🚀 Use Cases
•⁠  ⁠Retail sales performance analysis  
•⁠  ⁠Data engineering and analytics portfolio project  
•⁠  ⁠Academic data warehouse implementation  
•⁠  ⁠Business intelligence reporting  


## 📌 Conclusion
This project demonstrates the practical implementation of a *modern data warehouse* using SQL and Power BI.  
By combining structured ETL pipelines, dimensional modeling, and interactive dashboards, it highlights how raw data can be transformed into *actionable business insights*.

 
📍 *Project Type:* End-to-End DW & Analytics Project  
📍 *Focus:* ETL, SQL, Dimensional Modeling, Power BI
