📊 **COVID-19 Data Engineering Pipeline**
This project implements an end-to-end data engineering pipeline on Azure to ingest, transform, and visualize COVID-19 data (confirmed cases, deaths, testing rates, ICU admissions, and demographics) for EU and UK. It utilizes Azure Data Factory, Azure SQL, and Power BI to deliver actionable insights and enable downstream analytics and machine learning use cases.

🚀 **Features**
* Automated ingestion of datasets from ECDC and Eurostat
* ETL workflows in Azure Data Factory with data quality validation
* Data storage in Azure Data Lake Storage (ADLS)
* Curated datasets loaded into Azure SQL Database
* Interactive Power BI dashboard for trend visualization
* ML-ready structured data for data scientists


🛠️ **Architecture Overview**

External Sources (ECDC, Eurostat)  ->   Azure Data Factory (Pipelines, Data Flows, Triggers)  ->
  Azure Data Lake Storage (Raw → Processed Zones)  ->  Azure SQL Database (Data Warehouse)  
  ->  Power BI (Dashboard)



📂 **Datasets Used**
* ECDC COVID-19 Cases and Deaths
* ECDC ICU Admissions & Testing Rates
* Eurostat Population by Age Group


💻 **Technologies**
* Azure Data Factory (ADF)
* Azure Data Lake Storage (ADLS Gen2)
* Azure SQL Database
* Power BI
* SQL
* Data Flows, Linked Services, Triggers


📈 **Power BI Dashboard**
The dashboard includes:

* Daily/weekly case trends
* Testing and ICU admission rates
* Country-wise comparisons
* Age group segmentation
