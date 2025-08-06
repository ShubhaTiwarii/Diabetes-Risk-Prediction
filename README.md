# Diabetes Risk Prediction

A machine learning project that predicts diabetes risk based on patient symptoms and characteristics using multiple classification algorithms.

## Dataset Overview

The dataset contains **520 patient records** with 16 features including:
- **Demographics**: Age, Gender
- **Key Symptoms**: Polyuria (excessive urination), Polydipsia (excessive thirst)
- **Other Indicators**: Sudden weight loss, weakness, visual blurring, genital thrush, and more

## Key Features

- **Data Preprocessing**: Label encoding for categorical variables and standard scaling
- **Exploratory Data Analysis**: Correlation analysis and feature importance visualization
- **Multiple Model Comparison**: Testing 6 different classification algorithms
- **Performance Metrics**: Precision, Recall, ROC AUC, and F1-Score evaluation

## Models Tested

| Model | Training Accuracy | Testing Accuracy | F1-Score |
|-------|------------------|------------------|----------|
| **Random Forest** | 100% | **98.08%** | **0.984** |
| XGBoost | 100% | 95.51% | 0.961 |
| SVC | 99.18% | 94.87% | 0.967 |
| Logistic Regression | 95.05% | 89.74% | 0.955 |
| Linear SVC | 95.05% | 89.74% | - |
| Decision Tree | 96.70% | 88.46% | 0.800 |

## Key Findings

- **Best Model**: Random Forest Classifier achieved the highest accuracy (98.08%)
- **Most Important Features**: 
  - Polydipsia (excessive thirst) - 17.5% importance
  - Polyuria (excessive urination) - 12.5% importance
  - Gender - 6.09% importance
- **Strong Correlation**: Polyuria and Polydipsia show high correlation, which aligns with diabetes symptoms


## Results

The Random Forest model demonstrates excellent performance with:
- **Precision**: 98.95%
- **Recall**: 97.92%
- **ROC AUC**: 98.12%
- **F1-Score**: 98.43%
Polydipsia (excessive thirst) and Polyuria (excessive urine production by the body) are the most
important features.  

This model can effectively assist healthcare professionals in early diabetes risk assessment based on patient symptoms.
