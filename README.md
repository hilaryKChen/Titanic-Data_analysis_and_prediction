# Titanic-Data_analysis_and_prediction
[titanic_data_analysis](/titanic_data_analysis.ipynb)

## Overview
This project involves analyzing and predicting survival outcomes for passengers aboard the Titanic using machine learning techniques. The work is divided into two main parts:

### Part A: Data Pre-processing and Exploratory Analysis
1. **Importing and Exploring Data**: The dataset `titanic-train.csv` is loaded and analyzed for missing values and feature distributions.
2. **Cleaning Data**: Missing values are handled using statistical methods such as median and mode imputation.
3. **Feature Engineering**: New features like `Family` are created, and redundant features are dropped.
4. **Data Transformation**: Features are transformed into categorical or numerical formats suitable for machine learning models.
5. **Statistical and Graphical Analysis**: Survival rates are analyzed based on features like `Sex`, `Pclass`, `Age`, `Fare`, and `Family`.

### Part B: Data Prediction using Machine Learning
1. **Model Training**: A neural network is built using Keras and trained on the preprocessed training data.
2. **Testing Data Preparation**: The dataset `titanic-test.csv` is preprocessed similarly to the training data.
3. **Prediction**: The trained neural network predicts survival outcomes for the test data, and results are saved to csv file.

## Key Observations
- Female passengers and those in higher classes had significantly higher survival rates.
- Passengers with small families and higher ticket fares were more likely to survive.
- Age played a critical role, with younger passengers having better survival chances.

