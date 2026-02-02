Task 11: SVM – Breast Cancer Classification
 Overview

This project implements Support Vector Machine (SVM) models to classify breast cancer tumors as malignant or benign using the Sklearn Breast Cancer dataset.
The task focuses on kernel-based classification, feature scaling, hyperparameter tuning, and model evaluation.

 Objective

Understand how SVM works with different kernels

Compare Linear and RBF kernels

Perform hyperparameter tuning using GridSearchCV

Evaluate model performance using standard metrics

Save the trained model for reuse

 Dataset

Primary Dataset: sklearn.datasets.load_breast_cancer()

Samples: 569

Features: 30 numerical features

Target Classes:

0 → Malignant

1 → Benign

 No external dataset upload required
 No Kaggle API needed

 Tools & Libraries Used

Python

Scikit-learn

NumPy

Pandas

Matplotlib

Joblib

Workflow

Load the Breast Cancer dataset from sklearn

Inspect feature matrix and target distribution

Split data into training and testing sets

Apply StandardScaler for feature normalization

Train Linear SVM and evaluate accuracy

Train RBF SVM and compare performance

Tune C and gamma using GridSearchCV

Evaluate best model using:

Confusion Matrix

Classification Report

ROC Curve & AUC score

Save the trained pipeline model

 Model Evaluation Metrics

Accuracy Score

Confusion Matrix

Precision, Recall, F1-Score

ROC Curve

AUC Score