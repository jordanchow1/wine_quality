# wine_quality

## Overview
This project analyzes a dataset containing information on different wine samples, aiming to predict wine quality based on various physicochemical properties.

## Dataset
The dataset used in this analysis contains chemical properties of red and white wines, along with quality scores assigned by wine tasters. The goal is to understand the relationship between these features and wine quality.

## Features
The dataset includes the following attributes:
- **Fixed acidity**
- **Volatile acidity**
- **Citric acid**
- **Residual sugar**
- **Chlorides**
- **Free sulfur dioxide**
- **Total sulfur dioxide**
- **Density**
- **pH**
- **Sulphates**
- **Alcohol**
- **Quality (on a scale of 1 - 10)** (target variable)

## Analysis Steps
The notebook follows these key steps:
1. **Data Preprocessing**: Handling missing values, data cleaning, and feature selection.
2. **Exploratory Data Analysis (EDA)**: Visualizing relationships between features and wine quality.
3. **Feature Engineering**: Transforming data for better model performance.
4. **Model Training**: Applying machine learning models to predict wine quality.
5. **Model Evaluation**: Assessing performance using metrics like accuracy and F1-score.

## Classifiers
1. Random Forest Classifier
2. Logistic Regression

## Results
The Random Forest Classifier outperforms the logistic classifier, having an accuracy score of 0.67 (67% accuracy rate) and an f1 score of 0.38 (poor performance).
