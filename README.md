# Data-Quality-Governance-Framework

## 📌 Project Overview
DataTrust360 is an **end-to-end data quality and governance** solution designed to ensure accurate, reliable, and secure data processing. The project integrates **Azure, Informatica, Snowflake, and Power BI** to enable data extraction, transformation, validation, and reporting with best practices in data governance and compliance.

## 🏗️ Architecture Diagram
![architecture](https://github.com/vaibhavgaur20/Data-Quality-Governance-Framework/blob/main/Architecture.png)

## 🎯 Key Features
✅ **Data Quality Checks**: Ensure **null checks, duplicate handling, schema validation, and data accuracy** using **PySpark & SQL**  
✅ **Data Governance & Security**: Implement **access control, lineage tracking, and compliance** with **Azure Purview**  
✅ **ETL & Orchestration**: Automate pipelines using **Azure Data Factory & Informatica**  
✅ **Data Warehouse**: Store & transform data efficiently in **Snowflake**  
✅ **Monitoring & Reporting**: Visualize **data quality & governance metrics** in **Power BI & Grafana**  
✅ **Automation**: Python scripts for **data validation, governance audits, and pipeline health checks**  

## 🚀 Tech Stack
- **Cloud Platform**: Azure (ADF, Databricks, Storage Account, Synapse Analytics, Purview)
- **ETL Tool**: Informatica (Mappings, Workflows, Transformations)
- **Data Warehouse**: Snowflake (Schema design, Queries, Stored Procedures)
- **Big Data Processing**: Databricks (PySpark-based transformations)
- **Scripting & Automation**: Python (Data validation, Governance Audits, Monitoring Scripts)
- **Data Visualization**: Power BI (Dashboards, Reports)

## 📂 Folder Structure
```
DataTrust360/
│── docs/                          # Documentation
│   ├── architecture-diagram.png   # High-level architecture diagram
│   ├── data-governance-plan.md    # Data governance framework
│   ├── data-quality-checklist.md  # Data quality rules and metrics
│   ├── README.md                  # Project overview
│
│── src/                           # Source code
│   ├── azure/                     # Azure services configuration
│   ├── informatica/               # Informatica ETL workflows
│   ├── snowflake/                 # Snowflake DWH scripts
│   ├── powerbi/                   # Power BI dashboards & reports
│   ├── python-scripts/            # Python scripts for automation & validation
│
│── config/                        # Configuration files
│── tests/                         # Testing & validation
│── monitoring/                    # Data observability & logging
│── .gitignore                     # Ignore sensitive files
│── README.md                      # Project description & setup guide
│── LICENSE                        # License information
```

## 🛠️ Setup & Deployment
### **1️⃣ Prerequisites**
- Azure Subscription with access to ADF, Databricks, Synapse, and Purview
- Snowflake Account
- Informatica PowerCenter installed (or cloud-based version)
- Power BI Desktop for visualization
- Python 3.x environment

### **2️⃣ Installation Steps**
#### **Azure Setup**
1. Create an **Azure Data Factory (ADF)** instance.
2. Set up **Azure Data Lake Storage (ADLS)** to store raw data.
3. Deploy **Azure Databricks** for big data transformations.
4. Configure **Azure Synapse Analytics** for warehouse processing.
5. Enable **Azure Purview** for data governance and lineage tracking.

#### **Snowflake Setup**
1. Create **schemas and tables** using `schema/snowflake_schema.sql`.
2. Load sample data into Snowflake.
3. Configure **role-based access control (RBAC)**.

#### **Informatica Setup**
1. Import mappings and workflows from `src/informatica/`.
2. Set up connections to **Azure & Snowflake**.
3. Configure job schedules.

#### **Python & Power BI**
1. Install required Python packages:
   ```sh
   pip install pandas pyspark snowflake-connector-python azure-storage-blob
   ```
2. Open Power BI and connect to **Snowflake & Azure Synapse Analytics**.
3. Import datasets and build dashboards using `src/powerbi/`.

## 📊 Data Governance & Quality Metrics
### ✅ **Data Quality Checks**
- **Completeness**: Ensure no missing values in critical columns.
- **Uniqueness**: Remove duplicates before loading data.
- **Consistency**: Check schema consistency across data sources.
- **Validity**: Validate against predefined business rules.
- **Timeliness**: Ensure data freshness using time-based monitoring.

### 🔐 **Data Governance Features**
- **Data Lineage Tracking** using **Azure Purview**.
- **Access Controls & Permissions** in **Snowflake & Azure**.
- **Audit Logs & Monitoring** for data pipeline tracking.

## 🚦 Monitoring & Alerts
- **Power BI dashboards** to visualize data quality trends.
- **Azure Monitor & Logging** for pipeline failures.
- **Email & Slack Alerts** for governance breaches.

## 📅 Roadmap
✔️ **Phase 1**: Set up ETL pipeline & data governance framework  
✔️ **Phase 2**: Implement automated quality checks  
✔️ **Phase 3**: Enhance monitoring & reporting with Power BI  
✔️ **Phase 4**: Optimize pipeline performance & scale for large datasets  




