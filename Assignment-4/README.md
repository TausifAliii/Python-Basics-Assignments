# Assignment 4 - Hospital Patient Data Analysis

## Overview
This assignment focuses on analyzing hospital patient and billing data using data cleaning, aggregation, merging, and transformation techniques.

The goal is to prepare a clean and structured dataset that can be used for further analysis such as department-wise revenue and patient billing insights.

## Dataset
- Patient_Data.csv
- Billing_Data.csv

## Tasks Performed

### 1. Data Loading and Inspection
- Loaded dataset using pandas
- Checked structure using info() and head()

### 2. Data Cleaning
- Selected relevant columns (PatientID, Department, Doctor, BillAmount)
- Removed unnecessary administrative columns
- Handled missing values using mean
- Removed duplicate patient records

### 3. Data Aggregation
- Used groupby to calculate total bill amount per department

### 4. Data Integration
- Merged patient and billing datasets using PatientID

### 5. Data Transformation
- Added new patient records using concatenation
- Added new columns such as InsuranceCovered and FinalAmount

## Key Insights
- Department-wise revenue helps identify high-performing departments
- Data cleaning improves accuracy and reliability
- Merging datasets provides a complete view of patient billing
- Feature engineering enhances dataset usability

## Conclusion
This assignment demonstrates practical data analysis skills such as data cleaning, aggregation, merging, and transformation. These techniques are essential for real-world data analysis and decision-making.

## Author
Tausif Ali
