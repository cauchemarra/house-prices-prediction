# Project Name: House Price Prediction

## Project Overview
This project focuses on predicting house prices using machine learning models.
The main goal is to build an accurate regression model and explore different preprocessing and feature engineering techniques.

Dataset: Kaggle "House Prices: Advanced Regression Techniques".

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## Project Pipeline

1. Data Exploration (EDA)
2. Data Cleaning and Missing Values Handling
3. Feature Engineering
4. Encoding Categorical Variables
5. Train/Test Split
6. Baseline Model (Linear Regression)
7. Regularization (Ridge Regression with Cross-Validation)
8. Model Evaluation (MAE, RMSE)

## Models

- Linear Regression (Baseline)
- Ridge Regression (with Cross-Validation)

Target variable was log-transformed to improve model performance.

## Results

| Model            | MAE    | RMSE   |
|------------------|--------|--------|
| Baseline Linear  | ~18k   | ~26k   |
| Ridge + Log      | ~13.8k | ~19k   |

The log transformation and regularization improved performance by ~25%.
