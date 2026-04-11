# Assignment 11: Breast Cancer Prediction using Decision Tree

## Project Overview

This project focuses on building a machine learning model using the Decision Tree algorithm to predict whether a tumor is malignant or benign. The dataset used in this project is a standard classification dataset available in the scikit-learn library, which contains multiple medical features.

Early detection of diseases such as cancer is very important in the healthcare industry. Machine learning models can help doctors analyze patient data and make faster, more accurate decisions. This project demonstrates how Decision Trees can be used for classification tasks in real-world healthcare scenarios.

The project follows a complete data science workflow, including data understanding, exploratory data analysis (EDA), model building, evaluation, and optimization.

---

## Objective

The main objective of this project is to:

- Build a Decision Tree Classification model
- Predict whether a tumor is malignant or benign
- Analyze model performance using evaluation metrics
- Understand how decision trees make predictions

---

## Dataset Description

The dataset is taken from the scikit-learn library and contains:

- Multiple numerical features representing medical measurements
- A target variable:
  - **0 → Malignant**
  - **1 → Benign**

The dataset is clean, well-structured, and does not require extensive preprocessing.

---

## Steps Performed

### 1. Data Loading
Loaded dataset using sklearn and converted it into a pandas DataFrame.

### 2. Data Understanding
Checked data types, summary statistics, and missing values.

### 3. Exploratory Data Analysis (EDA)
Used histograms and boxplots to understand feature distributions.

### 4. Correlation Analysis
Created a heatmap to study relationships between features.

### 5. Data Preprocessing
Separated features (X) and target variable (y). No major preprocessing required.

### 6. Train-Test Split
Split the dataset into training and testing sets (80-20).

### 7. Model Building
Implemented Decision Tree Classifier using scikit-learn.

### 8. Model Evaluation
Evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

### 9. Hyperparameter Tuning
Used GridSearchCV to find the best parameters.

### 10. Model Visualization
Visualized the decision tree to understand decision rules.

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

- The Decision Tree model performed well in classification tasks.
- The dataset being clean helped in achieving good accuracy.
- Hyperparameter tuning improved model performance.
- Visualization helped in understanding decision rules clearly.

---

## Model Strengths and Limitations

### Strengths:
- Easy to understand and interpret  
- Does not require feature scaling  
- Works well for classification problems  

### Limitations:
- Can overfit if not properly tuned  
- Sensitive to small changes in data  
- Less stable compared to ensemble models  

---

## Real-World Application

This model can be used in the healthcare industry to assist doctors in diagnosing diseases at an early stage. It can help in identifying whether a tumor is malignant or benign, which is crucial for treatment planning.

Such models can improve decision-making, reduce diagnosis time, and enhance patient outcomes.

---

## conclusion

In this project, we successfully built a Decision Tree Classification model and applied it to a real-world healthcare dataset. We performed data analysis, model training, evaluation, and optimization.

The project demonstrated how machine learning can be used effectively for classification problems. Decision Trees provided clear interpretability, making them suitable for applications where understanding the decision process is important.

---

## Files Included

- `Assignment_11_Decision_Tree.ipynb`
- `README.md`

---

## Author

**Tausif Ali**  
Data Science Weekday Batch – Hyderabad
