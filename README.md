# Assignment for ImagoAI

# Overview
This project involves processing hyperspectral imaging data, performing dimensionality reduction, and developing a machine learning model to predict mycotoxin levels (DON concentration) in corn samples. The model utilizes several regression models for accurate predictions.

# Dataset Description
The dataset contains spectral reflectance values across multiple wavelength bands for corn samples. The key columns include:

hsi_id: Unique identifier for each sample.

Spectral features: Reflectance values across various wavelength bands.

mycotoxin_levels: Target variable (DON concentration).

# Features Implemented
1)Data Preprocessing

2)Handling missing values (imputation with median values)

3)Feature normalization using StandardScaler

4)Principal Component Analysis (PCA) for dimensionality reduction

# Model Training & Optimization
1)Use of Neural Network, Decision Tree Regression, Gradient Bossting Regression, XGBoost regression model

2)Hyperparameter tuning (learning rate, max depth, subsampling, etc.)

3)Early stopping to prevent overfitting

# Evaluation & Visualization
1)Metrics: MAE, RMSE, and R² score

2)Scatter plot for actual vs. predicted values
