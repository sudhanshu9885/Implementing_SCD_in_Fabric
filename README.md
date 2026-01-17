# Implementing_SCD_in_Fabric

# End-to-End Automated Data Pipeline on Microsoft Fabric  
**Seamless On-Premises to Cloud Data Integration with Fully Automated Analytics Pipelines**  

**Build a scalable, automated pipeline to deliver analytics-ready datasets from on-premises sources to Microsoft Fabric.**  

---

## Tools & Technologies
- **Data Platform:** Microsoft Fabric, Fabric Lakehouse, Fabric Warehouse  
- **Processing & Transformation:** Dataflow Gen1, Fabric Notebooks  
- **Connectivity & Automation:** On-Premises Data Gateway, Triggers, Email Alerts  
- **Data Format & Storage:** Delta Lake  

---

## Key Features

- **Data Ingestion (Bronze Layer):**  
  Designed a secure ingestion pipeline to load structured raw data from on-premises systems into Fabric Lakehouse using the On-Premises Data Gateway. Preserved raw data for traceability and ensured reliable cloud connectivity.

- **Data Cleaning & Transformation (Silver Layer):**  
  Used Dataflow Gen1 for cleansing and transformation, including joins, duplicate removal, data standardization, and formatting. Loaded validated datasets into Fabric Warehouse for scalable analytics.

- **ETL Processing & Data Consistency (Gold Layer):**  
  Implemented Slowly Changing Dimension (SCD) Type-1 logic using Fabric Notebooks, ensuring dimension tables reflect the most current records. Processed curated datasets into multiple Gold-layer tables optimized for reporting and analytics.

- **Automation, Scheduling & Monitoring:**  
  Configured automated pipeline scheduling with Fabric triggers for reliable data refreshes. Added failure-handling mechanisms with email alerts to notify stakeholders of execution issues.

- **Data Pipeline Architecture:**  
  Built a unified, end-to-end Fabric pipeline following the Bronze–Silver–Gold layered approach, streamlining ingestion, transformation, storage, and monitoring within a single platform.

---

## Business Impact
Delivered a fully automated, scalable, and monitored data pipeline, providing analytics-ready datasets from on-premises sources. Enabled faster insights, improved data reliability, and reduced manual intervention for business and analytics teams.


