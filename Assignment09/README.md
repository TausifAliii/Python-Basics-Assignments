# Assignment 9 - Data Preprocessing and Feature Engineering

## Overview

This assignment focuses on preparing raw data for machine learning using the Adult dataset. The dataset contains demographic and work-related information such as age, education, occupation, working hours, and income level. The main goal is to clean the dataset and transform it into a structured format so that machine learning models can understand it properly.

---

## Objective

The objective of this assignment is to apply different data preprocessing and feature engineering techniques. This includes handling missing values, encoding categorical variables, scaling numerical features, creating new meaningful features, and applying transformations. These steps improve the quality of data and help in building accurate models.

---

## Dataset Description

The Adult dataset includes the following important features:

- Age: Age of the individual  
- Education_num: Education level in numeric form  
- Occupation: Type of job  
- Hours_per_week: Working hours per week  
- Capital_gain / Capital_loss: Financial indicators  
- Income: Target variable (<=50K or >50K)  

---

## Steps Performed

### 1. Data Exploration  
The dataset was explored using summary statistics and basic inspection to understand its structure and identify missing values.

### 2. Handling Missing Values  
Missing values represented by '?' were replaced with NaN and removed to ensure clean data.

### 3. Encoding Categorical Variables  
Label Encoding was applied to high-cardinality columns like occupation. One-Hot Encoding was applied to other categorical variables to convert them into numerical form.

### 4. Feature Scaling  
Both Standard Scaling and Min-Max Scaling were applied to bring numerical features into a similar range and improve model performance.

### 5. Feature Engineering  
New features were created:
- **age_hours**: Combination of age and working hours  
- **capital_total**: Net financial gain  

### 6. Log Transformation  
Log transformation was applied to the capital_gain feature to reduce skewness and improve data distribution.

### 7. Outlier Detection  
Isolation Forest was used to detect unusual data points that may negatively affect model performance.

### 8. PPS Score Analysis  
Predictive Power Score (PPS) was used to understand how well features can predict each other and identify important variables.

---

## Conclusion

In this assignment, we prepared the Adult dataset using various preprocessing techniques. Clean and well-structured data is essential for building accurate machine learning models. Feature engineering and transformation further improve the model's ability to learn meaningful patterns.

---

## Files

- assignment9.ipynb  
- adult_with_headers.csv  

---

## Author

Tausif Ali
