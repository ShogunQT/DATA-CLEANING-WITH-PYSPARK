# DATA-CLEANING-WITH-PYSPARK #
COMPANY NAME - CODETECH IT SOLUTIONS
NAME - JAY ZAWARE
INTERN ID - CT04DR1224
DOMAIN - BIG DATA
DURATION - 4 WEEKS
MENTOR - NEELA SANTOSH

# TASK DESCRIPTION #
# Task Description: Data Cleaning and Preprocessing Using PySpark
Objective:
The main goal of this task is to clean and preprocess a large dataset using PySpark to ensure data consistency, completeness, and readiness for further analysis. The process focuses on identifying and handling missing values (nulls) and duplicate records efficiently in a distributed environment.

# Dataset Used:
Name: Netflix Movies and TV Shows Dataset (netflix_titles.csv)
Description: This dataset contains information about movies and TV shows available on Netflix, including title, director, cast, country, release year, rating, and duration.
Source: Public dataset from Kaggle

# Tools and Environment:
Platform: Google Colab
Framework: Apache Spark (PySpark API)
Programming Language: Python
Data Format: CSV

# Tasks Performed:
Setup PySpark environment in Google Colab for distributed data processing.
Load the Netflix dataset using PySpark’s read.csv() function.
Inspect the dataset by viewing schema, sample records, and total number of rows.
Identify missing (null) values in each column using PySpark functions (isNull(), when(), _sum()).
Remove rows containing null values using na.drop().
Save the cleaned dataset back to CSV format for future use.

# Expected Outcome:
A cleaned version of the Netflix dataset with:
No missing (null) values
No duplicate records

# OUTCOME SCREENSHOTS




