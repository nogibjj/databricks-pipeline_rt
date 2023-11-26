# Databricks Data Pipeline Project

## Overview
This project involves the creation and execution of a data pipeline within Azure Databricks, demonstrating the end-to-end process from data ingestion to analysis.

## Pipeline Stages
- **Data Preview**: A preliminary notebook to inspect initial datasets.
- **Data Ingestion**: A notebook to ingest and store data into DBFS, establishing the `raw_song_data` database.
- **Data Analysis**: SQL-based analysis performed on `prepared_song_data` derived from the ingested raw data.
- **Data Querying**: Executing queries on the structured dataset to extract insights.

## Automation
A scheduled workflow is established to execute the notebooks daily at 3:30 PM UTC, ensuring the pipeline's operation is consistent and automated.

## Insights
Through this pipeline, we interact with data at various stages, apply transformations, and utilize SQL for in-depth data querying, all orchestrated seamlessly within the Databricks environment.

