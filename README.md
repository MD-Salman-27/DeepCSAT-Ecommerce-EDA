# DeepCSAT – Ecommerce Customer Satisfaction Analysis

## Project Overview

This project focuses on analyzing customer support data from an e-commerce platform to understand the factors influencing Customer Satisfaction Score (CSAT). The main objective of the project is to perform Exploratory Data Analysis (EDA) and data preparation on the dataset to identify patterns, trends, and relationships between different variables that affect customer satisfaction.

The project uses data analysis techniques to examine customer interactions with support services, including order details, issue categories, support channels, handling time, and product information. By analyzing these factors, the project aims to provide insights that can help improve customer service quality and overall customer experience in the e-commerce industry.

---

## Problem Statement

In the rapidly growing e-commerce industry, customer satisfaction is a key factor in determining business success. Customers frequently contact support teams to resolve issues related to products, orders, delivery, and services. Due to the large volume of customer support interactions, it becomes difficult for organizations to manually analyze customer feedback and identify the factors that influence satisfaction levels.

The available dataset contains various attributes related to customer support interactions such as product category, issue type, support channel, response time, and customer location. However, this raw data may contain missing values, redundant information, and inconsistent formats. Therefore, it is necessary to perform data cleaning, preparation, and exploratory data analysis to extract meaningful insights from the dataset.

---

## Dataset Description

The dataset used in this project contains customer support interaction records from an e-commerce platform.

Key characteristics of the dataset include:

* Large dataset containing thousands of customer support records
* Multiple features related to customer service interactions
* Includes both numerical and categorical data
* Contains a target variable called **CSAT Score (Customer Satisfaction Score)**

Example features in the dataset include:

* Unique ID
* Order ID
* Customer City
* Channel Name
* Product Category
* Issue Category
* Sub-category
* Order Status
* Item Price
* Connected Handling Time
* Agent Shift
* Supervisor
* Manager
* CSAT Score

---

## Project Workflow

### 1. Data Understanding

* Loading the dataset
* Understanding dataset structure
* Identifying column types and features

### 2. Data Cleaning

* Checking missing values
* Handling null values
* Removing duplicate records
* Dropping irrelevant columns

### 3. Data Preparation

* Preparing categorical variables
* Converting data into appropriate formats
* Preparing dataset for analysis

### 4. Exploratory Data Analysis (EDA)

Various visualizations and statistical methods are used to analyze the dataset and identify patterns.

EDA tasks include:

* CSAT Score distribution
* Channel vs CSAT analysis
* Product category analysis
* Customer city distribution
* Item price distribution
* Handling time analysis
* Agent shift analysis
* Tenure bucket analysis
* Issue category analysis
* Correlation analysis

---

## Tools and Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook / Google Colab

---

## Key Insights

Exploratory Data Analysis helps in identifying patterns in customer support data. The analysis provides insights into how different factors such as product category, issue type, support channel, and response time may influence customer satisfaction.

These insights can help organizations improve customer support processes, reduce response times, and enhance overall customer experience.

---

## Conclusion

This project demonstrates how data analysis techniques can be applied to customer support datasets to extract meaningful insights. By performing exploratory data analysis and data preparation, it becomes possible to understand the factors that affect customer satisfaction and identify areas where service quality can be improved.

The insights obtained from this analysis can help e-commerce companies make data-driven decisions to enhance customer support services and increase customer satisfaction.

---

## Future Work

Future improvements to this project may include:

* Building machine learning models to predict CSAT Score
* Creating interactive dashboards for data visualization
* Performing advanced feature engineering
* Implementing real-time customer satisfaction monitoring systems
