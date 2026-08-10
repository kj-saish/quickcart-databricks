# QuickCart - End-to-End Databricks Data Engineering Project

## Project Overview

QuickCart is an end-to-end data engineering project built using Databricks.

The project demonstrates:

- PySpark
- SQL
- Delta Lake
- Medallion Architecture
- Batch and Streaming Processing
- Data Quality
- SCD Type 2
- Incremental Data Processing
- Lakeflow Pipelines
- Lakeflow Jobs
- Unity Catalog
- Databricks SQL

## Current Progress

### Phase 1 - Source Data Generation

Generated source datasets:

- Customers - 100,000 records
- Products - 5,000 records
- Orders - 1,000,000 records
- Payments - ~1,000,000 records
- Deliveries - ~950,000 records

Also simulated source-system data quality issues:

- Duplicate records
- Updated records
- NULL values
- Invalid foreign keys
- Invalid business values
- Late-arriving records

## Architecture

Source Systems > Bronze > Silver > Gold > Databricks SQL 