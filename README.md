# Home Sales Data Analysis using SparkSQL

This project demonstrates the use of Apache Spark and SparkSQL to analyze home sales data. The data is loaded from a CSV file, and various queries are performed to gain insights into the dataset.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Setup](#setup)
- [Usage](#usage)
- [Queries](#queries)
- [Results](#results)
- [Conclusion](#conclusion)

## Introduction
The purpose of this project is to showcase the capabilities of SparkSQL in analyzing large datasets. By leveraging the power of Spark, we can efficiently process and query the home sales data to extract meaningful information.

## Dataset
The dataset used in this project is stored in a CSV file named "home_sales_revised.csv". It contains information about home sales, including details such as the sale date, price, number of bedrooms, bathrooms, square footage, and more.

## Setup
To run this project, you need to have the following dependencies installed:
- Apache Spark
- PySpark
- Python 3.x

Additionally, make sure you have the "home_sales_revised.csv" file available in the project directory.

## Usage
1. Clone the repository
2. Navigate to the project directory
3. Launch a Spark shell
4. Execute the SparkSQL queries
# Run the queries from the provided code

## Queries
The project includes several SparkSQL queries to analyze the home sales data:

Average price for a four-bedroom house sold per year
Average price of a home for each year it was built, with 3 bedrooms and 3 bathrooms
Average price of a home for each year it was built, with 3 bedrooms, 3 bathrooms, 2 floors, and 2,000+ sqft living space
Average price of a home per "view" rating, with an average price greater than or equal to $350,000

## Results
The queries provide insights into the home sales data, such as:

Trends in the average price of four-bedroom houses over the years
Relationship between the year a home was built and its average price, based on specific criteria
Impact of the "view" rating on the average price of high-value homes
The results are displayed using the show() method in SparkSQL.

## Conclusion
This project demonstrates the power and efficiency of using SparkSQL to analyze large datasets. By leveraging Spark's distributed computing capabilities, we can quickly process and query the home sales data to extract valuable insights. The queries performed in this project provide a glimpse into the potential of SparkSQL for data analysis and decision-making.
