# 🍽️ Restaurant Analytics Platform (Azure + Databricks)

## 🚀 Overview
End-to-end data platform that ingests real-time and batch restaurant data,
processes it using Medallion Architecture, and generates insights using AI and BI dashboards.

## 🧩 Architecture
[ADD DIAGRAM IMAGE HERE]

Event Hub (Streaming)
        ↓
LakeFlow CDC (Batch - Azure SQL)
        ↓
Bronze → Silver → Gold (Delta Lake)
        ↓
Mosaic AI (Sentiment Analysis)
        ↓
Dashboards
