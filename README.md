# STT-890-Introduction_to_MLOps

# Linear Regression Models - MLOps Homework

## Overview
This repository contains two linear regression models built using `scikit-learn`. The models are trained on the `sampregdata.csv` dataset. 

- **Model 1**: Trained using a single feature (`X1`).
- **Model 2**: Trained using two features (`X1` and `X2`).

## Model Comparison
Below are the evaluation metrics for both models:

| Metric               | Model 1 (X1)  | Model 2 (X1, X2) |
|----------------------|--------------|------------------|
| **Mean Absolute Error (MAE)** | 8.3164  | 6.8719  |
| **Mean Squared Error (MSE)**  | 105.5182 | 72.7738  |
| **R² Score**          | -0.0043      | 0.3074   |

## Interpretation
- Model 2, which uses both `X1` and `X2`, performs better than Model 1.
- The **Mean Absolute Error (MAE)** and **Mean Squared Error (MSE)** are lower for Model 2, indicating better predictive accuracy.
- The **R² Score** for Model 2 is **0.3074**, showing that it explains about 30.7% of the variance in the data, whereas Model 1 has an **R² Score** close to 0, meaning it does not explain the variance well.

## Repository Organization
- `hw1_data/sampregdata.csv` - Dataset
- `models/linear_regression_model_1.pkl` - Trained Model 1 (X1)
- `models/linear_regression_model_2.pkl` - Trained Model 2 (X1, X2)
- `hw1.ipynb` - Notebook with code for training and evaluation
- `README.md` - Project documentation

## Version Control
- The repository tracks both models using Git.
- Model 1 is an earlier version, and Model 2 is the current improved version.

