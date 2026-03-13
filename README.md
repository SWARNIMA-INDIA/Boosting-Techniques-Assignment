# Boosting Techniques Assignment

## Project Overview

This project is part of a Machine Learning assignment focused on **Boosting Techniques**. Boosting is an ensemble learning method that combines multiple weak learners to create a stronger and more accurate model.

In this assignment, different boosting algorithms such as **AdaBoost, Gradient Boosting, XGBoost, and CatBoost** are studied and implemented using Python. The project includes both theoretical explanations and practical implementations using real datasets.

---

## Objectives

The main objectives of this assignment are:

* To understand the concept of **Boosting in Machine Learning**
* To learn the difference between **AdaBoost and Gradient Boosting**
* To understand **regularization in XGBoost**
* To learn how **CatBoost handles categorical data**
* To implement boosting algorithms using Python
* To evaluate machine learning models using appropriate metrics

---

## Datasets Used

### 1. Breast Cancer Dataset

This dataset is used for **classification tasks**.

Features include different measurements of cell nuclei such as radius, texture, perimeter, and area. The goal is to predict whether the tumor is **malignant or benign**.

Dataset loading function:

```python
from sklearn.datasets import load_breast_cancer
```

---

### 2. California Housing Dataset

This dataset is used for **regression tasks**.

It contains information such as median income, house age, population, and number of rooms. The goal is to **predict housing prices**.

Dataset loading function:

```python
from sklearn.datasets import fetch_california_housing
```

---

## Algorithms Implemented

### 1. AdaBoost Classifier

AdaBoost improves model performance by giving more importance to incorrectly predicted data points.

Used for:

* Breast cancer classification
* Model accuracy evaluation

---

### 2. Gradient Boosting Regressor

Gradient Boosting improves predictions by reducing the errors made by previous models.

Used for:

* California housing price prediction
* Evaluation using **R² score**

---

### 3. XGBoost Classifier

XGBoost is an advanced boosting algorithm that improves performance using optimization and regularization techniques.

Used for:

* Breast cancer classification
* Hyperparameter tuning using **GridSearchCV**

---

### 4. CatBoost Classifier

CatBoost is designed to handle categorical features efficiently and helps reduce overfitting.

Used for:

* Classification tasks
* Confusion matrix visualization

---

## Technologies Used

* Python
* Scikit-learn
* XGBoost
* CatBoost
* NumPy
* Pandas
* Matplotlib
* Seaborn

---

## Evaluation Metrics

Different evaluation metrics were used depending on the task.

For **Classification Tasks**

* Accuracy
* Confusion Matrix
* Precision
* Recall
* F1 Score

For **Regression Tasks**

* R² Score

---

## Project Structure

```
Boosting-Techniques-Assignment
│
├── boosting_assignment.ipynb
├── README.md
└── assignment_report.pdf
```

---

## Learning Outcomes

Through this project I learned:

* How boosting algorithms improve machine learning models
* Practical implementation of **AdaBoost, Gradient Boosting, XGBoost, and CatBoost**
* Model evaluation using different performance metrics
* Basic hyperparameter tuning techniques

---

## Author

**Swarnima Srivastava**

* This project was completed as part of a Machine Learning assignment on Boosting Techniques.
