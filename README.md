🚖 Azure Data Engineering Project – NYC Taxi Data
📌 Overview

This project demonstrates a modern data engineering pipeline using Azure Data Services and Databricks for ingesting, transforming, and analyzing large-scale data. The dataset used is the NYC Taxi Trip Records, a popular real-world dataset for big data and analytics.

The solution follows the Medallion Architecture (Bronze → Silver → Gold) and integrates with Power BI for reporting and visualization.

🏗️ Architecture

🔑 Key Stages

Ingestion (Bronze Layer)

Data ingested using Azure Data Factory from NYC Taxi API.

Raw data stored in Azure Data Lake Storage Gen2 in Parquet format.

Transformation (Silver Layer)

Data cleaned, validated, and transformed using Azure Databricks (PySpark).

Stored in Parquet format in the Silver zone.

Serving (Gold Layer)

Processed data written into Delta Lake tables.

Optimized for BI & Analytics use cases with Delta Lake features like ACID transactions, versioning, and time travel.

Reporting & Analytics

Power BI connected with Delta Lake to build dashboards for taxi trip insights.

Security

Secured with Azure Active Directory (AAD) and Azure Key Vault for access management.

⚙️ Technologies & Services Used

Azure Data Factory – Data ingestion pipelines

Azure Data Lake Gen2 – Scalable data storage

Azure Databricks (PySpark) – Data transformation & analytics

Delta Lake – Reliable data lake with ACID transactions

Power BI – Reporting & visualization

Azure AD & Key Vault – Security & governance

📊 Dataset

Source: NYC Taxi Trip Records

Data includes taxi trips with timestamps, locations, fares, tips, and more.

Data ingested via API and processed into structured analytical datasets.


🚀 Features

✔ End-to-end data pipeline (Ingestion → Transformation → Reporting)
✔ Medallion architecture implementation (Bronze, Silver, Gold layers)
✔ Use of Parquet & Delta Lake for optimized storage
✔ Real-time and batch ingestion scenarios
✔ BI-ready dataset with Power BI integration
✔ Secure and scalable Azure solution

📈 Example Insights (Power BI)

Taxi demand trends by time of day

Peak pickup & drop-off zones

Revenue analysis (fares, tips, surcharges)

Seasonal patterns in rides

🔮 Future Enhancements

Automate pipeline orchestration using Azure Data Factory triggers

Implement streaming ingestion with Event Hubs / Kafka

Deploy ML models on Databricks for fare prediction

🏅 Skills & Learning Outcomes

Data Engineering on Azure

PySpark transformations on large datasets

Delta Lake for reliability in data lakes

Building ETL pipelines with orchestration

End-to-end BI reporting with Power BI

📜 References

Azure Data Factory Documentation

Azure Databricks & Delta Lake Documentation

NYC Taxi Data Portal
