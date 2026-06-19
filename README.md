# Rainfall_Prediction_ML
Machine Learning project for rainfall prediction using weather data, feature engineering, GridSearchCV, and classification models.

# Rainfall Prediction Classifier

## Overview

This project develops a machine learning classifier to predict whether it will rain the next day using historical Australian weather data. The project includes data preprocessing, feature engineering, model optimization, and performance evaluation using multiple classification algorithms.

## Dataset

The project uses the Australian Weather Dataset, which contains meteorological observations such as temperature, humidity, pressure, wind conditions, and rainfall records collected from various locations in Australia.

## Objectives

* Predict rainfall occurrence for the next day.
* Perform feature engineering on real-world weather data.
* Build and optimize machine learning classification models.
* Compare model performance using evaluation metrics.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn

## Machine Learning Workflow

### Data Preprocessing

* Removed missing values.
* Selected weather stations from Melbourne, Melbourne Airport, and Watsonia.
* Converted date information into seasonal categories.
* Encoded categorical features and scaled numerical variables.

### Feature Engineering

* Created a new **Season** feature from the date column.
* Applied One-Hot Encoding to categorical variables.
* Standardized numerical features using StandardScaler.

### Model Development

* Random Forest Classifier
* Logistic Regression

### Model Optimization

* Hyperparameter tuning using GridSearchCV.
* Cross-validation for robust model selection.

### Evaluation

* Classification Report
* Confusion Matrix
* Accuracy Score
* Feature Importance Analysis

## Key Learning Outcomes

* Data preprocessing and feature engineering
* Building machine learning pipelines
* Hyperparameter tuning with GridSearchCV
* Classification model evaluation
* Feature importance interpretation

## Future Improvements

* Experiment with XGBoost and Gradient Boosting models.
* Deploy the model using Streamlit.
* Improve performance through advanced feature engineering.
