## DATA-PIPELINE-DEVELOPMENT
## COMPANY : CODETECH IT SOLUTIONS
## NAME : CHIDURALA MOUNYA SAI
## INTERN ID : CT08OPZ
## DOMAIN : DATA SCIENCE
## DURATION : 4 WEEKS
## MENTOR : NEELA SANTOSH

## PROJECT INFORMATION:
In this project, we focus on analyzing Uber trip data by implementing an ETL (Extract, Transform, Load) pipeline. The goal is to clean, transform, and structure the raw Uber dataset into an optimized format that allows for efficient querying and analysis.

## What is the Purpose of this Task?
Uber generates large volumes of trip records containing valuable insights into passenger behavior, trip distances, fare calculations, and travel patterns. However, raw data often contains missing values, duplicates, and inconsistent formats, making it difficult to analyze directly.

This project aims to process and organize the Uber data into a star schema format, ensuring that it is clean, structured, and ready for advanced data analysis.
## Key Steps in the ETL Process

1️⃣ Data Cleaning
Handle missing values in numerical and categorical columns.
Remove duplicate records to avoid inconsistencies.
Convert datetime fields into a structured format for analysis.
2️⃣ Feature Extraction
Extract time-based attributes such as hour, day, month, and weekday from the pickup and dropoff timestamps.
Identify trip distances and passenger count variations for better insights.
3️⃣ Data Transformation
Encode categorical variables such as payment types and rate codes for consistency.
Normalize numerical data like fare amounts and trip distances for improved processing.
4️⃣ Schema Design & Star Schema Implementation
To optimize the data for fast querying and structured storage, we design a star schema with:

Datetime Dimension – Extracts detailed time-based features.
Passenger Count Dimension – Organizes trip data by passenger numbers.
Trip Distance Dimension – Stores trip distance details.
Rate Code Dimension – Maps rate codes to trip categories.
Pickup & Dropoff Location Dimensions – Stores longitude and latitude values separately.
Payment Type Dimension – Categorizes different payment methods.
Fact Table – Links all dimension tables and stores key transactional details such as fare amount, tip, and total cost.
5️⃣ ETL Pipeline Implementation
The ETL process is implemented using Python and Pandas, allowing us to:

Extract raw Uber data from the CSV file.
Transform and preprocess the dataset into structured tables.
Load the cleaned data into a new file (processed_uber_data.csv) for further use.

## OUTPUT 

![Image](https://github.com/user-attachments/assets/53e19036-5c23-4356-81c8-5a0aa9e21345)

![Image](https://github.com/user-attachments/assets/72515235-e4c8-4c0a-afde-160e01f10c82)


