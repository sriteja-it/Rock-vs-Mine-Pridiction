# Rock vs. Mine Prediction

The **"Rock vs. Mine Prediction"** project focuses on predicting whether an underwater object is a **rock** or a **mine** using Machine Learning techniques. By leveraging powerful Python libraries such as **NumPy**, **Pandas**, **Scikit-learn**, and **Logistic Regression**, this project provides an end-to-end solution for accurate underwater object classification.

---

# Project Overview

The objective of this project is to build a Machine Learning model capable of accurately identifying underwater objects as either rocks or mines using SONAR signal data. This classification problem has important applications in:

- Marine Exploration
- Naval Defense Systems
- Underwater Surveillance
- SONAR Signal Detection

Using carefully processed sonar data and machine learning algorithms, this project demonstrates how predictive models can solve real-world classification problems effectively.

---

# Key Features

## Data Collection and Processing

The project uses the famous **SONAR dataset**, which contains numerical features representing sonar signals reflected from underwater objects. Using **Pandas** and **NumPy**, the data is cleaned, processed, and prepared for model training.

---

## Data Visualization

Visualization techniques are used to better understand the dataset and feature relationships. Using libraries such as **Matplotlib**, the project can generate:

- Histograms
- Scatter Plots
- Correlation Analysis
- Feature Distribution Graphs

These visualizations help improve data understanding and feature analysis.

---

## Train-Test Split

To evaluate the Machine Learning model properly, the dataset is divided into:

- Training Data
- Testing Data

This ensures that the model is tested on unseen data and provides a realistic measure of performance.

---

## Logistic Regression Model

The project uses **Logistic Regression**, a supervised learning algorithm suitable for binary classification tasks. Since the output contains only two classes:

- Rock (R)
- Mine (M)

Logistic Regression works efficiently for this prediction system.

---

## Model Evaluation

The performance of the model is evaluated using different evaluation metrics such as:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix

These metrics help analyze how effectively the model classifies rocks and mines.

---

# Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook / Google Colab

---

# Dataset Information

The dataset contains SONAR signals bounced off different surfaces.

| Label | Meaning |
|-------|----------|
| R | Rock |
| M | Mine |

### Dataset Features

- 60 numerical input features
- 1 output label
- Real-world SONAR frequency data

Dataset Source:  
https://archive.ics.uci.edu/ml/datasets/connectionist+bench+(sonar,+mines+vs.+rocks)

---

# Getting Started

To run this project locally, follow these steps:

## 1. Clone the Repository

```bash
https://github.com/sriteja-it/Rock-vs-Mine-Pridiction
