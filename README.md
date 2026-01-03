# Research-Project
This project implements and compares multiple machine learning and deep learning models for disease prediction using clinical data. Models including Logistic Regression, Naive Bayes, SVM, KNN, Decision Tree, Random Forest, ANN, and XGBoost were evaluated using accuracy and ROC-AUC metrics. 

🩺 Disease Prediction using Machine Learning
📌 Overview

This repository contains a comprehensive machine learning–based framework for disease prediction using structured clinical data. The project explores and compares multiple classical machine learning models and a deep learning model to analyze their effectiveness in predicting the presence of disease. The primary goal is to build reproducible, well-evaluated models suitable for healthcare-related research and academic publication.

🎯 Objectives

To implement and compare various supervised machine learning algorithms for disease prediction

To analyze model performance using appropriate evaluation metrics

To study the challenges associated with clinical prediction tasks

To provide a reproducible pipeline for healthcare machine learning research

🧠 Models Implemented

The following models have been implemented and evaluated:

Logistic Regression (Baseline Model)

Naive Bayes

Support Vector Machine (Linear Kernel)

K-Nearest Neighbors (KNN)

Decision Tree

Random Forest

Artificial Neural Network (ANN)

XGBoost (Extreme Gradient Boosting)

Both traditional machine learning models and a neural network–based approach are included to provide a broad comparative analysis.

⚙️ Methodology
1. Data Preprocessing

Removal of irrelevant features (e.g., ID column)

Train–test split with stratification

Feature standardization using StandardScaler

2. Model Training

Models were trained using standardized features

PCA was applied selectively for models sensitive to high dimensionality (e.g., SVM, KNN)

Tree-based models and ANN were trained without PCA

3. Evaluation Metrics

The following metrics were used for performance evaluation:

Accuracy

ROC–AUC (primary metric for medical prediction tasks)

ROC–AUC was prioritized due to its threshold-independent nature and suitability for imbalanced clinical datasets.

📊 Results Summary

Experimental results show that advanced models such as ANN and XGBoost achieve strong discriminative performance with ROC–AUC values close to 0.80. While overall accuracy remains moderate (around 70–75%), this reflects the inherent complexity and overlap present in real-world clinical data. The results are consistent with findings reported in existing medical machine learning literature.

📈 Visualization

The repository includes visualization code for:

Model accuracy comparison charts

ROC curves

Confusion matrices (optional)

These visualizations support clear interpretation and comparison of model performance.
