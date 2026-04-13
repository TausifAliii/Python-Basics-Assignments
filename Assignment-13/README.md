# Assignment 13: Diabetes Prediction using XGBoost & LightGBM

## Student Details
- **Name:** Tausif Ali  
- **Batch:** Data Science Weekday – Hyderabad  
- **Topic:** XGBoost & LightGBM  

---

## Project Overview

This project focuses on predicting diabetes using advanced boosting algorithms, namely **XGBoost** and **LightGBM**. The objective is to build accurate and efficient classification models using a structured medical dataset.

The workflow includes data loading, exploratory data analysis (EDA), preprocessing, feature scaling, model building, evaluation, and comparison.

---

## Dataset Description

The dataset contains medical attributes such as:

- Pregnancies  
- Glucose  
- Blood Pressure  
- Skin Thickness  
- Insulin  
- BMI  
- Diabetes Pedigree Function  
- Age  
- Outcome (Target Variable: 0 = Non-Diabetic, 1 = Diabetic)

---

## Technologies Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- XGBoost  
- LightGBM  

---

## Steps Performed

### 1. Data Loading
- Loaded dataset using pandas
- Checked structure using `.head()`

### 2. Data Understanding
- Used `.info()`, `.describe()`, `.isnull()`  
- Checked for missing values and data types  

### 3. Exploratory Data Analysis (EDA)
- Histograms to analyze distribution  
- Box plots to detect outliers  

### 4. Correlation Analysis
- Heatmap to identify relationships between features  

### 5. Data Preprocessing
- Separated features (X) and target (y)  

### 6. Feature Scaling
- Applied StandardScaler to normalize features  

### 7. Train-Test Split
- Split dataset into 80% training and 20% testing  

### 8. Model Building
- Implemented XGBoost and LightGBM models  

### 9. Model Evaluation
- Evaluated using:
  - Accuracy  
  - Precision  
  - Recall  
  - F1-score  
- Visualized using Confusion Matrix  

---

## Comparative Analysis

XGBoost achieved slightly higher accuracy, indicating better predictive performance. LightGBM, however, was faster and more computationally efficient.

This highlights a trade-off:
- XGBoost → Better accuracy  
- LightGBM → Better speed & scalability  

---

## Conclusion

Both XGBoost and LightGBM performed effectively for diabetes prediction. XGBoost provided better accuracy, while LightGBM offered faster performance.

This project demonstrates the importance of boosting algorithms in machine learning and their real-world applications in healthcare analytics.

---

## Key Learnings

- Understanding boosting algorithms  
- Importance of feature scaling  
- Model comparison techniques  
- Real-world ML workflow  
- Performance evaluation using multiple metrics  

---

## Future Improvements

- Hyperparameter tuning  
- Cross-validation  
- Handling class imbalance  
- Feature selection techniques  
