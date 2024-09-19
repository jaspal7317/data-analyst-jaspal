# Data Analytics Platform for the City of Vancouver

## Overview
This project outlines the development and implementation of a Data Analytics Platform (DAP) for the City of Vancouver using AWS cloud services. The DAP aims to streamline data management, enhance decision-making, and ensure the security and integrity of sensitive information.

## Table of Contents
•⁠  ⁠[Phase 1: Service Request Form](#phase-1-service-request-form)
•⁠  ⁠[Phase 2: DAP Design and Implementation](#phase-2-dap-design-and-implementation)

## Phase 1: Service Request Form

### Project Description
Jaspal designed a Data Analytics Platform (DAP) for service request data to enhance the efficiency of service delivery. The project involved ETL processes using AWS Glue, data cleaning, and analysis to identify operational bottlenecks and resource allocation issues.

### Objective
To analyze service request data for 2023 and 2024, enhance operational efficiency, and provide real-time insights into service delivery.

### Dataset
•⁠  ⁠Service Requests 2023: 100 entries including request type, status, timestamps, etc.
•⁠  ⁠Service Requests 2024: 100 entries mirroring the 2023 dataset structure.

![image](https://github.com/user-attachments/assets/bce89263-d93a-4239-b5d1-93fe24eab598)

![image](https://github.com/user-attachments/assets/be600df6-7283-46ee-b0ae-b5d14f7ff48c)



### Methodology
•⁠  ⁠ETL using AWS Glue 
•⁠  ⁠Data cleaning and standardization
•⁠  ⁠Real-time updates for daily reflection on service handling
•⁠  ⁠Analyzed using Amazon Redshift and Athena for insights
![image](https://github.com/user-attachments/assets/620560b4-04fc-4a5c-8b90-c5a5c5ce69d0)

![image](https://github.com/user-attachments/assets/1c198c38-6294-43f0-a62c-d460bc14d9aa)

![image](https://github.com/user-attachments/assets/d11c8431-7d21-4725-8489-6e62868d3c1f)



### Tools and Technologies
•⁠  ⁠AWS Glue
•⁠  ⁠Amazon S3
•⁠  ⁠Amazon Redshift
•⁠  ⁠AWS Athena

![image](https://github.com/user-attachments/assets/8e81731d-b4e1-48c1-b9e8-d0a8fef12acf)

![image](https://github.com/user-attachments/assets/a3bd8d4c-f16d-40a0-ae48-16c9c7a195be)




### Deliverables
•⁠  ⁠Cleaned and structured data for 2023 and 2024
•⁠  ⁠Real-time analysis dashboards
•⁠  ⁠Identified patterns in service requests and response times

![image](https://github.com/user-attachments/assets/eb394cf9-c40f-4b58-bb25-fdd9b183a3af)

![image](https://github.com/user-attachments/assets/d3e7e93e-20b7-4d7f-ab1a-f506642c16eb)



### Exploratory Data Analysis (EDA)
•⁠  ⁠*Objective:* To identify patterns in service requests, response times, and resolution rates.
•⁠  ⁠*Tools:* AWS Glue, Amazon Redshift, Amazon S3, AWS Athena.
•⁠  ⁠*Outcome:* Key insights into operational efficiency and customer satisfaction.

![image](https://github.com/user-attachments/assets/4480bcf7-1084-468c-a32b-d12e7a2c0452)

![image](https://github.com/user-attachments/assets/229e4bb1-b020-4d3f-9943-3d8e2ff39ad3)

![image](https://github.com/user-attachments/assets/a13ae686-dd9f-4181-bd70-6d5597e21b87)


### Data Wrangling
•⁠  ⁠*Objective:* To prepare and clean the dataset for analysis.
•⁠  ⁠*Tools:* AWS Glue DataBrew.
•⁠  ⁠*Outcome:* Data cleaning, null values handling, and standardization of request categories.

![image](https://github.com/user-attachments/assets/bf833b30-563f-4216-a427-05ba3b3ba27d)

![image](https://github.com/user-attachments/assets/ae76a258-e520-4fd9-b965-91874a59c87e)




### Data Protection
•⁠  ⁠*Objective:* To protect data confidentiality and integrity using AWS KMS for encryption.
•⁠  ⁠*Outcome:* Secure storage and access management for service request data.



### Data Governance
•⁠  ⁠*Objective:* To ensure data quality, privacy, and compliance.
•⁠  ⁠*Outcome:* Implemented data quality checks and privacy rules using ETL pipelines.



### Data Monitoring
•⁠  ⁠*Objective:* To monitor resource performance and data integrity.
•⁠  ⁠*Tools:* AWS CloudWatch, AWS CloudTrail.
•⁠  ⁠*Outcome:* Real-time monitoring and alerts for resource usage and data access.



## Phase 2: DAP Design and Implementation

### Data Protection
•⁠  ⁠*Objective:* To implement encryption, user management, and data replication.
•⁠  ⁠*Tools:* AWS KMS, Amazon S3, IAM.
•⁠  ⁠*Outcome:* Secure data storage with encryption and backup strategies.

<img width="432" alt="image" src="https://github.com/user-attachments/assets/5fbe0079-f73c-4a66-b0da-0829e162c9b8">

<img width="432" alt="image" src="https://github.com/user-attachments/assets/76e6a426-8f3f-4798-a2e2-527ca1fb0886">

<img width="432" alt="image" src="https://github.com/user-attachments/assets/327f1844-9ae4-4c85-ab09-7f15d2198ab2">

<img width="432" alt="image" src="https://github.com/user-attachments/assets/fe24c8ff-1047-4695-917d-a9fd01302738">

### Data Governance
•⁠  ⁠*Objective:* To maintain data quality and privacy through ETL pipelines.
•⁠  ⁠*Outcome:* Ensured high-quality, reliable data for analysis.

<img width="432" alt="image" src="https://github.com/user-attachments/assets/36d9038f-d19e-4903-9b0d-68809a950c06">

<img width="432" alt="image" src="https://github.com/user-attachments/assets/ff4c7e55-4114-48c9-9f8c-e55ef5c49eb1">

<img width="432" alt="image" src="https://github.com/user-attachments/assets/142165d1-3b42-41b4-a8b5-a7ea709b3159">

<img width="432" alt="image" src="https://github.com/user-attachments/assets/98e02a81-f9a2-45d0-a126-71c52fdb979d">

<img width="432" alt="image" src="https://github.com/user-attachments/assets/348de6e9-bf12-4747-94bf-0982b35e1af6">

<img width="432" alt="image" src="https://github.com/user-attachments/assets/f685fbfe-873b-4289-840a-cd91e8eaa7b2">


### Data Monitoring
•⁠  ⁠*Objective:* To track resource performance and data integrity.
•⁠  ⁠*Tools:* AWS CloudWatch, AWS CloudTrail.
•⁠  ⁠*Outcome:* Comprehensive logging and monitoring for resource management.# data-analyst-jaspal

<img width="432" alt="image" src="https://github.com/user-attachments/assets/60ad2117-8a66-4d4c-9efa-1fb5a7819b8a">

<img width="432" alt="image" src="https://github.com/user-attachments/assets/5ed99236-b894-499d-b037-2141d03ea0fa">

<img width="432" alt="image" src="https://github.com/user-attachments/assets/7b8b24dc-d22c-4091-822d-52356c51bafa">

<img width="432" alt="image" src="https://github.com/user-attachments/assets/64e83a35-2206-45a8-8472-a003f2a3aea3">

<img width="432" alt="image" src="https://github.com/user-attachments/assets/09939b23-f8ab-4fdd-986b-c26cdc8f14d4">


# University Canada West - Academics Department
## Hiring and Appointment of Faculty

### Project Description
This project focuses on improving the hiring and appointment process for faculty at University Canada West's Academics Department. By utilizing AWS cloud services, the aim is to streamline data management, enhance decision-making, and provide insightful analytics to understand the optimal sourcing channels, candidate drop-off rates, and overall efficiency of the recruitment process.

### Objectives
•⁠  ⁠Identify the optimal sourcing channels for hiring faculty members.
•⁠  ⁠Analyze candidate drop-off rates at various stages of the hiring process.
•⁠  ⁠Generate predictive metrics for offer acceptance probability.
•⁠  ⁠Improve operational efficiency in the hiring and appointment process.

### Datasets
•⁠  ⁠Detailed logs of candidate progress through each hiring stage.
•⁠  ⁠Existing HR data on past offer acceptances and declines.
•⁠  ⁠Records of job offers made and their outcomes.
•⁠  ⁠The source of each applicant and successful hire.

### Methodology
•⁠  ⁠*Data Collection*: Datasets were collected and stored in Amazon S3 buckets.
•⁠  ⁠*Data Cleaning and Wrangling*: AWS Glue DataBrew was used to clean and standardize the data.
•⁠  ⁠*Analysis*: AWS Athena was utilized for analyzing the data to generate insights on the hiring process.
•⁠  ⁠*Visualization*: Created visual representations of metrics such as candidate drop-off rates and optimal sourcing channels.
•⁠  ⁠*Monitoring*: AWS CloudWatch was used for tracking resource performance and ensuring data integrity.

<img width="432" alt="image" src="https://github.com/user-attachments/assets/2774dbf5-7881-4807-8ff1-3a73c382e4a8">

<img width="432" alt="image" src="https://github.com/user-attachments/assets/72390226-28ea-4339-b4cd-2069d3cc8f8b">

<img width="432" alt="image" src="https://github.com/user-attachments/assets/120c4cac-23a8-4eac-be8e-8e587968e5ce">

<img width="432" alt="image" src="https://github.com/user-attachments/assets/0ea1e32b-ff2e-42f3-b6e1-1c3926d3e18b">

<img width="432" alt="image" src="https://github.com/user-attachments/assets/33858ac4-fea8-4d32-924b-d95800374ffc">

<img width="432" alt="image" src="https://github.com/user-attachments/assets/634405f2-df73-42dd-8577-fc4f3ba43062">


### Tools and Technologies
•⁠  ⁠*Amazon S3*: For data storage.
•⁠  ⁠*AWS Glue DataBrew*: For data cleaning and wrangling.
•⁠  ⁠*AWS Athena*: For data analysis.
•⁠  ⁠*AWS CloudWatch*: For monitoring and logging.
•⁠  ⁠*AWS IAM*: For managing user access and roles.

### Deliverables
•⁠  ⁠Cleaned and structured datasets for the hiring process.
•⁠  ⁠Analytical insights on candidate drop-off rates and offer acceptance probabilities.
•⁠  ⁠Visual dashboards depicting the hiring funnel and optimal sourcing channels.
•⁠  ⁠Reports summarizing key findings and recommendations for improving the hiring process.


