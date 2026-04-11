## Assignment 10: Drug Response Classification using Support Vector Machine (SVM)

## Project Overview

This project focuses on solving a real-world healthcare problem using machine learning. The goal is to predict whether a patient will respond positively to a drug based on various biological and medical features.

In the pharmaceutical industry, drug testing is a costly and time-consuming process. Not every patient responds to a drug in the same way due to differences in metabolism, medical history, and physiological conditions. By using machine learning, we can predict drug effectiveness early, helping reduce clinical trial costs and improve patient care.

This project demonstrates a complete data science workflow, including data preprocessing, exploratory data analysis (EDA), model building, and evaluation using Support Vector Machine (SVM).

---

## Objective

The main objective of this project is to build a classification model that can predict drug response:

- **0 → No Response**
- **1 → Positive Response**

The model aims to assist in decision-making for personalized medicine by identifying whether a drug is likely to be effective for a patient.

---

## Dataset Description

The dataset contains multiple patient-related features such as:

- Drug Dosage (mg)
- Systolic Blood Pressure (mmHg)
- Heart Rate (BPM)
- Liver Toxicity Index (U/L)
- Blood Glucose Level (mg/dL)
- Drug Response (Target Variable)

Each row represents a patient and their response to a drug based on these medical attributes.

---

## Steps Performed

The following steps were performed in this project:

### 1. Data Loading
The dataset was loaded using pandas and initial inspection was done to understand its structure.

### 2. Data Understanding
Checked data types, missing values, and statistical summaries to identify potential issues.

### 3. Exploratory Data Analysis (EDA)
Used histograms and boxplots to analyze data distribution and identify outliers.

### 4. Correlation Analysis
Generated a heatmap to understand relationships between different features.

### 5. Data Preprocessing
- Cleaned column names
- Encoded categorical variables (if any)
- Separated features (X) and target variable (y)

### 6. Train-Test Split
Split the dataset into training and testing sets to evaluate model performance.

### 7. Feature Scaling
Applied StandardScaler to normalize feature values for better SVM performance.

### 8. Model Building (SVM)
Trained a Support Vector Machine model using a linear kernel.

### 9. Model Evaluation
Evaluated the model using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

### 10. Kernel Comparison
Compared performance of:
- Linear Kernel
- Polynomial Kernel
- RBF Kernel

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Results & Insights

- The SVM model performed well in classifying drug responses.
- Feature scaling significantly improved model performance.
- The RBF kernel performed better in capturing non-linear patterns.
- The confusion matrix showed a good balance between correct predictions and errors.

---

## Model Strengths and Limitations

### Strengths:
- Effective for high-dimensional data
- Works well for classification problems
- Can handle non-linear data using kernels

### Limitations:
- Sensitive to feature scaling
- Performance depends on kernel selection
- Can be computationally expensive for large datasets

---

## Real-World Application

This model can be used in the healthcare industry to support personalized medicine. Doctors can predict whether a drug will work for a patient before prescribing it, reducing unnecessary treatments and improving patient outcomes.

Additionally, pharmaceutical companies can use such models to optimize clinical trials, saving time and resources by identifying effective drugs early.

---

## Conclusion

In this project, we successfully implemented a Support Vector Machine model for drug response classification. The complete workflow from data exploration to model evaluation was performed in a structured and systematic manner.

This project highlights the importance of data preprocessing, feature scaling, and model selection in achieving good performance. It also demonstrates how machine learning can be applied to solve real-world healthcare problems.

---

## Files Included

- `Assignment_10_SVM.ipynb` → Jupyter Notebook  
- `Pharma_Industry.csv` → Dataset  
- `README.md` → Project documentation  

---

## Author

**Tausif Ali**  
Data Science Weekday Batch – Hyderabad  

---
