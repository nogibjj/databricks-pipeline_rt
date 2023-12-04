Databricks ETL Pipeline Project
Introduction
This repository hosts the ETL (Extract, Transform, Load) pipeline project implemented in Databricks using PySpark, Python, and Delta Tables, along with SQL for data processing. The project demonstrates end-to-end ETL operations within the Databricks Workspace.

Originally based on the Week-11 Mini-Project, this repository has been adapted to fit specific ETL requirements.

Project Overview
The project showcases ETL operations in Databricks using sample automotive data sourced from GitHub. The notebooks responsible for the data processing are stored in the 'Notebooks' folder in this repository.

A Databricks workflow is configured to execute these notebooks sequentially, representing a complete ETL workflow. GitHub Actions are set up to handle CI/CD processes upon repository updates.

Schema
<img width="748" alt="Screenshot 2023-11-28 at 11 57 09 PM" src="https://github.com/nogibjj/databricks-pipeline_rt/assets/143838819/91ca111f-e78f-4093-a3a9-e6bb2fdb3fe3">

Getting Started
The primary data operations occur on the Databricks platform using the Automotive dataset from GitHub.

Notebooks:
Extract: Loads raw data from the source and saves it as a Delta Table. Extract Notebook
Transform_Load: Processes data from the raw-data Delta Table and saves it to a processed Delta Table. Transform_Load Notebook
Visualize: Generates visualizations from the processed table and saves the outputs to the repository. Visualize Notebook
Workflows
This project includes two main workflows:

ETL Workflow in Databricks: Executes extraction, transformation/loading, and visualization steps.
CI/CD Workflow in GitHub: Manages installation, testing, formatting, and linting of the project files.
ETL Workflow
The Databricks workflow, named Ind_Proj_3, automates the following tasks:

Extraction
Transformation and Loading
Visualization
Successful Execution of Databricks Workflow:
Data Workflow (Add your screenshot here)

Note: The workflow is set to trigger automatically monthly to optimize costs.
<img width="1329" alt="Screenshot 2023-11-30 at 4 00 13 PM" src="https://github.com/nogibjj/databricks-pipeline_rt/assets/143838819/22c13101-82b2-44c2-8ecf-1c18f2681325">

CI/CD Workflow
GitHub Actions automate package installation, Python script testing (pytest), code formatting (black), and linting (ruff).

<img width="1263" alt="Screenshot 2023-11-30 at 3 59 38 PM" src="https://github.com/nogibjj/databricks-pipeline_rt/assets/143838819/1f144ef2-8e37-4e14-b479-e6ac165d76df">


Error Handling
Each code segment and notebook includes robust error handling and data validation. Errors are clearly logged, and cases with empty dataframes are flagged.

Repository Contents
README.md - Project information and usage instructions.
requirements.txt - Required libraries and packages for the project.
.github/workflows - Contains the cicd.yml for GitHub Actions.
Makefile - Commands for GitHub Actions and virtual environment setup.
.devcontainer - Docker and development container configuration files.
Notebooks - Contains ETL notebooks for version control and CI/CD.
plot.png - Output visualization generated by the project.
resources - Additional files for README documentation.
Feel free to modify the content to better fit your project's specifics and add the relevant links or screenshots where placeholders are mentioned.

