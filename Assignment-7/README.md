# Assignment 7 - Multiple Linear Regression

## Overview

This assignment focuses on predicting the price of Toyota Corolla cars using multiple linear regression. The dataset contains various features such as age, kilometers driven, fuel type, horsepower, and other specifications. The goal is to understand how these factors influence the price and to build models that can make accurate predictions.

---

## Objective

The objective of this assignment is to analyze the relationship between multiple input variables and the car price. It also aims to compare different regression models and understand their performance in predicting the target variable.

---

## Dataset Description

The dataset includes the following variables:

- Age: Age of the car in years  
- KM: Total kilometers driven  
- Fuel_Type: Type of fuel used  
- HP: Horsepower of the car  
- Automatic: Whether the car is automatic or manual  
- CC: Engine capacity  
- Doors: Number of doors  
- Weight: Weight of the car  
- Price: Target variable (car price)  

---

## Steps Performed

### 1. Data Preprocessing  
The dataset was checked for missing values and cleaned accordingly. Categorical variables such as fuel type were converted into numerical format using encoding so that the model could process them.

### 2. Exploratory Data Analysis  
Summary statistics and visualizations were used to understand the distribution of variables and their relationships. This helped in identifying patterns and correlations in the data.

### 3. Model Building  
Three different models were built:
- Linear Regression  
- Ridge Regression  
- Lasso Regression  

Each model was trained using the training dataset.

### 4. Model Evaluation  
The models were evaluated using Mean Squared Error and R-squared values. These metrics helped in understanding how accurate the predictions were.

### 5. Regularization Techniques  
Ridge regression was used to reduce overfitting by penalizing large coefficients. Lasso regression was used for feature selection by removing less important variables.

---

## Conclusion

The analysis shows that multiple linear regression can effectively predict car prices using various features. Ridge regression improved model stability, while Lasso regression simplified the model by selecting important variables. This assignment demonstrates how different regression techniques can be used to build accurate and interpretable models.

---

## Files

- multiple_linear_regression.ipynb  
- ToyotaCorolla - MLR.csv  

---

## Author

Tausif Ali
