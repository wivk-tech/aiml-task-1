# Titanic Dataset - Data Cleaning & Preprocessing

## Overview
This task was part of an AI & ML Internship. The goal was to clean and preprocess the Titanic dataset.

## Key Steps
1. Loaded and explored the dataset.
2. Handled missing values:
   - Used median for `Age`, mode for `Embarked`.
   - Dropped `Cabin` due to too many nulls.
3. Encoded categorical variables:
   - Label encoded `Sex`, one-hot encoded `Embarked`.
4. Standardized `Age` and `Fare` using `StandardScaler`.
5. Visualized and removed outliers using boxplots and IQR method.
6. Saved the cleaned dataset for future modeling.

## Tools Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## Author
Vishwajeet Kumar
