# Microsoft-fabric-stock-market-analytics-and-monitoring-system

# Microsoft Fabric Stock Market Analytics & Monitoring System

## 🚀 Overview

This project demonstrates an end-to-end real-time data engineering solution using Microsoft Fabric, implementing a Medallion Architecture (Bronze, Silver, Gold) for stock market analytics and monitoring.

## 🏗 Architecture

* Eventstream → Lakehouse (Bronze)
* Silver layer (cleaned, deduplicated, enriched)
* Gold layer (aggregated KPIs)
* Power BI dashboard
* Alerting system

fabric-stock-market-analytics/
│
├── README.md
├── architecture/
│   └── architecture-diagram.png
│
├── data/
│   └── sample_data.csv
│
├── notebooks/
│   ├── bronze_ingestion.ipynb
│   ├── silver_transformation.ipynb
│   ├── gold_kpi.ipynb
│
├── sql/
│   ├── create_bronze.sql
│   ├── create_silver.sql
│   ├── create_gold.sql
│   ├── merge_silver.sql
│   ├── alerts.sql
│
├── powerbi/
│   └── dashboard.pbix
│
└── docs/
    └── design.md

## ⚙️ Technologies

* Microsoft Fabric (Lakehouse, Eventstream)
* Spark SQL / Delta Lake
* Power BI
* SQL

## 📊 Features

* Real-time stock data ingestion
* Data transformation & cleansing
* Financial KPIs (spread, volatility, moving averages)
* Incremental processing using MERGE
* Row-Level Security (RLS)
* Alerting system for anomalies

## 🔐 Security

Implemented dynamic Row-Level Security (RLS) in Power BI using user-based filtering.

## 🚨 Alerts

* High volatility detection
* Price spike alerts
* Liquidity (spread) monitoring

## 📈 Dashboard

Power BI dashboard provides:

* Market trends
* Top gainers/losers
* Volume & volatility insights

## 🧠 Key Learnings

* Medallion architecture in Fabric
* Real-time data streaming
* Incremental data pipelines
* Data governance and security

## 📂 Repository Structure

See folder structure for SQL scripts, notebooks, and dashboard files.

## 👤 Author

Rita Uzoka

<img width="1200" height="609" alt="image" src="https://github.com/user-attachments/assets/792264c3-49a2-4142-9c38-47ad49050c8b" />



<img width="1195" height="615" alt="image" src="https://github.com/user-attachments/assets/271a51cf-2a01-47b6-9d2b-0f10c0afc702" />



