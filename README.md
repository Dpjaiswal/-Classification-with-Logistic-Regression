# Classification-with-Logistic-Regression

# Overview
This project implements a logistic regression model to classify breast tumors as malignant (M) or benign (B) based on diagnostic measurements. The model achieves high accuracy in predicting tumor malignancy and includes comprehensive evaluation metrics.


# Dataset
The dataset contains features computed from digitized images of fine needle aspirates (FNA) of breast masses. Key characteristics:

569 instances (212 malignant, 357 benign) 30 numeric features (mean, standard error, and worst values of 10 measurements) Target variable: diagnosis (M = malignant, B = benign)

# Implementation Steps
Data Preparation Load and inspect the dataset Convert diagnosis to binary (M=1, B=0) Drop non-feature columns (id, Unnamed: 32) Split into training (80%) and test (20%) sets Standardize features using StandardScaler

Model Training Logistic regression with default parameters Trained on standardized features

Evaluation Metrics Confusion matrix Classification report (precision, recall, F1-score) ROC-AUC score ROC curve visualization

Threshold Analysis Precision-recall tradeoff at different thresholds F1-score optimization Visualization of performance metrics across thresholds


