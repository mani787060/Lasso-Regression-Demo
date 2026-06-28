# Lasso Regression Demo

## 📌 Project Overview

This project demonstrates **Lasso Regression (L1 Regularization)** and its ability to perform **automatic feature selection** by shrinking less important feature coefficients to zero.

Using a synthetic dataset generated with Scikit-Learn's `make_regression`, the notebook explores how Lasso controls model complexity, reduces overfitting, and identifies the most relevant features for prediction.

---

## 🎯 Objectives

* Understand the fundamentals of Lasso Regression
* Learn how L1 Regularization works
* Study coefficient shrinkage and feature selection
* Analyze the impact of different alpha (λ) values
* Compare Lasso Regression with Linear and Ridge Regression

---

## 📂 Dataset

**Dataset Used:** `make_regression`

A synthetic regression dataset generated using Scikit-Learn to demonstrate regularization techniques and feature selection.

---

## 📖 Concepts Covered

* Linear Regression
* Lasso Regression
* L1 Regularization
* Feature Selection
* Coefficient Shrinkage
* Overfitting Prevention
* Alpha (Regularization Strength)
* Model Complexity Control

---

## 🛠️ Libraries Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-Learn

---

## ⚙️ Implementation Steps

### Data Preparation

* Generate regression data using `make_regression`
* Split data into training and testing sets

### Model Training

* Train a Lasso Regression model
* Experiment with different alpha values

### Coefficient Analysis

* Observe how coefficients change with increasing alpha
* Identify features whose coefficients become zero

### Model Comparison

* Compare Lasso Regression with Linear Regression
* Compare Lasso Regression with Ridge Regression

### Visualization

* Plot coefficient shrinkage
* Analyze feature selection behavior
* Visualize the effect of regularization strength

---

## 🔍 Key Observations

* Lasso Regression can reduce some coefficients exactly to zero.
* Higher alpha values lead to stronger regularization.
* Automatic feature selection helps simplify the model.
* Lasso is useful when dealing with high-dimensional datasets.

---

## ✅ Advantages

* Performs automatic feature selection
* Reduces model complexity
* Helps prevent overfitting
* Improves model interpretability
* Works well with datasets containing many features

---

## 💻 Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-Learn

---

## 🏁 Conclusion

Lasso Regression is a powerful regularization technique that not only reduces overfitting but also performs feature selection by eliminating less important variables. This project provides a practical understanding of how L1 Regularization influences model behavior and feature importance.

