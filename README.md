# Machine Learning Assignment 3

This repository contains the implementation and comparison of multiple **machine learning classifiers** from scratch and using scikit-learn.  
The work is structured around Assignment 3 for the Machine Learning course.

---

## 📊 Tasks Implemented
- **Task A – Logistic Regression**
  - Gradient Descent implementation (scratch)
  - `sklearn.linear_model.LogisticRegression`
- **Task B – Nearest Centroid Classifier (NCC)**
  - Custom scratch version
  - `sklearn.neighbors.NearestCentroid`
- **Task C – k-Nearest Neighbors (k-NN)**
  - Custom scratch version with best `k`
  - `sklearn.neighbors.KNeighborsClassifier`
- **Task D – Perceptron**
  - Scratch implementation (Mathematical Perceptron)
  - `sklearn.linear_model.Perceptron`
- **Task E – Final Comparison**
  - Accuracy, Precision, Recall, F1-score
  - Training & testing time comparison

---

## 📈 Results
The methods were evaluated on the same dataset and splits.  
A summary table is included in the report (`.docx`) and notebook (`.ipynb`).

| Method | Accuracy | Precision | Recall | F1 | Train Time (s) | Test Time (s) |
|--------|----------|-----------|--------|----|----------------|---------------|
| Logistic (scratch GD) | 0.7675 | 0.7824 | 0.7860 | 0.7842 | 8.93 | 0.0002 |
| Logistic (sklearn)    | 0.7750 | 0.7778 | 0.8140 | 0.7955 | 1.40 | 0.0004 |
| NCC (scratch)         | 0.7525 | 0.7544 | 0.8000 | 0.7765 | 0.002 | 0.0084 |
| NCC (sklearn)         | 0.7525 | 0.7544 | 0.8000 | 0.7765 | 0.001 | 0.0006 |
| k-NN (scratch, k=9)   | 0.9200 | 0.9178 | 0.9349 | 0.9263 | ~0   | 0.114 |
| k-NN (sklearn, k=9)   | 0.9200 | 0.9178 | 0.9349 | 0.9263 | 0.002 | 0.031 |
| Perceptron (scratch)  | 0.9400 | 0.9125 | 0.9733 | 0.9419 | 5.42 | 0.00004 |
| Perceptron (sklearn)  | 0.9600 | 0.9367 | 0.9867 | 0.9610 | 0.004 | 0.0002 |

---
# Lab Assignment 3 – Machine Learning Models

## 📌 Overview
This repository contains the implementation of **Lab 3** for the Data Mining & Decision Support course.  
The notebook demonstrates the application of different **machine learning algorithms** on datasets, including training, evaluation, and comparison.

## 📝 Tasks
### Task 1
- Implementation of the first model/method (e.g., preprocessing, simple model).  

### Task 2
- Implementation of the second model/method with evaluation metrics.  

### Task 3
- Advanced analysis (e.g., Linear Discriminant Analysis, comparison, robustness testing).  

