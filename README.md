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

## Final Dashboard:
![image](https://github.com/user-attachments/assets/5bd6e3ee-3d89-40b9-8619-cd75dd0666b6)

### Dashboard visualizations: 
![image](https://github.com/user-attachments/assets/ba3aa143-c82f-4111-a704-b302a01fbf4b)
![image](https://github.com/user-attachments/assets/6453ebf0-cdcf-4e49-86cb-3eb4059bb1e5)
![image](https://github.com/user-attachments/assets/0548b219-97e2-45f7-831c-5ab753cfc173)
![image](https://github.com/user-attachments/assets/c8b22838-df03-4485-921b-3f2ea9c12038)
![image](https://github.com/user-attachments/assets/8a2ef17d-adc9-4cfb-aeb9-baccbf45b0fb)

## Summary

This project demonstrates how to use AWS and Apache technologies together to build a seamless, cost-efficient ETL pipeline. With Spark for large-scale data transformation and Hive for efficient querying, coupled with Tableau for powerful visualizations, this project provides a scalable solution for handling big data in the cloud.

## Process:

#### Creating EMR Hadoop Framework on AWS:
![image](https://github.com/user-attachments/assets/4c0493ba-10ae-459a-8e88-416776b6d5a5)
![image](https://github.com/user-attachments/assets/6c1346a2-a525-42a8-80ea-c52362f83e41)

#### Setting up cluster:
![image](https://github.com/user-attachments/assets/ac6d704e-8441-429d-936b-3db0d0e7fac8)
![image](https://github.com/user-attachments/assets/6bdee0b0-6e6b-48d9-b95c-7892097a14de)

#### Creating inbound security group rules:
![image](https://github.com/user-attachments/assets/fef1791d-f32b-4fb6-8f20-f82688a6066c)

#### Signing into the EMR cluster for executing hive commands: 
![image](https://github.com/user-attachments/assets/43a1cd32-45c9-422f-b2da-1b61459eb154)

#### Creating S3 Bucket: 
![image](https://github.com/user-attachments/assets/5d7d230e-1560-44e8-919a-a6a5b2bea4a6)

#### Uploading data into S3 bucket:
![image](https://github.com/user-attachments/assets/31e416e6-c731-4cf9-a032-7829e02a51cc)
![image](https://github.com/user-attachments/assets/539c5407-031d-4137-86f4-4001d4ba485c)

#### Copying data path
![image](https://github.com/user-attachments/assets/fec8ae48-95b1-482d-a840-b5d975dc5c5d)

#### Creating sales table based on data in hive:
![image](https://github.com/user-attachments/assets/928601d9-6de5-4bbd-9f86-79ac29722a84)

#### Applying transformations:
![image](https://github.com/user-attachments/assets/3c3be06c-10b2-4345-8568-7964400c3ed0)

#### Tables:
![image](https://github.com/user-attachments/assets/28746947-b6e8-4725-8fa4-c4cbff176e5d)

#### Final transformations: 
![image](https://github.com/user-attachments/assets/b964ea55-68dc-41ae-950c-57463d7c61b5)

#### Creating yarn clusters of the data:
![image](https://github.com/user-attachments/assets/1a1c2b5b-571d-420a-b38a-c0d7f9a50e1c)

#### Snippet of the data:
![image](https://github.com/user-attachments/assets/a5061b2b-51f1-4bd8-adbb-054a7a47713d)

#### Connecting data to Tableau through their EMR Connector:
![image](https://github.com/user-attachments/assets/55395b90-ffec-4f84-a0e6-b2d3a3e28509)
![image](https://github.com/user-attachments/assets/4e498b3a-65c2-4759-ab40-324fca972a27)
![image](https://github.com/user-attachments/assets/61b0c940-6185-4033-9675-782007afb4b6)

#### Data table set up:
![image](https://github.com/user-attachments/assets/8a16d348-ca0c-4460-8d52-ba5077ff3847)

#### Starting the visualization work: 
![image](https://github.com/user-attachments/assets/2be1202d-049a-433a-b366-89f57d9c2e8b)

## Tableau Dashboard:
![image](https://github.com/user-attachments/assets/5bd6e3ee-3d89-40b9-8619-cd75dd0666b6)
