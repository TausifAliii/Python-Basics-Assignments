# Assignment 8 - Logistic Regression (Diabetes Prediction)

## Overview

This assignment focuses on predicting whether a person has diabetes using logistic regression. The dataset contains medical information such as glucose level, blood pressure, BMI, age, and other health-related factors. The goal is to build a classification model that can clearly identify whether a patient is diabetic or not.

---

## Objective

The main objective of this assignment is to understand how different medical features influence the chances of diabetes and to build a model that can classify outcomes accurately. It also involves evaluating model performance using multiple metrics.

---

## Dataset Description

The dataset includes the following features:

- Pregnancies: Number of times pregnant  
- Glucose: Blood glucose level  
- BloodPressure: Blood pressure level  
- SkinThickness: Skin fold thickness  
- Insulin: Insulin level  
- BMI: Body mass index  
- DiabetesPedigreeFunction: Genetic influence  
- Age: Age of the patient  
- Outcome: Target variable (0 = No Diabetes, 1 = Diabetes)  

---

## Steps Performed

### 1. Data Exploration  
The dataset was explored using summary statistics and visualizations. Histograms were used to understand the distribution of values, and a heatmap was used to identify relationships between features.

### 2. Data Preprocessing  
Zero values in important medical columns were replaced with mean values to ensure realistic data. This step improves model performance and avoids incorrect learning.

### 3. Model Building  
A logistic regression model was built using the training dataset. This model predicts the probability of diabetes and classifies it into two categories.

### 4. Model Evaluation  
The model was evaluated using:
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- ROC-AUC Score  

The ROC curve was also plotted to visualize model performance.

### 5. Interpretation  
The coefficients of the model were analyzed to understand which features have the most impact. Glucose, BMI, and age were found to be important factors in predicting diabetes.

---

## Conclusion

The logistic regression model performed well in classifying patients as diabetic or non-diabetic. The analysis shows that certain medical features play a significant role in prediction. This approach can be useful in healthcare for early detection and decision-making.

---

## Files

- logistic_regression.ipynb  
- diabetes.csv  

---

## Author

Tausif Ali
