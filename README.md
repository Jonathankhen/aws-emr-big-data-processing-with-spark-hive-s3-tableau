# Scalable Big Data Pipeline: AWS EMR, Spark, Hive, S3, Tableau

This project showcases a robust ETL pipeline built to handle large-scale sales data using powerful tools like AWS EMR, Apache Spark, Hive, and Tableau. The goal is to transform raw data from AWS S3, process it on an EMR cluster, and visualize the final results in Tableau.

## Main Features

- **Data Source**: Raw sales data is hosted in an S3 bucket.
- **Processing Engine**: Apache Spark, running on AWS EMR, is responsible for processing and transforming the data.
- **Data Storage**: The processed data is stored in Hive tables within the EMR cluster for efficient querying.
- **Insights & Visualization**: Tableau is used to connect to Hive, generating real-time visual reports and dashboards.

## Workflow Breakdown

1. **Sales Data Extraction**: The raw sales data is fetched from an S3 bucket where external vendors upload it periodically.
2. **Transformation & Processing**: Apache Spark handles data transformation, such as cleaning, formatting, and enrichment on AWS EMR. Hive is used to manage and query the data schema.
3. **Loading Processed Data**: Once Spark processes the data, it is loaded into Hive tables for future querying or reporting.
4. **Data Visualization**: Tableau reads from Hive tables to generate visual dashboards, enabling quick insights into sales trends and other business metrics.

## Tools & Technologies

- **AWS S3**: Stores raw input data.
- **AWS EMR**: Provides a scalable environment for running Spark and Hive to process large datasets.
- **Apache Hive**: Handles schema management and enables querying of processed data.
- **Apache Spark**: Processes and transforms the data with speed and efficiency.
- **Tableau**: Visualizes the final output, providing business insights in the form of dashboards.

## Architecture Diagram

![image](https://github.com/user-attachments/assets/5fc89c38-e418-4bce-8704-3cb7b4050fd1)

This diagram outlines the data flow, from extraction in S3 to final visualization in Tableau, detailing the entire processing journey.

## Summary

This project demonstrates how to use AWS and Apache technologies together to build a seamless, cost-efficient ETL pipeline. With Spark for large-scale data transformation and Hive for efficient querying, coupled with Tableau for powerful visualizations, this project provides a scalable solution for handling big data in the cloud.
