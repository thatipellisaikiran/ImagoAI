# Assignment for ImagoAI

Overview
This project involves processing hyperspectral imaging data, performing dimensionality reduction, and developing a machine learning model to predict mycotoxin levels (DON concentration) in corn samples. The model utilizes several regression models for accurate predictions.

Dataset Description
The dataset contains spectral reflectance values across multiple wavelength bands for corn samples. The key columns include:

hsi_id: Unique identifier for each sample.

Spectral features: Reflectance values across various wavelength bands.

mycotoxin_levels: Target variable (DON concentration).

Features Implemented
Data Preprocessing
Handling missing values (imputation with median values)

Feature normalization using StandardScaler

Principal Component Analysis (PCA) for dimensionality reduction

Model Training & Optimization
Use of Neural Network, Decision Tree Regression, Gradient Bossting Regression, XGBoost regression model

Hyperparameter tuning (learning rate, max depth, subsampling, etc.)

Early stopping to prevent overfitting

Evaluation & Visualization
Metrics: MAE, RMSE, and R² score

Scatter plot for actual vs. predicted values
