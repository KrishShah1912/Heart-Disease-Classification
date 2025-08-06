# Heart Disease Classification – Using Machine Learning

This project presents a complete machine learning pipeline for predicting heart disease using clinical data. It demonstrates data preprocessing, exploratory analysis, model training, hyperparameter tuning, and performance evaluation—all wrapped in a clean, reproducible workflow.

# Project Highlights
1. Dataset: UCI Heart Disease dataset (processed version)
2. Goal: Binary classification to predict presence of heart disease
3. Tech Stack: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
4. Modeling Techniques: Logistic Regression, Random Forest, Decision Tree, KNN, SVM
5. Evaluation Metrics: Accuracy, Precision, Recall, F1 Score, ROC-AUC

# Workflow Overview

1. Data Loading & Inspection
   * Read CSV data
   * Check for nulls, data types, and basic statistics
2. Exploratory Data Analysis (EDA)
   * Visualize distributions and correlations
   * Identify key features influencing heart disease 
4. Preprocessing
   * Label encoding for categorical features
   * Feature scaling using StandardScaler
5. Model Training
   * Train multiple classifiers
   * Compare performance using cross-validation
6. Hyperparameter Tuning
   * GridSearchCV for optimal parameters
   * Final model selection based on ROC-AUC
7. Model Evaluation
   * Confusion matrix, classification report
   * ROC curve visualization


# Results:
  ✅ Model Accuracy: 88.5%
