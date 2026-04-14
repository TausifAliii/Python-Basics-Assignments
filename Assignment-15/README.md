# Assignment 15: Advanced Clustering Analysis (K-Means, DBSCAN & PCA)

## Student Details
- **Name:** Tausif Ali  
- **Batch:** Data Science Weekday – Hyderabad  
- **Topic:** Customer Segmentation using Clustering  

---

## Project Overview

This project focuses on segmenting airline customers based on their behavior using clustering techniques. The analysis includes K-Means and DBSCAN algorithms along with PCA (Principal Component Analysis) for dimensionality reduction and improved visualization.

The goal is to identify meaningful customer groups that can help businesses make better marketing and retention strategies.

---

## Dataset Description

The dataset contains customer information such as:

- Balance (miles earned)  
- Qualifying miles  
- Credit card usage (cc1, cc2, cc3)  
- Bonus miles  
- Flight activity  
- Days since enrollment  
- Award status  

All features are numerical and suitable for clustering.

---

## Technologies Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
  - StandardScaler  
  - KMeans  
  - DBSCAN  
  - PCA  
  - Silhouette Score  

---

## Steps Performed

### 1. Data Loading
- Loaded dataset from Excel  
- Verified structure using `.head()`  

### 2. Data Cleaning
- Removed ID column as it does not contribute to clustering  

### 3. Exploratory Data Analysis (EDA)
- Histograms to analyze distribution  
- Box plots to detect outliers  

### 4. Feature Scaling
- Applied StandardScaler  
- Ensured equal contribution of all features  

### 5. Elbow Method
- Determined optimal number of clusters  
- Selected K = 3  

### 6. K-Means Clustering
- Applied K-Means algorithm  
- Generated cluster labels  

### 7. DBSCAN Clustering
- Applied density-based clustering  
- Detected noise and irregular clusters  

### 8. PCA (Dimensionality Reduction)
- Reduced features to 2 components  
- Improved visualization and interpretation  

### 9. Visualization
- Scatter plots for cluster representation  
- PCA-based cluster visualization  

### 10. Evaluation
- Used Silhouette Score  
  - K-Means: ~0.31  
  - DBSCAN: ~0.25  

---

## Comparative Analysis

K-Means performed better than DBSCAN based on silhouette score, indicating more well-defined clusters.

DBSCAN struggled due to lack of clear dense regions and sensitivity to parameter selection.

PCA improved visualization and helped reveal cluster structure more clearly.

---

##Business Insights

- **Cluster 1:** High-value customers with high activity and engagement  
- **Cluster 2:** Medium-level customers with moderate usage  
- **Cluster 3:** Low-value customers with minimal engagement  

These insights can be used for:
- Targeted marketing campaigns  
- Customer retention strategies  
- Loyalty program optimization  

---

## Key Learnings

- Importance of feature scaling in clustering  
- Choosing optimal K using Elbow method  
- Difference between centroid-based and density-based clustering  
- Role of PCA in simplifying complex datasets  
- Evaluating clustering using silhouette score  

---

## Future Improvements

- Hyperparameter tuning for DBSCAN  
- Use of advanced clustering (Hierarchical, GMM)  
- Applying clustering on larger real-world datasets  
- Cluster profiling using statistical summaries  

---

## Conclusion

K-Means provided better clustering performance for this dataset, while DBSCAN helped identify noise points. PCA enhanced visualization and interpretability.

This project demonstrates how clustering can be effectively used in real-world business scenarios for customer segmentation and decision-making.
