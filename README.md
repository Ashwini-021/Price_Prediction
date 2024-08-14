# Random Forest Model for House Price Prediction

This notebook demonstrates the steps involved in building a Random Forest model to predict house prices using a dataset from a Kaggle competition.

## Overview

The notebook includes the following steps:

1. **Data Loading**: The dataset is loaded using pandas.
2. **Feature Selection**: Relevant features are selected for training the model.
3. **Data Splitting**: The data is split into training and validation sets.
4. **Model Training**: A Random Forest model is trained on the training data.
5. **Model Validation**: The model's performance is evaluated using Mean Absolute Error (MAE).
6. **Model Training on Full Data**: The model is retrained on the entire dataset.
7. **Prediction**: Predictions are made on the test dataset using the trained model.

## Files

- `train.csv`: The training data used for building the model.
- `test.csv`: The test data used for making predictions.

## Usage

1. **Data Loading and Preparation**:
   - The training data is loaded and features are selected.
   - The data is split into training and validation sets.

2. **Model Training and Evaluation**:
   - A Random Forest model is trained on the training set.
   - The model's performance is evaluated using the Mean Absolute Error (MAE) metric on the validation set.

3. **Training on Full Data**:
   - The model is retrained on the entire dataset to improve accuracy.

4. **Prediction**:
   - The model is used to make predictions on the test dataset.

## Libraries Used

- `pandas`
- `scikit-learn`

## Results

- The model's performance is evaluated using the Mean Absolute Error (MAE).
