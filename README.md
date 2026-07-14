# 🚀 Data Engineering Portfolio

A growing portfolio of Cloud and Data Engineering projects, showcasing production-style data pipelines, cloud-native solutions, scalable architectures, and modern data engineering best practices.

---

# [🛒 eCommerce Batch Data Pipeline using PySpark ETL](https://github.com/venkadeshsr/ecommerce-batch-data-pipeline)

A production-style end-to-end e-commerce batch data pipeline built using **Python, PySpark, Apache Airflow, PostgreSQL, and Docker**.

**Phase 1** implements:

- Synthetic CSV data generation
- ODS (Operational Data Store) ingestion
- Bronze → Silver → Gold data processing using PySpark
- PostgreSQL Reporting Mart
- File archival and lifecycle management
- Workflow orchestration with Apache Airflow

The project follows the **Medallion Architecture** and production-oriented ETL design principles, with future phases planned to introduce cloud deployment, data quality validation, monitoring, CI/CD, and real-time data processing.

## 📌 Project Overview

This project simulates a real-world e-commerce batch data pipeline that processes synthetic transactional sales data from ingestion to analytics-ready reporting.

The pipeline generates synthetic CSV files, ingests them into an ODS layer, transforms the data through the **Bronze**, **Silver**, and **Gold** layers using **PySpark**, loads reporting tables into **PostgreSQL**, archives processed files, and orchestrates the complete workflow using **Apache Airflow**.
