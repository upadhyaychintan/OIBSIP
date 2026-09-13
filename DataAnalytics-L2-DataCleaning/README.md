# Data Cleaning

## Project Overview

This project focuses on cleaning and preparing a messy employee dataset for further analysis. 
The dataset contains missing values, inconsistent data types, duplicate records, and other data quality issues.

## Objectives

- Inspect the structure and quality of the dataset
- Identify missing values and handle them appropriately
- Check and remove duplicate records
- Standardize text and date values
- Detect outliers using the IQR method
- Correct inappropriate data types
- Compare the dataset before and after cleaning
- Export the cleaned dataset as a CSV file

## Data Cleaning Performed

- Missing Age and Salary values were handled using median imputation.
- Duplicate records were checked and removed where necessary.
- Text fields were standardized by removing unnecessary whitespace.
- Join_Date was converted to datetime format.
- Employee_ID and Phone were converted to string format.
- Salary and Age were converted to appropriate numeric types.
- Outliers were checked using the IQR method.
- A final cleaned CSV file was generated.

## Tools Used

- Python
- Pandas
- NumPy
- Google Colab
- Jupyter Notebook

## Output

The cleaned employee dataset is saved as:

`Cleaned_Messy_Employee_Dataset.csv`
