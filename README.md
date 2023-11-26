# Databricks Data Pipeline Project

## Overview
This project involves the creation and execution of a data pipeline within Azure Databricks, demonstrating the end-to-end process from data ingestion to analysis.

## Pipeline Stages
- **Data Preview**: A preliminary notebook to inspect initial datasets.
- **Data Ingestion**: A notebook to ingest and store data into DBFS, establishing the `raw_song_data` database.
- **Data Analysis**: SQL-based analysis performed on `prepared_song_data` derived from the ingested raw data.
- **Data Querying**: Executing queries on the structured dataset to extract insights.
<img width="1270" alt="Screenshot 2023-11-26 at 12 55 52 AM" src="https://github.com/nogibjj/databricks-pipeline_rt/assets/143838819/bedfdbc0-e3d0-44ef-acda-6464b31dfff8">
<img width="1257" alt="Screenshot 2023-11-26 at 12 56 16 AM" src="https://github.com/nogibjj/databricks-pipeline_rt/assets/143838819/0586d8f1-dbdd-4449-aa20-cbf449867db8">


## Automation
A scheduled workflow is established to execute the notebooks daily at 3:30 PM UTC, ensuring the pipeline's operation is consistent and automated.

## Insights
Through this pipeline, we interact with data at various stages, apply transformations, and utilize SQL for in-depth data querying, all orchestrated seamlessly within the Databricks environment.
<img width="1251" alt="Screenshot 2023-11-26 at 12 45 29 AM" src="https://github.com/nogibjj/databricks-pipeline_rt/assets/143838819/3c908856-f3da-43d8-b985-559c88e4c393">

