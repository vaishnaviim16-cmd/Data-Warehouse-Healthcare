# Data-Warehouse-Healthcare
This project demonstrates the design and implementation of an enterprise-grade Healthcare Claims Data Warehouse using modern data engineering practices.

The solution follows a layered architecture:
- Bronze (Raw Ingestion Layer)
- Silver (Data Vault 2.0 Modeling)
- Gold (Dimensional Modeling - Star Schema)

The warehouse supports analytics use cases such as claims trends, rejection rates, provider performance, and financial reporting.

---

## Objectives

- Design an enterprise data warehouse using Data Vault 2.0
- Implement Star Schema for analytics consumption
- Handle incremental and CDC-based loads
- Implement data quality validation framework
- Support KPI-driven analytics reporting
- Demonstrate production-grade folder structure and documentation

---

## Architecture (High Level)

Source Data → Bronze Layer (Raw Delta Tables)  
→ Silver Layer (Data Vault: Hubs, Links, Satellites)  
→ Gold Layer (Fact & Dimension Tables - Star Schema)  
→ Analytics / BI Consumption

---

## Tech Stack

- Python
- PySpark
- Delta Lake
- Databricks
- AWS S3 (optional deployment)
- SQL

---

