# Individual Project

## Overview
This project demonstrates a robust ETL (Extract, Transform, Load) pipeline using Databricks, Delta Lake, and Spark SQL. The primary goal is to efficiently extract data from a specified source, transform it using Spark SQL, and load it into Delta Lake for storage and further analysis. The project also includes data validation, error handling, and a visualization component to represent the transformed data.

Features
- **ETL Operations**: Utilizes Databricks notebooks for efficient ETL operations.
- **Delta Lake Integration**: Demonstrates the use of Delta Lake for advanced data storage capabilities.
- **Spark SQL Transformations**: Employs Spark SQL for effective data transformations.
- **Data Validation and Error Handling**: Ensures the integrity of the data through systematic checks and robust error handling mechanisms.
- **Visualization**: Provides a clear visual representation of the data post-transformation.
- **Automated Trigger**: Includes an automated mechanism to initiate the ETL pipeline.

### Preparation Steps:
1. Create a Databricks workspace on a cloud platform like Azure.
2. Integrate your GitHub account with the Databricks Workspace.
3. Configure a global initialization script in the Databricks cluster for environment variables.
4. Establish a Databricks cluster that supports PySpark.
5. Clone the project repository into the Databricks workspace.
6. Set up a Databricks job to automate the pipeline execution.

### Pipeline Components:
- Data Source Extraction Script: `mylib/extract.py`
- Data Transformation and Load Script: `mylib/transform_load.py`
- Data Query and Visualization Script: `mylib/query.py`

## Requirements
The project involves developing a data pipeline in Databricks, incorporating at least one data source and one data sink.

## Demo Video
A comprehensive video demonstration of the ETL pipeline is available  [here](). This video walks you through the entire process, showcasing the automated trigger and the key aspects of our pipeline, along with the conclusions and actionable recommendations for the management team.

## Job pipeline
![etl](https://github.com/nogibjj/Mini_Project11_Yabei/assets/143656459/57c258ce-ef7f-4970-9d8c-6ec3aeca6e22)

## visualization
![result](https://github.com/nogibjj/Mini_Project11_Yabei/assets/143656459/ce851b21-99c2-44d3-8e18-5c30175aaee0)

