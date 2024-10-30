# Azure End-to-End Data Pipelining Real-Time Project 
## Overview

This project builds a data pipeline on Azure to process and visualize customer and sales data from an on-prem SQL database. The end goal is a Power BI dashboard that tracks KPIs like gender distribution and product category sales, with filters for dates, categories, and gender to support better business analysis.

## Solution Structure

- **Data Ingestion**: Extracts data from SQL, loads it to Azure Data Lake via Data Factory.
- **Transformation**: Uses Databricks to clean and organize data into Bronze, Silver, and Gold layers.
- **Reporting**: Loads refined data into Synapse Analytics and builds Power BI dashboard.
- **Automation**: Schedules daily data refreshes.

## Tech Stack

- **Azure Data Lake Storage (ADLS)**: For storing raw and processed data.
- **Azure Databricks**: For data transformation and processing.
- **Azure Synapse Analytics**: For data warehousing and SQL-based analytics.
- **Power BI**: For data visualization and reporting.
- **Azure Key Vault**: For securely managing credentials and secrets.
- **SQL Server (On-Premises)**: Source of customer and sales data.
