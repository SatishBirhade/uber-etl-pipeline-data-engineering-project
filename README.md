# Uber Data Analytics | Modern Data Engineering GCP Project

## Introduction

The goal of this project is to perform data analytics on Uber data using various tools and technologies, including GCP Storage, Python, Compute Instance, Mage Data Pipeline Tool, BigQuery, and Looker Studio.

## Architecture 
<img src="Architecture.jpg">  

## Technology Used
- Programming Language - Python

Google Cloud Platform
1. Google Storage
2. Compute Instance 
3. BigQuery
4. Looker Studio

Modern Data Pipeine Tool - https://www.mage.ai/

Contibute to this open source project - https://github.com/mage-ai/mage-ai


## Dataset Used
TLC Trip Record Data
Yellow and green taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts. 

Here is the dataset used in the video - https://github.com/SatishBirhade/uber-etl-pipeline-data-engineering-project/blob/5680c7aafa6c8ea15f022df6d18436f2ef3a7a53/Raw%20Data/uber_data.csv

More info about dataset can be found here:
1. Website - https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
2. Data Dictionary - https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf

## Data Model
<img src="https://github.com/SatishBirhade/uber-etl-pipeline-data-engineering-project/blob/5680c7aafa6c8ea15f022df6d18436f2ef3a7a53/Model_Structure/data_model%20structure%20(facts%20and%20dimension%20table).jpeg">

## Project Workflow

### Step 1: Data Preprocessing and Model Building

1. Review the data dictionary.
2. Open Jupyter Notebook to read CSV data.
3. Create a data model with fact and dimension tables.(using lucid.app)
4. Use the `info` function to check data types.
5. Convert date columns to a standard format.
6. Write data transformation code.
7. Merge data into the fact table.

### Step 2: Google Cloud Setup

1. Create a Google Cloud storage bucket.
2. Create a VM instance with the required configuration, including SSH access.
3. Run setup commands from `command.txt`.

### Step 3: GCP Integration

1. Check if the project is running on your external IP address.
2. Write code for data loading, transformation, and exporting.
3. Create a GCP service account, download the JSON key, and configure the `io_config.yaml` file for GCP connectivity.

### Step 4: BigQuery Integration

1. Open BigQuery, create a multi-region dataset, and resolve any errors.
2. Load all cleaned tables into BigQuery.

### Step 5: Visualization and Reporting

1. Apply SQL queries to join tables and create the `table_analysis`.
2. Use Looker to generate reports, connecting to BigQuery and adding the `table_analysis` table.
3. Create visualizations and reports using various charts and controls

### Final Dashboard Link: https://github.com/SatishBirhade/uber-etl-pipeline-data-engineering-project/blob/c8030b4167c082e95d1c9facf9c0976a2a0d7129/Uber_Data_Analytics_Dashboard.pdf

### Conclusion
This project aims to provide insights into Uber data through comprehensive data analytics. For a detailed explanation of each step and further project updates, please refer to the GitHub repository.

### Project Video : https://github.com/SatishBirhade/uber-etl-pipeline-data-engineering-project/blob/299a2e60123f18a171e587d0525d8620d0e3803b/Project_running_video.mp4


