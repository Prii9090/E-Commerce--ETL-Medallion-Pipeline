# **E-Commerce Data Engineering Pipeline (Medallion Architecture)**
## Project Overview
-An end-to-end data pipeline built in Databricks using PySpark and SQL. The project processes raw e-commerce transaction data through a Medallion Architecture (Bronze, Silver, Gold) to generate business-ready KPIs and customer segmentation.

## Tech Stack
-Language: Python (PySpark), SQL

-Platform: Databricks

-Storage: Delta Lake

-Architecture: Medallion (Bronze/Silver/Gold)

## Key Features
Data Cleaning (Silver): Standardized schemas, handled missing values, and validated transaction data.

Aggregations (Gold): Generated country-level sales metrics and monthly revenue trends.

Customer Segmentation: Implemented RFM-style logic to categorize customers into 'Champion', 'Loyal', and 'Standard' segments.

Cross-Language Integration: Used TempViews to bridge PySpark transformations with SQL-based BI reporting.
