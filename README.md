
# 📦 DataCo Supply Chain & Sales Analysis  
**End-to-End Fabric Project**

## 🧾 Project Overview
This project presents an **end-to-end data analytics pipeline** for analyzing **Supply Chain and Sales data** of **DataCo Global**.  
The solution is built using **Microsoft Fabric**, starting from raw data ingestion up to **data warehousing and Power BI reporting**.

The project covers the full data lifecycle:
- Data ingestion  
- Data modeling (Semantic Layer)  
- Data transformation (ODS, STG)  
- Data Warehousing (DWH)  
- Business Intelligence & visualization  

---

## 👤 Prepared By
- **Name:** Anas El-Alfy  
- **Date:** 26 / 01 / 2026  

---

## 📂 Dataset Description

### 🔹 Source
The analysis is based on the **DataCo Global Supply Chain Dataset**, which represents real business activities across the supply chain.

### 🔹 Business Domains Covered
- Provisioning  
- Production  
- Sales  
- Commercial Distribution  

### 🔹 Data Characteristics
- **Data Type:** Structured Data  
- **Main Dataset:** `DataCoSupplyChainDataset.csv`  
- **Metadata File:** `DescriptionDataCoSupplyChain.csv`  

### 🔹 Product Categories
- Clothing  
- Sports  
- Electronic Supplies  

---

## 🧠 Architecture Overview

The project follows a **Medallion Architecture** implemented in **Microsoft Fabric**:

```
Bronze Layer  →  Silver Layer  →  Gold Layer
(Raw Data)      (Cleaned)        (DWH & BI)
```

---

## 🧩 Semantic Model
- Star Schema design  
- Optimized for analytical queries  
- Fully integrated with Power BI  

---

## 🗄️ Data Layers

### 1️⃣ ODS (Operational Data Store)
- Initial structured storage  
- Minimal transformations  
- Source for staging layer  

### 2️⃣ STG (Staging Layer)
Transformations applied:
- Data type corrections  
- NULL handling  
- Column renaming  
- Data cleansing  

### 3️⃣ DWH (Gold Layer)
- SQL-based Data Warehouse  
- Fact & Dimension tables  
- Single source of truth  

---

## 🔄 Data Pipeline

1. Copy Data → **Bronze Layer**  
2. Dataflows → **Silver Layer**  
3. SQL DWH → **Gold Layer**  

---

## 📊 Power BI Overview
- Interactive dashboards  
- Sales & supply chain KPIs  
- Category and distribution insights  

---

## 🛠️ Tools & Technologies
- Microsoft Fabric  
- SQL  
- Power BI  
- Dataflows  

---

## 🎯 Key Outcomes
- End-to-end analytics solution  
- Scalable data architecture  
- Business-ready insights  

---

📌 *This project follows best practices in Data Engineering and Business Intelligence.*
