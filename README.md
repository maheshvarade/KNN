# K-Nearest Neighbors (KNN) for Car Safety Classification 🚗

This project implements the **K-Nearest Neighbors (KNN)** algorithm to classify cars based on safety using the **Car Evaluation Dataset** from UCI Machine Learning Repository.

## 📌 Features
- Preprocesses categorical data using Label Encoding.
- Normalizes features using `StandardScaler` to improve distance calculations.
- Implements **KNN Classification** using Scikit-Learn.
- Optimizes hyperparameters using **RandomizedSearchCV** for best results.
- Evaluates model performance with accuracy, confusion matrix, and classification report.

## 📂 Dataset
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Car+Evaluation)
- **Attributes**: 
  - Buying price
  - Maintenance cost
  - Number of doors
  - Passenger capacity
  - Luggage boot size
  - Safety level
  - Class (Target Variable)


Baseline Accuracy (Default KNN): 81.50%

Optimized Accuracy (Using RandomizedSearchCV): 92% 🚀
