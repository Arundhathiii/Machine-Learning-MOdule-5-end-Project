# Car Price Prediction Model

## Overview

This project aims to develop a predictive model to estimate car prices based on various features such as engine size, curb weight, horsepower, and more. The model uses a Random Forest Regressor algorithm and is trained on a dataset of cars.

## Dataset

The dataset used for this project can be found https://drive.google.com/file/d/1FHmYNLs9v0Enc-UExEMpitOFGsWvB2dP/view?usp=drive_link.

## Model Development

The following steps were taken to develop the model:

1. Data preprocessing: The dataset was cleaned and preprocessed by handling missing values and encoding categorical variables.
2. Feature selection: The most relevant features were selected using feature importance scores.
3. Model training: A Random Forest Regressor model was trained on the preprocessed data.
4. Hyperparameter tuning: Hyperparameter tuning was performed using GridSearchCV to optimize the model's performance.

## Results

The model achieved an R-squared value of 0.955 on the test data. However, after hyperparameter tuning, the model's performance decreased slightly, achieving an R-squared value of 0.8842.
