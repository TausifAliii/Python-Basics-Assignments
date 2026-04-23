# SONAR Mine vs Rock Classification using Artificial Neural Networks

## Overview

This project focuses on building a machine learning model to classify sonar signals as either a mine or a rock. The dataset contains sonar signal readings collected from underwater objects. The main goal is to train a model that can learn patterns from these signals and make accurate predictions.

This is a binary classification problem and is solved using an Artificial Neural Network (ANN).

---

## Business Objective

The objective of this project is to develop a system that can automatically detect underwater mines. This is important for improving maritime safety and supporting naval operations. Manual detection of sonar signals is difficult, so using machine learning helps improve accuracy and efficiency.

---

## Problem Statement

The dataset consists of sonar signals that are reflected from different objects. Each signal is represented by 60 numerical features. The target variable indicates whether the signal belongs to a mine (M) or a rock (R).

The task is to build a model that can correctly classify these signals based on the input features.

---

## Dataset Information

* Total samples: 208
* Number of features: 60
* Target classes: Mine (M), Rock (R)

Each feature represents the energy of the sonar signal in a specific frequency band.

---

## Approach

The project follows a structured approach:

1. Load and understand the dataset
2. Clean the data and handle invalid values
3. Convert the target variable into numeric format
4. Apply feature scaling
5. Split the dataset into training and testing sets
6. Build an Artificial Neural Network model
7. Train the model using training data
8. Evaluate the model using test data
9. Improve performance using hyperparameter tuning

---

## Model Details

The ANN model consists of:

* Input layer with 60 features
* Hidden layers with ReLU activation
* Output layer with sigmoid activation
* Optimizer: Adam
* Loss function: Binary crossentropy

---

## Evaluation Metrics

The model is evaluated using the following metrics:

* Accuracy
* Precision
* Recall
* F1 Score

A confusion matrix is also used to understand prediction results.

---

## Results

The baseline model provides good performance, and the tuned model improves the results further. Hyperparameter tuning helps in achieving better accuracy and reducing overfitting.

---

## Conclusion

In this project, we successfully built an Artificial Neural Network model to classify sonar signals. The model was able to learn patterns from the data and make accurate predictions.

This project demonstrates how deep learning can be applied to real-world problems and highlights the importance of preprocessing and model tuning.

---

## Files Included

* Jupyter Notebook file
* Dataset file
* README file

---

## Author

Tausif Ali
