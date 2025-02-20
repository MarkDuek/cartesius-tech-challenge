# Cartesius Tech Challenge: Stock Prediction

This project involves building and evaluating predictive models for stock prices based on historical data. The task is to predict whether the stock price will go up or down based on the historical features.

## Model Performance Comparison

This repository presents a comparison of various models evaluated on a specific dataset. The table below summarizes key performance metrics, including Accuracy, Precision, Recall, and F1 Score, for each model.

### Models Overview

- **Regression**: A baseline regression approach.
- **XGBoost**: An ensemble method using gradient boosting.
- **LSTM**: Long Short-Term Memory network, particularly useful for sequential data.
- **CNN1d**: A one-dimensional Convolutional Neural Network.
- **CNN2d**: A two-dimensional Convolutional Neural Network.
- **ResNet50**: A pre-trained deep residual network with 50 layers, known for its strong performance in image recognition tasks.

## Evaluation Metrics

| Metric       | Regression | XGBoost | LSTM | CNN1d | CNN2d | ResNet50 |
|--------------|------------|---------|------|-------|-------|----------|
| **Accuracy** | 0.88       | 0.76    | 0.78 | 0.88  | 0.84  | 0.77     |
| **Precision**| 0.86       | 0.82    | 0.82 | 0.85  | 0.82  | 0.71     |
| **Recall**   | 0.88       | 0.62    | 0.68 | 0.93  | 0.91  | 0.95     |
| **F1 Score** | 0.87       | 0.70    | 0.72 | 0.88  | 0.86  | 0.82     |

