## Incremental Data Loading Pipeline with Azure Databricks and Delta Live Tables

### Introduction

Here, implement incremental or delta load and full load ETL data pipeline by using ADF. This ETL pipeline driven by metadata tables stored on delta lake, and implemented logging, email notification via logic app after every pipeline run.
Create Pyspark and Spark SQL code in Databricks notebook and execute through ETL pipeline.

Data governance is effectively implemented using Unity Catalog, which also manages permissions to ensure secure and organized data access.
User/Group Names are grant permissions to.
       
       Data Engineering Team - all privilege
       Testing team - all read
       Reporting Team - curated table read only


### Architecture

<img width="600" alt="architecture" src="https://github.com/laijupjoy/Incremental-Data-Loading-Pipeline-in-Azure-Databricks-with-Delta-Live-Tables/assets/87544051/56a9cb20-6113-4e1e-80ae-d8a8a02bfbd2">

### ADF Copy Activity Pipeline

![adf_copy_activity](https://github.com/laijupjoy/Incremental-Data-Loading-Pipeline-in-Azure-Databricks-with-Delta-Live-Tables/assets/87544051/a09a22ba-a8b5-487c-ace2-80ca3b5882c0)


![data lineage](https://github.com/user-attachments/assets/624681e1-1830-4603-ab6f-49dc4d433527)

### Technology Used
~~~
1.ADLS Gen2
2.Azure Data Factory
3.Azure Databricks
4.Delta Live Tables
5.Azure Logic Apps
6.Azure Key Vault
7.Azure DevOps
~~~
