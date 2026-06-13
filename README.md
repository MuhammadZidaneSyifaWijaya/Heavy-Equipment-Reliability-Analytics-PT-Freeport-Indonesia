# ⛰️ Enterprise Data Architecture & BI Case Study — PT Freeport Indonesia

> 🔒 **Confidentiality Notice:** Due to strict Non-Disclosure Agreements (NDA) and enterprise data security protocols at PT Freeport Indonesia, the actual dashboard visuals, source code, and proprietary datasets cannot be published. This repository serves as a high-level technical overview of the data architecture, methodologies, and business impact implemented during the project.

## 📌 Project Overview
Developed an end-to-end Business Intelligence solution to monitor and analyze heavy equipment maintenance logs and spare parts records. The objective was to provide shared, real-time visibility into failure frequency and repair cycle performance across the fleet, enabling actionable Root Cause Analysis (RCA) for operations stakeholders.

## 🏗️ Data Architecture & Pipeline
The project followed a structured data lifecycle, from raw extraction to executive visualization:

1. **🗄️ Data Source & Ingestion:** 
   Queried enterprise SQL databases using complex joins, subqueries, and aggregations to extract raw transactional data (heavy equipment maintenance logs and spare parts records) into multiple Excel files.
2. **⚙️ Data Cleansing & ETL Process:** 
   Performed data transformation, handled missing values, and standardized formats to consolidate records into a clean, analysis-ready dataset that underpinned all subsequent RCA work.
3. **🗃️ Data Modeling:** 
   Architected a relational data model (optimized via Star Schema) to establish clear relationships between fact and dimension tables, ensuring efficient query performance.
4. **📊 Power BI Dashboarding:** 
   Built Power BI dashboards, driven by DAX measures, surfacing Mean Time Between Failures (MTBF) and Mean Time to Repair (MTTR) trends across up to 500 heavy equipment units (internal assets and partner vendor rentals). This provided 6 maintenance teams with a shared real-time view of equipment health and repair scheduling.
5. **🎯 Business Impact & Process Optimization:** 
   Identified process gaps and operational bottlenecks through Root Cause Analysis (RCA) across the monitored fleet. Provided actionable insights to 2 operations stakeholders that were adopted into the revised maintenance schedule, successfully securing a **25% improvement in MTBF**.

## 🛠️ Tech Stack Used
* **Business Intelligence:** Power BI (DAX, Power Query)
* **Data Processing & Storage:** SQL Server, Microsoft Excel
* **Methodologies:** ETL Pipelines, Dimensional Data Modeling (Star Schema), Root Cause Analysis (RCA)
