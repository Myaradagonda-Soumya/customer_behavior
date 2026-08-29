Customer Behaviour Analysis – Data Analytics Project

📌 Project Overview

This project focuses on analyzing customer purchasing behaviour by using Python, SQL, PostgreSQL, and Power BI. The objective is to extract meaningful insights from raw customer data by performing data cleaning, exploratory data analysis (EDA), SQL-based analysis, and interactive dashboard creation.

The project follows a complete end-to-end data analytics workflow starting from data loading to generating business insights through visualization.

🎯 Project Objectives

Understand customer purchasing patterns and behaviour.

Clean and prepare raw data for analysis.

Perform Exploratory Data Analysis (EDA) to identify trends and relationships.

Use SQL queries to answer business questions.

Build an interactive Power BI dashboard.

Generate actionable insights through reports and visualizations.

🛠️ Tools & Technologies Used

Tool	Purpose:
Python	Data loading, cleaning, and EDA
Pandas	Data manipulation and preprocessing
NumPy	Numerical operations
Matplotlib & Seaborn	Data visualization
PostgreSQL	Database management and SQL analysis
SQL	Business queries and data analysis
Power BI	Dashboard development and reporting
Jupyter Notebook:Python development environment
GitHub	Project documentation and version control

📂 Project Workflow

1. Data Loading

Imported the raw dataset into Python using Pandas.

Checked dataset structure, columns, and data types.

Reviewed initial records to understand the data.

Example:

import pandas as pd

df = pd.read_csv("customer_data.csv")

df.head()

2. Data Cleaning

Performed data preprocessing steps:

Checked missing values.

Removed duplicate records.

Corrected incorrect data types.

Handled inconsistent values.

Prepared clean data for analysis.

Example:

df.isnull().sum()

df.drop_duplicates(inplace=True)

3. Exploratory Data Analysis (EDA)

Performed EDA to discover patterns and trends.

Analysis included:

Customer demographics analysis.

Purchase behaviour analysis.

Category-wise sales analysis.

Spending patterns.

Customer segmentation.

Visualizations created:

Bar charts

Histograms

Count plots

Distribution plots

Correlation analysis

EDA helped identify important business insights from the dataset.

4. PostgreSQL Database Analysis

The cleaned dataset was loaded into PostgreSQL.

SQL was used to answer business questions such as:

Total revenue generated.

Average purchase amount.

Customer segmentation.

Top purchased products.

Category performance.

Customer behaviour analysis.

Example SQL query:

SELECT 
category,
SUM("Purchase Amount (USD)") AS total_revenue
FROM customer
GROUP BY category;

5. Power BI Dashboard Development

Created an interactive dashboard to present insights visually.

Dashboard includes:

Key Performance Indicators (KPIs)

Total Customers

Total Revenue

Average Purchase Amount

Top Performing Categories

Visualizations

Customer distribution

Sales by category

Purchase trends

Customer segments

Product analysis

Power BI dashboard allows users to interact with filters and explore business insights.

📊 Project Report

The final report includes:

Project Introduction

Problem Statement

Dataset Description

Data Cleaning Process

EDA Findings

SQL Analysis

Dashboard Screenshots

Business Insights

Conclusion

🚀 How to Run the Project

Step 1: Clone Repository

git clone https://github.com/yourusername/customer-behaviour-analysis.git

Step 2: Install Required Libraries

Install Python dependencies:

pip install pandas numpy matplotlib seaborn jupyter

Step 3: Run Python Notebook

Open Jupyter Notebook:

jupyter notebook

Run the notebook to perform:

Data loading

Data cleaning

EDA

Visualization

Step 4: PostgreSQL Setup

1. Create a database in PostgreSQL.


2. Import cleaned dataset.


3. Execute SQL queries provided in the SQL folder.

Step 5: Open Power BI Dashboard

1. Open the .pbix file.


2. Refresh data connection.


3. Explore dashboard insights.

📁 Project Structure

Customer-Behaviour-Analysis/
│
├── Dataset/
│   └── customer_data.csv
│
├── Python/
│   └── Data_Cleaning_EDA.ipynb
│
├── SQL/
│   └── Business_Queries.sql
│
├── PowerBI/
│   └── Customer_Dashboard.pbix
│
├── Report/
│   └── Project_Report.pdf
│
└── README.md


📌 Key Insights Generated

Identified customer purchasing patterns.

Segmented customers based on purchase frequency.

Found high-performing product categories.

Analyzed revenue contribution.

Created a dashboard for decision-making.


✅ Conclusion

This project demonstrates a complete Data Analyst workflow including data preparation, exploratory analysis, SQL querying, and business intelligence reporting. The combination of Python, PostgreSQL, and Power BI helped transform raw data into meaningful insights for better decision-making.


👩‍💻 Author

Soumya Myaradagonda
Data Analyst Aspirant
Skills: Python | SQL | Excel | Power BI | Data Analytics
