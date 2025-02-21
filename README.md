# Cartesius Tech Challenge: Stock Prediction

This project involves building and evaluating predictive models for stock prices based on historical data. The task is to predict whether the stock price will go up or down based on the historical features.

## Model Performance Comparison

This repository presents a comparison of various models evaluated on a specific dataset. The table below summarizes key performance metrics, including Accuracy, Precision, Recall, and F1 Score, for each model.

### Models Overview

- **Logistic Regression**: A baseline regression approach.
- **XGBoost**: An ensemble method using gradient boosting.
- **LSTM**: Long Short-Term Memory network, particularly useful for sequential data.
- **CNN1d**: A one-dimensional Convolutional Neural Network.
- **CNN2d**: A two-dimensional Convolutional Neural Network.
- **ResNet50**: A pre-trained deep residual network with 50 layers, known for its strong performance in image recognition tasks.

## Evaluation Metrics

| Model               | Accuracy | Precision | Recall  | F1 Score |
|---------------------|----------|-----------|---------|----------|
| Logistic Regression | **0.88** | **0.86**  | 0.88    | 0.87     |
| XGBoost             | 0.76     | 0.82      | 0.62    | 0.70     |
| LSTM                | 0.78     | 0.82      | 0.68    | 0.72     |
| CNN1d               | **0.88** | 0.85      | 0.93    | **0.88** |
| CNN2d               | 0.84     | 0.82      | 0.91    | 0.86     |
| ResNet50            | 0.77     | 0.71      | **0.95**| 0.82     |



