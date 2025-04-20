# Diabetes Readmission Prediction

This repository contains a full machine learning pipeline for predicting hospital readmissions among diabetic patients. Using the Diabetes 130-US hospitals dataset, the project covers everything from data exploration and preprocessing to model building, evaluation, and visualization.

## Overview

Hospital readmissions are a key indicator of healthcare quality and cost. By predicting which diabetic patients are at high risk of readmission, hospitals can better manage resources and patient care.

This project aims to:
- Analyze patterns in diabetic patient records
- Build classification models to predict readmissions
- Evaluate model performance using relevant metrics

## Project Links

- **Medium Article**: [Hospital Readmission Prediction for Diabetic Patients](#)
- **Jupyter Notebook**: `diabetes-readmission.ipynb`

## Project Features

### 1. Data Exploration and Cleaning
- Detailed inspection of missing values, outliers, and data types
- Class distribution analysis for readmission outcomes
- Encoding of categorical variables and dropping irrelevant features

### 2. Exploratory Data Analysis (EDA)
- Visualizations to examine relationships between features and readmission
- Count plots, heatmaps, boxplots, and distribution charts
- Identified high-impact features such as number of procedures, length of stay, and number of medications

### 3. Machine Learning Models
- **Logistic Regression**
- **Random Forest**
- **XGBoost**
- **Support Vector Machine**
- Evaluation via:
  - Accuracy
  - Precision, Recall, F1-Score
  - ROC-AUC and PR-AUC curves

### 4. Model Insights
- Compared model performance across metrics
- Interpreted feature importance from ensemble models
- Visualized confusion matrices for real-world understanding

## Dataset

- **Source**: UCI Machine Learning Repository – [Diabetes 130-US hospitals](https://archive.ics.uci.edu/ml/datasets/diabetes+130-us+hospitals+for+years+1999-2008)
- **Records**: ~100,000 encounters
- **Features**: Demographics, lab tests, medications, diagnoses, hospital encounters
- **Target**: Readmission status (`<30`, `>30`, `NO`) — converted into binary classification

## Technologies Used

- **Python**
- **Libraries**:
  - `pandas`, `numpy`, `scikit-learn`, `xgboost`
  - `matplotlib`, `seaborn`
- **Tools**:
  - Jupyter Notebook
  - Git & GitHub for version control
  - Medium for blog publication

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/diabetes-readmission.git
