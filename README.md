# Predicting Housing Prices with Linear Regression

## Overview

This repository showcases a Python implementation for forecasting housing prices using linear regression. The dataset encompasses essential features such as living area, bedroom count, bathrooms, and total rooms.

## Organized File Structure

- **Data Directory**: Contains both the dataset (`train.csv`) and the test dataset (`test.csv`).
- **PRODIGY_ML_01.ipynb Notebook**: Jupyter notebook housing the primary code for data analysis, model training, and predictions.
- **README.md Guide**: A succinct guide for understanding the code.

## Usage Instructions

1. **Libraries Installation**: Install required Python libraries - pandas, seaborn, matplotlib, numpy, scipy, and scikit-learn.
2. **Execution Steps**: Execute the Jupyter notebook [`PRODIGY_ML_01.ipynb`](https://github.com/dipeshbabu/PRODIGY_ML_01/blob/main/PRODIGY_ML_01.ipynb) sequentially to comprehend the analysis and model training.
3. **Predictions**: Utilize the trained model to predict house prices on the test dataset (`test.csv`), with results visually presented.

## Noteworthy Code Components

1. **Exploring Data Insights**:
   - Employ Seaborn and Matplotlib for insightful visualizations.
2. **Enhancing Model Performance through Target Variable Transformation**:
   - Log transform the target variable (`SalePrice`) for improved accuracy.
3. **Assessing Feature Normality**:
   - Utilize the Shapiro-Wilk test to evaluate feature normality.
4. **Effective Model Training**:
   - Train a linear regression model on both original and log-transformed data.
5. **Performance Metrics Evaluation**:
   - Evaluate model performance using Mean Squared Error, Root Mean Squared Error, and R2-squared.
6. **Visual Representation of Predictions**:
   - Present model predictions alongside actual prices for better comprehension.

## Results Summary

The linear regression model showcases a reasonably accurate predictive performance. Transformed sale prices enhance interpretability by reverting from the logarithmic scale.
