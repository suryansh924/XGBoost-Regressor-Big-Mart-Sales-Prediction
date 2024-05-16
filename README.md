# BigMart Sales Prediction Project using XGBoost Regressor Model

Project <a href = "https://colab.research.google.com/drive/1GKipCIVODA3qhw09WnhQeJLmIkGeLCmf?usp=sharing">link</a> to collab: 

## Overview
This project aims to predict the sales of BigMart outlets using machine learning techniques. We start by performing Exploratory Data Analysis (EDA) to understand the characteristics of the dataset. Then, we preprocess the data to prepare it for model training. Finally, we train an XGBoost regressor to predict sales and evaluate its performance.

## Data Collection and Processing
- Load the dataset (`train.csv`) and examine its information using `info()` method.
- Check for missing values in the dataset using `isnull().sum()` method.
- Handle missing values appropriately.

## Data Analysis
### Numerical Features
- Analyze numerical features to understand their distributions and relationships with the target variable (sales).

### Categorical Features
- Examine categorical features to identify unique categories and their impact on sales.

## Data Pre-Processing
- Perform data pre-processing steps such as handling categorical variables, feature scaling, and encoding categorical variables.

## Model Training
- Split the dataset into training and testing sets using `train_test_split`.
- Train an XGBoost regressor model on the training data.

## Evaluation
- Predict sales on both training and testing datasets.
- Evaluate the model's performance using the R-squared metric.
- Provide a summary of the model's performance on both training and testing data.

## Summary
In this project, we developed a machine learning model to predict the sales of BigMart outlets. We started with data collection and processing, followed by exploratory data analysis to understand the dataset's characteristics. After data pre-processing, we trained an XGBoost regressor model and evaluated its performance. The model achieved an R-squared score of *`0.63`* on the training data and *`0.59`* on the testing data, indicating moderate predictive accuracy.
