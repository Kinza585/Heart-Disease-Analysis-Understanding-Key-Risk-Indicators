# Heart Disease Analysis

## Overview

Heart disease is one of the leading causes of death worldwide. This project aims to analyze heart disease data to identify key risk factors and their correlations. By exploring patterns in health metrics like cholesterol levels, blood pressure, and patient demographics, we strive to provide insights for early detection and prevention of heart disease.

## Problem Statement

The project focuses on understanding the relationships between various health indicators and heart disease. By analyzing these patterns, we can help in formulating strategies for better diagnosis and prevention.

## Dataset

The dataset used for this analysis is publicly available on Kaggle:
[Heart Disease Data](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data)

- **Records**: 303
- **Attributes**: 14, including demographics, medical test results, and a target variable indicating heart disease presence.

## Exploratory Data Analysis (EDA)

Key questions explored in this project:

1. **General Information**
   - How many rows and columns are in the dataset?
   - Are there any missing values?

2. **Target Variable Analysis**
   - What is the distribution of the target variable (heart disease presence: 0 or 1)?
   - How many patients have heart disease vs. those who don't?

3. **Demographic Insights**
   - Age range of patients.
   - Gender distribution.

4. **Health Metrics**
   - Average and median values for:
     - Resting blood pressure (`trestbps`).
     - Serum cholesterol (`chol`).
     - Maximum heart rate (`thalach`).

5. **Categorical Features**
   - Counts of patients with exercise-induced angina (`exang`).
   - Distribution of chest pain types (`cp`).

6. **Visual Analysis**
   - Age distribution of patients.
   - Comparison of average cholesterol levels for patients with and without heart disease.

7. **Outlier Detection**
   - Identification of outliers in cholesterol (`chol`) and resting blood pressure (`trestbps`).

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

