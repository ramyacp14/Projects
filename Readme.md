# Sales Prediction Project

This project focuses on predicting future sales for a retail company using time series analysis and the Facebook Prophet library.

## Project Overview

The project analyzes sales data from multiple stores and aims to forecast future sales. It includes data preprocessing, exploratory data analysis, and time series forecasting using Facebook Prophet.

## Data Sources

The project uses two main datasets:
1. `train.csv`: Contains daily sales data for multiple stores
2. `store.csv`: Contains additional information about each store

## Key Features

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA) with visualizations
- Time series forecasting using Facebook Prophet
- Incorporation of holiday effects in the forecast

## Requirements

- Python 3.6+
- pandas
- numpy
- matplotlib
- seaborn
- fbprophet

## Usage

1. Mount your Google Drive (if using Google Colab)
2. Import the required libraries
3. Load and preprocess the data
4. Perform EDA
5. Train the Prophet model
6. Make predictions and visualize results

## Main Functions

- `sales_prediction(Store_ID, sales_df, holidays, periods)`: Generates sales predictions for a specific store

## Future Improvements

- Fine-tune the Prophet model parameters
- Incorporate additional external factors that might affect sales
- Implement cross-validation for model evaluation
- Extend the analysis to include all stores in the dataset
