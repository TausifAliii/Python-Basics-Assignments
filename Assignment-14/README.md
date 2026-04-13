## Assignment 14: PCA and Clustering Analysis

## Student Details
- **Name:** Tausif Ali  
- **Batch:** Data Science Weekday – Hyderabad  
- **Topic:** Principal Component Analysis (PCA) & Clustering  

---

## Project Overview

This project focuses on applying **Principal Component Analysis (PCA)** for dimensionality reduction and **K-Means clustering** for grouping data points. The goal is to analyze high-dimensional data efficiently and understand the impact of dimensionality reduction on clustering performance.

The workflow includes data exploration, preprocessing, PCA transformation, clustering on both original and reduced data, evaluation, and comparison.

---

## Dataset Description

The dataset used is the **Wine Dataset**, which contains multiple numerical features describing chemical properties of wines.

These features include:
- Alcohol  
- Malic Acid  
- Ash  
- Alcalinity of Ash  
- Magnesium  
- Total Phenols  
- Flavanoids  
- Nonflavanoid Phenols  
- Proanthocyanins  
- Color Intensity  
- Hue  
- OD280/OD315  
- Proline  

All features are numerical and suitable for PCA and clustering.

---

## Technologies Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
  - StandardScaler  
  - PCA  
  - KMeans  
  - Silhouette Score  

---

## Steps Performed

### 1. Data Loading
- Loaded dataset using pandas  
- Verified structure using `.head()`  

### 2. Data Understanding
- Checked data types using `.info()`  
- Generated summary statistics using `.describe()`  
- Verified missing values  

### 3. Exploratory Data Analysis (EDA)
- Used histograms to understand feature distribution  
- Used box plots to detect outliers  

### 4. Correlation Analysis
- Created heatmap to analyze relationships between features  
- Identified correlated features  

### 5. Feature Scaling
- Applied StandardScaler  
- Ensured all features have mean = 0 and standard deviation = 1  

### 6. PCA Implementation
- Applied PCA to reduce dimensionality  
- Used scree plot (cumulative explained variance)  
- Selected optimal number of components  

### 7. Clustering (Original Data)
- Applied K-Means clustering on scaled data  
- Grouped data into clusters  

### 8. Clustering (PCA Data)
- Applied K-Means on PCA-transformed data  
- Improved visualization and computational efficiency  

### 9. Visualization
- Used scatter plot for PCA clusters  
- Visualized clusters in 2D space  

### 10. Evaluation
- Used Silhouette Score to evaluate clustering performance  
- Compared clustering quality between original and PCA data  

---

## Comparative Analysis

Clustering on PCA-transformed data is faster and easier to visualize due to reduced dimensions. However, clustering on the original dataset retains complete information and may capture more detailed patterns.

This creates a trade-off:
- **PCA Data:** Faster, simpler, easier visualization  
- **Original Data:** More detailed but computationally expensive  

---

## Conclusion

PCA effectively reduces dimensionality while preserving most of the important information. It simplifies the dataset and improves computational efficiency.

Clustering combined with PCA provides a powerful approach for analyzing high-dimensional datasets. This technique is widely used in real-world applications such as customer segmentation, anomaly detection, and image processing.

---

## Key Learnings

- Understanding dimensionality reduction using PCA  
- Importance of feature scaling  
- Clustering techniques using K-Means  
- Evaluation using silhouette score  
- Trade-offs between accuracy and efficiency  

---

## Future Improvements

- Use Elbow Method to find optimal clusters  
- Apply hierarchical clustering  
- Try DBSCAN for density-based clustering  
- Use real-world large datasets  
