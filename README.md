# Tokyo-olympics-azure-project
# Azure Data Engineering and Analytics Project on Tokyo Olympics

## Project Description

This project showcases a data engineering and analytics pipeline built on Microsoft Azure. It involves the use of Azure Data Factory (ADF), Azure Data Lake Storage Gen2 (ADLS2), Azure Databricks, and Azure Synapse Analytics to ingest, transform, and analyze data.

The main steps of the project include:

1. **Data Ingestion and Transformation**: Raw data is sourced from a GitHub repository using ADF's Copy Data Tool and stored in the ADLS2, transformed with Azure Databricks, and loaded back into ADLS2.
 
![CopyData-github-ADLS2](https://github.com/NikhilHanumanthaiah/Tokyo-olympics-azure-project/assets/146332720/603d05c9-d248-48e9-b4ba-208616cf94d2)

2. **Data Warehousing**: A lake database is created in Azure Synapse Analytics to create the tables and to query the data
 ![Tokyo-Olympics-lakeDatabase](https://github.com/NikhilHanumanthaiah/Tokyo-olympics-azure-project/assets/146332720/76639e0d-4977-42e5-95b4-cd56a5005e86)

3. **Data Analysis**: Queries are run on the tables in Azure Synapse Analytics to gain insights from the data.

## Prerequisites
- An Azure subscription.
- Azure Data Factory configured with appropriate permissions.
- Access to Azure Data Lake Storage Gen2.
- Azure Databricks workspace.
- Azure Synapse Analytics (formerly SQL Data Warehouse) setup.


I would like to acknowledge the Azure platform and its powerful services that enable efficient data engineering and analytics.

Data Source - Kaggle


