# 🎵 Music Streaming Data Engineering Project – Azure

## 📌 Project Overview
This project implements an **end-to-end Azure Data Engineering solution** for a Music Streaming platform.  
It demonstrates **real-world data engineering practices** such as **incremental ingestion, backfilling, metadata-driven pipelines, and Delta Live Tables (DLT)**.

The solution is designed to be **scalable, reliable, and analytics-ready**.

---

## 📸 Azure Data Factory Pipeline
The project uses **parameterized Azure Data Factory pipelines** to ingest data from the source system to Azure Data Lake.

**Pipeline Highlights:**
- Incremental data load using watermark logic  
- Backfilling support through pipeline parameters  
- Reusable, metadata-driven design
  
---

## 🧱 Data Processing
- **Bronze Layer** – Raw data ingestion with incremental load and CDC  
- **Silver Layer** – Cleaned and enriched data using Delta Live Tables  
- **Gold Layer** – STAR schema with fact and dimension tables  

---

## ⚙️ Key Features
- Incremental and backfill data ingestion  
