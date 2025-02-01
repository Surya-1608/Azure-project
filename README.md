# Azure-project

![image](https://github.com/user-attachments/assets/aea9d87a-f97b-4513-9454-52e08909ac23)


## Project Overview

This project demonstrates a complete Azure-based data pipeline for analyzing the Tokyo Olympics dataset obtained from Kaggle. The pipeline involves Azure Data Factory, Data Lake Storage Gen2, Databricks, and Synapse Analytics, enabling seamless data ingestion, transformation, and analysis. The final transformed data is ready for visualization in Power BI or Tableau.

## Technologies Used

**Azure Data Factory** – Orchestrates data movement and transformation

**Azure Data Lake Storage Gen2** – Stores raw and transformed data

**Azure Databricks** – Performs data processing and transformations

**Azure Synapse Analytics** – Analyzes data using SQL and big data tools

## Project Workflow

1️⃣ **Data Acquisition**

The Tokyo Olympics dataset was sourced from Kaggle and uploaded to GitHub.

2️⃣ **Data Ingestion** (Azure Data Factory)

Data was ingested into Azure Data Factory (ADF).

![image](https://github.com/user-attachments/assets/28f5d313-3fbc-434e-890f-21ae8ad5daac)
The dataset was stored in Azure Data Lake Storage Gen2 (Raw Folder).

3️⃣** Data Processing** (Azure Databricks)

Data was imported from Azure Data Lake Storage Gen2 into Databricks.

Initial transformations and cleaning were performed using Pyspark .

The processed data was saved back to Azure Data Lake Storage Gen2 (Processed Folder).

4️⃣** Data Processing** in Azure Synapse Analytics

The same dataset was also loaded into Azure Synapse Analytics.

Data ingestion, transformation, and querying were performed using SQL.

The final transformed dataset was stored for further analysis.

5️⃣ **Data Visualization**

The final processed data can be connected to Power BI or Tableau for insights and dashboard creation.
