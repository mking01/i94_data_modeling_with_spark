# i94 Data Modeling with Spark
This project constructs a STAR schema database and corresponding modularized pipeline for the job.  It contains a contingency planning discussion for a few scenario changes for the database.  It also includes a data quality check after data is written to the table.

## Overview
This project follows 5 steps:
1. Scope Project and Gather Data
2. Explore and Assess Data
3. Define Model
4. Run ETL to model data
5. Project Writeup

Steps 1-3 reside in the Capstone_Prelim_Analysis.ipynb file.  Steps 4 and 4 reside in the Capstone_Modularized.ipynb file.

## Files
- Capstone_Prelim_Analysis.ipynb: Scopes project, gathers data, explores and assesses data, does validations and quality checks on the raw files
- Capstone_Modularized.ipynb: Transforms code from prelim_analysis.ipynb into a modularized coding pipeline.  Contains data dictionary for final tables.  Discusses project design choices and contingency planning scenarios.
- us_cities_demographics.csv: .csv file containing demographic data for major US Cities
- part-0000-....parquet: .parquet file containing i94 immigration data.  1 of multiple files; only 1 uploaded here for example purposes.
- i94_SAS_Labels_Descriptions.SAS: .SAS file serving as the data dictionary for i94 data
- immigration_data_sample.csv: Alternate version of i94 immgration data
- airport-codes_csv.csv: .csv file containing data on all airports

## To Run:
Load jupyter notebooks and iterate through cells.

## Credits and Acknowledgements
This project was completed in conjunction with Udacity's Data Engineering Nanodegree program.
