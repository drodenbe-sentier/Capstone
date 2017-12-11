# Capstone
Capstone project - MIDS program

## Data 



Data Dictionaries and related documents can be found in: 

https://ia800608.us.archive.org/16/items/opm-federal-employment-data/docs/FedScope%20-%20DataDefinitions.pdf 
https://www.opm.gov/policy-data-oversight/data-analysis-documentation/data-policy-guidance/reporting-guidance/part-a-human-resources.pdf



## ETL
Code related to the ETL process can be found in folder Capstone/ETL/

Steps followed:
1. Downloaded files from the Federal workforce website.
2. Loaded files into google S3 bucket.
3. Create database w210 - FedWork in BigQuery 
3. Transform data and load it into BigQuery using queries through the BigQuery UI
4. Create final dataset status_dynamic_v3

## Modeling
Code related to the feature selection and modeling can be found in Capstone/Modeling/

## Visualization
Folder Capstone/Visualization/ contains the following:
1. Code to prepare data for visualization
2. Tableau workbooks 
