# Algerian Forest Fire FWI Prediction

## Project Overview

This project focuses on predicting the Fire Weather Index (FWI) using the Algerian Forest Fire dataset. The objective of this project is to analyze environmental and weather-related factors and build a machine learning model capable of predicting the Fire Weather Index.

## Project Workflow

The project was completed following a complete machine learning pipeline:

* Data Collection and Understanding
* Exploratory Data Analysis (EDA)
* Data Cleaning and Preprocessing
* Feature Engineering
* Feature Scaling using StandardScaler
* Train-Test Split
* Model Training and Evaluation

## Machine Learning Models Used

During model development, the following regression algorithms were implemented and evaluated:

* Linear Regression
* Ridge Regression
* Lasso Regression

To improve model performance and select the optimal regularization parameter, cross-validation techniques were applied using:

* LassoCV (Cross Validation)

## Model Evaluation

The models were evaluated using standard regression metrics such as:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score

Based on the evaluation results, the best-performing model was selected and saved using Pickle for deployment.

## Web Application Development

After model training, a web application was developed using Flask. The application allows users to enter weather-related parameters and obtain the predicted Fire Weather Index in real time.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Flask
* HTML & CSS
* Pickle

## Project Outcome

Successfully built an end-to-end Machine Learning application that performs Fire Weather Index prediction and provides predictions through a user-friendly Flask web interface.

## AUTHOR
PRINCE KUMAR 
AI/ML ENTHUSIAST
