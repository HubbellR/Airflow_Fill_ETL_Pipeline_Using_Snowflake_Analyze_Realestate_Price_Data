# Airflow_Fill_ETL_Pipeline_Using_Snowflake_Analyze_Realestate_Price_Data
This project is a full ETL Pipeline which goes from public realestate pricing data (from RedFin) to a fully analyzed product using Apache Airflow and Snowflake within an AWS server. For further details, please see readme file.

The following is an outline of the steps taken in this project.

1. We first need to establish an AWS EC2 server to host the processing for this data. We select a server with at leadt 4 GB of RAM since we are dealing with a large amount of data, which might have to sit in memory.

2.   In the EC2 server, we start a virtual environment. We do this because [...]
      We set up and activate the virtual environent using "python3 -m venv venv_name"
     , source venv_name/bin/activate".

4.  install the following dependencies on the EC2 server (using pip): pandas, boto3, awscli, apache airflow

5.  Create an access key to allow the user to EC2 resources. At a minimum, make sure that you download the access key and secret access key as a csv file and save it somewhere.

6.   Configure aws settings ("aws configure"), and make sure that airflow is initialized using "airlfow standalone"

7.   
8.  e
9.  e
10.  e
11.  e
12.  e
13.  e
14.  e
15.  
