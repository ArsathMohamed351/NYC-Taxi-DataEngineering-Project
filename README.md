# 🚖 NYC-Taxi-DataEngineering-Project

This project demonstrates an **end-to-end Data Engineering pipeline** built on the **Azure ecosystem** using NYC Taxi data.  
It covers data ingestion, transformation, storage, and visualization, showcasing modern data engineering practices with **Azure Data Factory, Azure Databricks, Delta Lake, and Power BI**.

---

## 📌 Project Architecture

<img width="1366" height="768" alt="OverView" src="https://github.com/user-attachments/assets/3ab855e2-25f4-4655-9269-3c4f4d91dadb" />


The pipeline follows these stages:

1. **Data Source**  
   - NYC Taxi dataset (publicly available trip data).  
   - Raw data ingested in **Parquet** format.

2. **Data Ingestion (Azure Data Factory)**  
   - Orchestrates ingestion of raw taxi data from source into **Azure Data Lake Storage (ADLS)**.  
   - Ensures secure and automated data movement.

3. **Data Storage (Raw Zone)**  
   - Raw data stored in **Parquet files** for cost-effective and schema-preserving storage.  

4. **Data Transformation (Azure Databricks)**  
   - Cleans, filters, and enriches raw data.  
   - Converts raw Parquet into **Delta Lake format** for optimized querying and ACID transactions.  

5. **Serving Layer (Delta Lake)**  
   - Transformed data stored in **Delta tables** for analytics and reporting.  
   - Supports incremental loads and time-travel queries.  

6. **Data Visualization (Power BI)**  
   - Interactive dashboards built on top of the transformed dataset.  
   - Provides insights into taxi trip volumes, revenue, and performance metrics.  

7. **Security & Governance**  
   - Azure Key Vault for secrets and credentials.  
   - Role-based access control for secure data handling.  

---

## 🛠️ Tech Stack

| Component              | Technology Used |
|------------------------|-----------------|
| Data Ingestion         | Azure Data Factory |
| Data Storage (Raw)     | Azure Data Lake Storage (Parquet) |
| Data Transformation    | Azure Databricks (PySpark) |
| Serving Layer          | Delta Lake |
| Visualization          | Power BI |
| Security               | Azure Key Vault |

---

## 📊 Power BI Dashboard

The Power BI dashboard provides:  
- Trip volume trends over time  
- Revenue analysis by vendor and payment type  
- Peak hours and demand hotspots  
- Performance KPIs for business insights  


---

## 🚀 How to Run the Project

1. **Clone the Repository**
 [  ```bash
   git clone https://github.com/your-username/NYC-Taxi-DataEngineering-Project.git
   cd NYC-Taxi-DataEngineering-Project](https://github.com/ArsathMohamed351/NYC-Taxi-DataEngineering-Project)
