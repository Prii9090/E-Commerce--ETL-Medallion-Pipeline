# **E-Commerce Data Engineering Pipeline (Medallion Architecture)**
## Project Overview
-An end-to-end data pipeline built in Databricks using PySpark and SQL. The project processes raw e-commerce transaction data through a Medallion Architecture (Bronze, Silver, Gold) to generate business-ready KPIs and customer segmentation.

## Tech Stack
-Language: Python (PySpark), SQL

-Platform: Databricks

-Storage: Delta Lake

-API/Connectivity: Leveraged createOrReplaceTempView to bridge Spark DataFrames with SQL analytics.

-Architecture: Medallion (Bronze/Silver/Gold)

## Key Features
-Data Cleaning (Silver): Standardized schemas, handled missing values, and validated transaction data.

-Aggregations (Gold): Generated country-level sales metrics and monthly revenue trends.

-Customer Segmentation: Implemented RFM-style logic to categorize customers into 'Champion', 'Loyal', and 'Standard' segments.

-Cross-Language Integration: Used TempViews to bridge PySpark transformations with SQL-based BI reporting.

## Business Insights Generated
-Market Health: Identified top-performing countries by revenue and customer density.

-Retention Analysis: Categorized the customer base to identify "At-Risk" revenue from segments with declining activity.

-Data Quality: Built monitoring queries to track missing IDs and unvalidated transactions.

<img width="1004" height="625" alt="image" src="https://github.com/user-attachments/assets/e5f42b2d-2d9f-4290-ae2c-4acb88d61871" />





<img width="1159" height="807" alt="image" src="https://github.com/user-attachments/assets/52630f2b-7d65-4396-9ca5-81383a1af612" />






<img width="1161" height="833" alt="image" src="https://github.com/user-attachments/assets/dbe367bd-2620-4d9e-94d6-d7c4393bde0d" />




