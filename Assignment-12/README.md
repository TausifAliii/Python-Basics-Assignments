# Assignment 12: Glass Classification using Random Forest

## Overview
This project focuses on building a machine learning model to classify different types of glass based on their chemical composition. The dataset contains multiple numerical features such as refractive index and elements like Sodium, Magnesium, Aluminum, Silicon, Calcium, etc.

The goal is to predict the type of glass using these features. This is a multi-class classification problem solved using the Random Forest algorithm.

---

## Objective
- To understand the structure of the glass dataset
- To perform Exploratory Data Analysis (EDA)
- To preprocess the data for machine learning
- To build and evaluate a Random Forest model
- To analyze feature importance and model performance

---

## Dataset Description
The dataset includes the following features:

- RI: Refractive Index  
- Na: Sodium  
- Mg: Magnesium  
- Al: Aluminum  
- Si: Silicon  
- K: Potassium  
- Ca: Calcium  
- Ba: Barium  
- Fe: Iron  

### Target Variable:
- Type of glass (multi-class classification)

---

## Steps Performed

### 1. Data Loading
- Loaded dataset using OpenML
- Converted into Pandas DataFrame

### 2. Data Understanding
- Checked data types and structure using `info()`
- Generated statistical summary using `describe()`
- Checked missing values

### 3. Exploratory Data Analysis (EDA)
- Used histograms to understand feature distribution
- Used boxplots to detect outliers
- Analyzed patterns in the dataset

### 4. Correlation Analysis
- Created heatmap to understand relationships between features
- Identified important and weak correlations

### 5. Data Preprocessing
- Separated features (X) and target (y)
- Applied Label Encoding to convert categorical target into numerical form

### 6. Feature Scaling
- Used StandardScaler to normalize feature values
- Improved model performance and stability

### 7. Train-Test Split
- Split dataset into 80% training and 20% testing data

### 8. Model Building
- Built Random Forest Classifier
- Used class_weight='balanced' to handle imbalance

### 9. Model Evaluation
- Evaluated using accuracy score
- Generated classification report
- Visualized confusion matrix

### 10. Feature Importance
- Identified most important features influencing predictions

### 11. Hyperparameter Tuning
- Used GridSearchCV to find best model parameters

---

## Key Techniques Used
- Random Forest Algorithm
- Feature Scaling (StandardScaler)
- Label Encoding
- GridSearchCV
- Data Visualization (Seaborn & Matplotlib)

---

## Results & Insights
- The Random Forest model achieved good accuracy
- Feature importance helped identify key influencing variables
- The model handled multi-class classification effectively
- Class imbalance was managed using class weights

---

## Strengths & Limitations

### Strengths:
- Handles non-linear relationships effectively  
- Reduces overfitting using multiple trees  
- Works well with complex datasets  

### Limitations:
- Can be computationally expensive  
- Less interpretable compared to simple models  

---

## Real-World Applications
- Glass manufacturing quality control  
- Material classification in industries  
- Forensic analysis of glass samples  
---

## Author
**Tausif Ali**  
Data Science Weekday – Hyderabad  
