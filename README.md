# Real-Estate-Price-Prediction
Machine Learning project for predicting real estate prices using Random Forest Regression, EDA, feature analysis, and Python.

## Overview
This project uses Machine Learning to predict house prices based on real estate transaction data. The model was developed using Python and Scikit-learn, following a complete machine learning workflow including data preprocessing, exploratory data analysis (EDA), model training, evaluation, and prediction.

## Dataset
The dataset contains **414 real estate records** with the following features:
* Transaction Date
* House Age
* Distance to the Nearest MRT Station
* Number of Convenience Stores
* Latitude
* Longitude

**Target Variable:**
* House Price of Unit Area

## Technologies Used
* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

## Machine Learning Workflow
* Loaded and explored the dataset.
* Performed data cleaning and validation.
* Conducted Exploratory Data Analysis (EDA).
* Selected relevant features for prediction.
* Split the dataset into training and testing sets.
* Trained a Random Forest Regressor.
* Evaluated model performance using MAE, RMSE, and R² Score.
* Predicted house prices for new property data.
* Analyzed feature importance to understand the factors influencing house prices.

## Model

**Random Forest Regressor**

## Evaluation Metrics
* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

## Project Structure
Real-Estate-Price-Prediction/
│── Realestate.csv
│── real_estate_prediction.py
│── README.md

## Results
The trained Random Forest Regression model successfully predicts house prices using property and location-related features. Model performance was evaluated using standard regression metrics to assess prediction accuracy.

## Future Improvements
* Hyperparameter tuning for improved performance.
* Compare additional regression models such as Linear Regression and XGBoost.
* Build a Streamlit web application for interactive predictions.
* Deploy the model for real-world use.

 ## Dataset
The dataset used in this project was obtained from Kaggle.


