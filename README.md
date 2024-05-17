# Project-3-HDB-Resale-Price-Prediction

## Overview
This project aims to predict the resale prices of HDB flats in Singapore using machine learning models. The models used in this project are:

- Gradient Boosting Regressor
- Neural Network
- Random Forest Regressor

The goal is to provide accurate predictions to assist buyers, sellers, and policymakers in making informed decisions.

## Requirements
- pandas
- numpy
- scikit-learn
- tensorflow (for neural network)
- matplotlib (for visualization)

## Data Preprocessing
### Load the Dataset:
Load the HDB resale transaction data into a pandas DataFrame.

### Convert 'month' to Datetime Format:
Convert the 'month' column to datetime format to enable time-based analysis and feature extraction.

### Calculate Total Remaining Lease:
Transform the 'remaining_lease' column into a single numerical format representing the total number of months.

### Extract 'Year' and 'Month_num' from 'month':
Extract the year and month from the 'month' column to use as features.

### Identify and Preprocess Categorical and Numerical Columns:
Use ColumnTransformer to apply standard scaling to numerical columns and one-hot encoding to categorical columns.
