# Predictive-maintenance-ML-Project
Machine learning project for predicting industrial equipment failures using sensor data.
# Predictive Maintenance using Machine Learning

## 📌 Project Overview

This project focuses on using machine learning to predict whether industrial equipment is likely to experience a failure.

Predictive maintenance can help manufacturing companies identify potential equipment failures in advance, reduce unexpected downtime, and improve maintenance planning.

The project uses sensor and machine-related data to build classification models that predict whether a machine will fail.

---

## 🎯 Objective

The main objective is to develop machine learning models that can classify equipment into:

- **0 — No Failure**
- **1 — Failure**

The project also evaluates the models using several performance metrics to understand how well they identify actual equipment failures.

---

## 📊 Dataset

The dataset contains information about industrial machines and their operating conditions.

### Main Features

- `UDI` – Unique identifier
- `Product ID` – Product identifier
- `Type` – Product type
- `Air temperature [K]` – Air temperature
- `Process temperature [K]` – Process temperature
- `Rotational speed [rpm]` – Rotational speed
- `Torque [Nm]` – Torque
- `Tool wear [min]` – Tool wear
- `Target` – Failure target
- `Failure Type` – Type of failure

The target variable is used for binary classification of machine failure.

---

## 🔍 Project Workflow

The project follows these main steps:

1. Data loading
2. Data exploration
3. Data quality checking
4. Exploratory Data Analysis (EDA)
5. Data preprocessing
6. Feature engineering
7. Train-test splitting
8. Machine learning model training
9. Hyperparameter tuning
10. Model evaluation
11. Comparison of model performance
12. Conclusions

---

## 🤖 Machine Learning

The project uses classification algorithms to predict equipment failure.

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix

Recall is particularly important because identifying actual machine failures is an important part of predictive maintenance.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📈 Results

The trained models are compared using multiple evaluation metrics rather than accuracy alone.

This provides a broader understanding of how effectively the models detect equipment failures and distinguish between failure and non-failure cases.

---

## 📁 Project Structure

```text
predictive-maintenance-ml/
│
├── predictive_maintenance.ipynb
├── README.md
└── dataset/

