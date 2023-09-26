# Spotify-end-to-end_data-pipeline

### Introduction
In this project , I have build and ETL pipeline using spotify API on AWS. The pipeline will retreive data from spotify API, transfrom into desired format using AWS lambda and load into AWS data store.

### Architecture
![Architecture Diagram](https://github.com/Kapsime/Spotify-end-to-end_data-pipeline/blob/main/Pipeline_Architecture_AWS.png)

### Api Used
**Spotipy** : [Spotipy](https://spotipy.readthedocs.io/en/2.22.1/) is a lightweight Python library for the Spotify Web API. With Spotipy we get full access to all of the music data provided by the Spotify platform.

### AWS Services Used
1. **S3** : Amazon Simple Storage Service (Amazon S3) is an highly scalable object storage that can store & retrieve any amount of data from anywhere on the web.

2. **AWS Lambda** :  Serverless computing service that lets you run your code without managing servers.

3. **Awazon Cloud Watch** : Monitoring Service for AWS resources & other application run on them , can be used to collect and monitor log files & set alarms.

4. **Data Crwaler** : A crawler can crawl multiple data stores in a single run. Upon completion, the crawler creates or updates one or more tables in your Data Catalog.

5. **AWS Glue Data Catalog** : The AWS Glue Data Catalog contains references to data that is used as sources and targets of your extract, transform, and load (ETL) jobs in AWS Glue.

6. **Amazon Athena** : Amazon Athena is an interactive query service that makes it easy to analyze data directly in Amazon Simple Storage Service (Amazon S3) using standard SQL.


### Install Python Packages
```
pip install pandas
pip install numpy
pip install spotipy
```


