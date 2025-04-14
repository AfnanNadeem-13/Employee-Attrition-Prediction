# Employee Attrition Prediction

## Overview
This project aims to predict employee attrition based on various factors using machine learning models. The dataset used is the IBM HR Analytics dataset, and several classification models, such as Logistic Regression and Random Forest, are implemented to predict whether an employee will leave the company.

## Objective
The objective of this project is to build a predictive model that can help organizations predict employee attrition and take proactive measures to retain valuable employees.

## Dataset
The dataset used is the **IBM HR Analytics Employee Attrition & Performance** dataset, which contains several features that impact an employee's likelihood of attrition, such as age, work environment satisfaction, and job role.

## Project Steps
1. **Data Preprocessing**: Cleaning and transforming the dataset for use in machine learning models.
2. **Model Training**: Training various models like Logistic Regression and Random Forest.
3. **Model Evaluation**: Evaluating the models using classification metrics such as accuracy, precision, recall, F1-score, and confusion matrix.
4. **Interpretation**: Using SHAP for model interpretation and explaining the impact of various features on the model's predictions.
5. **Actionable Insights**: Providing insights to HR teams on factors influencing employee attrition.

## Files
- `train_model.py`: Script for training models.
- `evaluate_model.py`: Script for evaluating model performance.
- `data_preprocessing.py`: Script for data preprocessing and feature engineering.
- `shap_interpretation.py`: Script for SHAP interpretation (if used).
- `requirements.txt`: List of dependencies used in the project.

## Installation
To run the project, you will need the following dependencies:

```bash
pip install -r requirements.txt
