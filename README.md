# Stock Market Kafka Real Time Data Engineering Project

Special thanks to [Darshil Parmar](https://www.youtube.com/@DarshilParmar) for providing valuable insights and guidance, making it possible to complete this project.

## Introduction 
This repository contains an end-to-end data engineering project that focuses on collecting, processing, and analyzing stock market data. The project utilizes Python as the primary programming language and various Amazon Web Services (AWS) services, such as S3, Athena, Glue Crawler, Glue Catalog, EC2, and Apache Kafka.

## Architecture 
<img src="https://github.com/PEPE0211/Aws-Stock-Market-Real-Time-Data-Analysis/blob/main/image/Architecture.jpg">

## Project Overview

The goal of this project is to demonstrate a complete data engineering pipeline for stock market data analysis. The pipeline consists of the following steps:

1. **Data Collection**: We collect stock market data from various sources. For this project, we have used Python to fetch the data.

2. **Data Ingestion**: The collected data is pushed onto an Apache Kafka cluster for efficient and real-time data streaming.

3. **Data Storage**: We store the data in an AWS S3 (Simple Storage Service) bucket for long-term storage and durability.

4. **Data Cataloging**: To make the data easily accessible and queryable, we use AWS Glue Crawler and Glue Catalog to catalog the data, creating a structured metadata repository.

5. **Data Analysis**: We analyze the cataloged data using Amazon Athena, a serverless query service, by running SQL queries to gain insights into the stock market trends and performance.

## Technology Used
- Programming Language - Python
- Amazon Web Service (AWS)
1. S3 (Simple Storage Service)
2. Athena
3. Glue Crawler
4. Glue Catalog
5. EC2
- Apache Kafka



