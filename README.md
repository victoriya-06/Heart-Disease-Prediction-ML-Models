# Heart-Disease-Prediction-Using-Machine-Learning-Classification-Models

## Overview

This project predicts the likelihood of heart disease using Machine Learning and Deep Learning techniques. Multiple classification models were developed, trained, and evaluated to compare their performance on a heart disease dataset.

The project includes traditional machine learning algorithms as well as a PyTorch-based Neural Network and provides comprehensive model evaluation using various performance metrics.

---

## Objectives

* Predict the presence of heart disease using patient health attributes.
* Compare the performance of multiple machine learning models.
* Apply hyperparameter tuning to improve model performance.
* Evaluate models using standard classification metrics.
* Visualize model performance and feature importance.

---

## Dataset

The dataset contains clinical and demographic information related to patients, including:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Resting ECG
* Maximum Heart Rate
* Exercise Induced Angina
* ST Depression
* Slope
* Number of Major Vessels
* Thalassemia
* Target (Heart Disease Presence)

---

## Data Preprocessing

The following preprocessing steps were performed:

* Removed duplicate records
* Feature-target separation
* Train-test split (80:20)
* Feature standardization using StandardScaler
* Conversion of data into PyTorch tensors

---

## Models Implemented

### 1. Logistic Regression

A baseline linear classification model.

### 2. Decision Tree Classifier

Optimized using GridSearchCV.

### 3. Random Forest Classifier

Optimized using GridSearchCV and used for feature importance analysis.

### 4. PyTorch Neural Network

Architecture includes:

* Fully Connected Layers
* Batch Normalization
* ReLU Activation
* Dropout Regularization
* Early Stopping
* Learning Rate Scheduling

---

## Hyperparameter Tuning

GridSearchCV was applied to:

* Decision Tree Classifier
* Random Forest Classifier

This helped identify the best-performing parameter combinations using 5-fold cross-validation.

---

## Evaluation Metrics

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Score
* Confusion Matrix
* ROC Curve Analysis

---

## Visualizations

The project generates:

* Training and Validation Curves
* Confusion Matrices
* ROC Curve Comparison
* Model Performance Comparison
* Random Forest Feature Importance Plot

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* PyTorch

---



## Results

The models were compared using multiple evaluation metrics. The project demonstrates the effectiveness of machine learning and deep learning techniques in predicting heart disease and identifying important clinical features that contribute to predictions.

---

