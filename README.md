# wine_quality

## Overview
This project analyzes a dataset containing information on different wine samples, aiming to predict wine quality based on various physicochemical properties.

## Dataset
The dataset used in this analysis contains chemical properties of red and white wines, along with quality scores assigned by wine tasters. The goal is to understand the relationship between these features and wine quality. (https://archive.ics.uci.edu/dataset/186/wine+quality)

## Features
The dataset includes the following attributes:
- **Fixed acidity**: The amount of non-volatile acids (such as tartaric acid) in wine.
- **Volatile acidity**: The concentration of acetic acid, which can contribute to an unpleasant vinegar taste.
- **Citric acid**: A naturally occurring acid that can add freshness and flavor to wine.
- **Residual sugar**: The amount of sugar left after fermentation.
- **Chlorides**: The amount of salt in the wine.
- **Free sulfur dioxide**: The amount of SO₂ that protects wine from spoilage.
- **Total sulfur dioxide**: The total SO₂ content, including both bound and free forms.
- **Density**: The mass per unit volume, which can indicate sugar and alcohol content.
- **pH**: A measure of acidity or alkalinity.
- **Sulphates**: A wine preservative that can enhance flavor.
- **Alcohol**: The percentage of alcohol content in the wine.
- **Quality (target variable)**: A numerical rating of the wine (from 0 to 10).

## Analysis Steps
The notebook follows these key steps:
1. **Data Preprocessing**: Handling missing values, data cleaning, and feature selection.
2. **Exploratory Data Analysis (EDA)**: Visualizing relationships between features and wine quality.
3. **Feature Engineering**: Transforming data for better model performance.
4. **Model Training**: Applying machine learning models to predict wine quality.
5. **Model Evaluation**: Assessing performance using metrics including accuracy and F1-score. Confusion matrix to visualize accuracy.

## Classifiers
1. Random Forest Classifier
2. Logistic Regression

## Results
The Random Forest Classifier outperforms the logistic classifier, having an accuracy score of 0.67 (67% accuracy rate) and an f1 score of 0.38 (poor performance).
