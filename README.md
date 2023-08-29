## **Data Engineering Project - Olympic Data Pipeline**
# **Overview**
This repository contains the code and documentation for a data engineering project that processes and analyzes Olympic data from Kaggle. The project involves several Azure services, including Azure Data Factory, Data Lake Gen 2, Azure Databricks, and Azure Synapse Analytics, to create a data pipeline for storing, transforming, and analyzing the data. The results are then visualized using Microsoft Power BI.

# **Project Structure**
**data_factory:** Contains the Azure Data Factory configuration files and data pipeline definitions.
**databricks:** Contains PySpark code and notebooks used for data transformation.
**synapse_analytics**: Includes SQL scripts and notebooks for data analysis in Azure Synapse Analytics.
**power_bi:** Contains Power BI reports and datasets for data visualization.

# Project Steps
**Data Ingestion**: Data from Kaggle is stored in a storage container in a specific Azure Storage account.

**Data Factory**: An Azure Data Factory is deployed to create data pipelines. These pipelines retrieve data from GitHub, perform transformations, and store the results in Data Lake Gen 2.

**Azure Databricks**: Azure Databricks is used to run PySpark code for data transformation. The data storage is mounted to the Data Factory for seamless data access.

**Data Transformation:** PySpark scripts in Databricks transform the data, and the results are returned to the storage container.

**Azure Synapse Analytics**: Azure Synapse Analytics is deployed for SQL data analysis. Data is loaded into Synapse Analytics for complex analytical queries.

**Data Visualization:** The data is loaded into Microsoft Power BI for creating interactive dashboards and reports.

# Usage

Run the data pipelines using Azure Data Factory to retrieve, transform, and store the data.

Execute the PySpark scripts in Azure Databricks for further data transformation.

Utilize Azure Synapse Analytics for data analysis using SQL queries.

Load the data into Microsoft Power BI to create visualizations and reports and add tables and different measures.

# Dependencies
Azure Data Factory
Azure Data Lake Gen 2
Azure Databricks
Azure Synapse Analytics
Microsoft Power BI

# Credits
Olympic data source: Kaggle

