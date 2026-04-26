# 🚀 API → AWS Data Pipeline (End-to-End Data Engineering Project)

## 📌 Project Overview
This project demonstrates an end-to-end data engineering pipeline that ingests data from a REST API, processes it using ETL techniques, and prepares it for analytics using AWS services.

The pipeline follows a modern **Medallion Architecture (Raw → Curated → Analytics)** and is designed to be AWS production-ready.

---

## 🏗️ Architecture

API (Open Brewery DB)
   ↓
Python Ingestion
   ↓
Raw Data (JSON - S3 Raw Zone)
   ↓
ETL Processing (Pandas / Glue Simulation)
   ↓
Curated Data (Parquet - S3 Curated Zone)
   ↓
Athena SQL Queries
   ↓
QuickSight Dashboard (BI Layer)

---

## ⚙️ Tech Stack
- Python
- Pandas
- Requests
- AWS S3 (Simulated)
- AWS Glue (ETL concept)
- AWS Athena (SQL analytics)
- AWS QuickSight (dashboard layer concept)

---

## 📊 Dataset
Open Brewery DB API (Public REST API)

---

## 🔄 Pipeline Steps

1. Extract data from REST API using Python
2. Store raw JSON data (data lake raw zone)
3. Clean and transform data (ETL processing)
4. Store optimized dataset in Parquet format (curated zone)
5. Run SQL queries using Athena (simulation in SQLite/Pandas)
6. Prepare dataset for QuickSight dashboard visualization

---

## 📈 Key Insights Generated
- Breweries by state
- Distribution of brewery types
- Top cities with highest brewery density

---

## 🧠 Key Learnings
- API data ingestion
- ETL pipeline design
- Data lake architecture (raw + curated zones)
- Data type handling for Parquet (schema enforcement)
- SQL-based analytics (Athena simulation)
- Cloud data engineering workflow

---

## 🚀 How to Run
1. Open Google Colab
2. Upload `pipeline.ipynb`
3. Run all cells sequentially
4. (Optional) Configure AWS credentials for S3 upload

---

## 📌 Future Improvements
- AWS Glue job automation
- Partitioned Parquet storage
- Real Athena table integration
- QuickSight live dashboard
- Airflow orchestration

---
