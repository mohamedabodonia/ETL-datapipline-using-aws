# Spotify Data Pipeline 
## overview 

This project applied on spotify data .  
In this project, i worked on creating data pipline using aws services (aws glue,s3,aws athena).   
I downloaded data from kaggle website then apply ETL pipline proecss on data. 

## project workflow

**1-Data Acquisition**: Downloaded the Spotify data file from Kaggle.

**2-AWS S3 Setup**: Created two S3 buckets on AWS Console  
* one as the source and the aother as the destination.

**3-Data Processing with AWS Glue**: applying some function on file   
* **ex**: joining coulmns and drop duplicated coulmns.

**4-Data Storage**: Save the processed data in the destination S3 bucket.

**5-Data Cataloging with AWS Glue Crawler**: Used the crawler tool to create schema for the data stored in s3 destination.

**6-Querying data using AWS Athena**: Leveraged AWS Athena to query and analyze the data.

## Technology used 

* **s3 bucket**: used as a data storagae.  
* **aws glue** : used as an ETL pipline tool .
* **aws glue crewler** : used to create schema for the data stored in datawarehouse.
* **aws athena** : to make quries on data using sql language.
*  **quicksight** : to visualize data and build dashboard.

## concolusion
this is a full project to creata a data pipline using aws cloud.  
the project contain all the process of extracting ,transformation and loading .  
