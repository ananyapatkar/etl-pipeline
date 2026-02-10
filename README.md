# etl-pipeline

## Overview
This repository contains a mini ETL (Extract, Transform, Load) pipeline built using Python and pandas.
The Superstore Sales dataset is used to demonstrate real-world ETL operations.

## ETL Steps
### Extract
- Loaded Superstore CSV dataset using pandas.

### Transform
- Removed duplicate records.
- Converted Order Date and Ship Date to datetime format.
- Created derived columns:
  - Profit_Margin
  - High_Discount flag
- Split data into Customers, Products, and Orders tables.

### Load
- Exported processed data into CSV files.
- Loaded all tables into a SQLite database.
