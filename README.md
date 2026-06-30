# Bengaluru House Price Prediction

A machine learning project that predicts house prices in Bengaluru using regression models.

## Project Overview
This project uses the Bengaluru house dataset to build a predictive model for estimating house prices based on features like:
- Location
- Square feet area
- Number of bathrooms
- Number of bedrooms (BHK)

We compare two models:
- Linear Regression
- Ridge Regression

## Dataset
- Source: Kaggle (Bengaluru House Data)
- Contains features like location, total_sqft, size, bath, balcony, and price

## Workflow

1. Load dataset
2. Handle missing values
3. Remove unnecessary columns
4. Clean and transform features (size → bhk, sqft conversion)
5. Encode categorical data (location)
6. Split dataset into train and test sets
7. Train models:
   - Linear Regression
   - Ridge Regression
8. Evaluate using:
   - RMSE (Root Mean Squared Error)
   - R² Score

## Results

- Linear Regression and Ridge Regression are compared based on error and accuracy.
- Ridge Regression helps reduce overfitting in high-dimensional data.

## Key Learnings

- Data cleaning and preprocessing
- Handling missing values
- Feature encoding (One-Hot Encoding)
- Regression models in machine learning
- Model evaluation techniques (RMSE & R²)

