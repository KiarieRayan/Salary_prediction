# Salary Prediction Model

This repository contains a machine learning model for predicting salaries based on years of experience. The model uses linear regression and is built using Scikit-learn.

## Model Overview

The model is designed to predict salaries (`Salary`) based on years of experience (`YearsExperience`). It utilizes a standard linear regression algorithm and incorporates feature scaling to improve performance.

## Performance Metrics

The model has been evaluated on a test dataset, and the following performance metrics were obtained:

- **Mean Squared Error (MSE)**: `49,830,096.86`
  - Indicates the average squared difference between predicted and actual values. Lower values represent better model performance.

- **Root Mean Squared Error (RMSE)**: `7,059.04`
  - Provides a measure of the average prediction error in the same units as the target variable (`Salary`). This value represents the average deviation of predictions from actual values.

- **Mean Absolute Error (MAE)**: `6,286.45`
  - Measures the average absolute deviation of predictions from actual values. It is less sensitive to outliers compared to MSE.

- **R-squared (R²)**: `0.902`
  - Indicates that approximately 90.2% of the variance in the `Salary` can be explained by the model. A higher R² value signifies a better fit.

## Getting Started

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/salary_prediction.git
   cd salary_prediction
