# Cartesius Tech Challenge: Stock Prediction

This project involves building and evaluating predictive models for stock prices based on historical data. The task is to predict whether the stock price will go up or down based on the historical features.

## Model Performance Comparison

This repository presents a comparison of various models evaluated on a specific dataset. The table below summarizes key performance metrics, including Accuracy, Precision, Recall, and F1 Score, for each stock model.

### Models Overview

- **Logistic Regression**: A baseline logistic regression approach.
- **XGBoost**: An ensemble method using gradient boosting.
- **LSTM**: Long Short-Term Memory network, particularly useful for sequential data.
- **CNN1d**: A one-dimensional Convolutional Neural Network.
- **CNN2d**: A two-dimensional Convolutional Neural Network.
- **ResNet50**: A pre-trained deep residual network with 50 layers, known for its strong performance in image recognition tasks.

Portfolios starts with R$10,000.00.

### BBAS3.SA

| Model                | Accuracy | Precision | Recall  | F1 Score | Portfolio Value |
|----------------------|----------|-----------|---------|----------|-----------------|
| Logistic Regression  | **0.89** | 0.84      | 0.90    | 0.87     | R$61,876.30      |
| XGBoost              | 0.62     | 0.53      | **0.91**| 0.67     | R$37,722.00      |
| LSTM                 | 0.88     | **0.85**  | 0.86    | 0.85     | **R$62,626.40**  |
| CNN1d                | 0.88     | **0.85**  | 0.88    | 0.86     | R$62,045.90      |
| CNN2d                | 0.88     | 0.88      | **0.92**| **0.90** | R$11,669.61      |
| ResNet50             | **0.89** | **0.91**  | 0.90    | **0.90** | R$13,445.63      |

---

### CSNA3.SA

| Model                | Accuracy | Precision | Recall  | F1 Score | Portfolio Value |
|----------------------|----------|-----------|---------|----------|-----------------|
| Logistic Regression  | 0.88     | 0.81      | **0.94**| 0.87     | **R$304,121.20** |
| XGBoost              | 0.70     | 0.60      | 0.89    | 0.72     | R$106,843.43     |
| LSTM                 | 0.88     | 0.82      | 0.90    | 0.86     | R$278,840.65     |
| CNN1d                | **0.89** | 0.87      | 0.86    | 0.86     | R$249,093.74     |
| CNN2d                | **0.89** | **0.95**  | 0.85    | **0.90** | R$13,436.11      |
| ResNet50             | 0.86     | 0.90      | 0.86    | 0.88     | R$14,276.67      |

---

### PETR4.SA

| Model                | Accuracy | Precision | Recall  | F1 Score | Portfolio Value |
|----------------------|----------|-----------|---------|----------|-----------------|
| Logistic Regression  | 0.86     | 0.86      | 0.88    | **0.87** | R$149,479.20     |
| XGBoost              | 0.67     | 0.83      | 0.46    | 0.59     | R$39,653.37      |
| LSTM                 | 0.86     | 0.84      | **0.89**| **0.87** | **R$153,745.39** |
| CNN1d                | **0.87** | **0.87**  | 0.87    | **0.87** | R$147,650.60     |
| CNN2d                | 0.86     | 0.83      | **0.90**| 0.86     | R$21,443.63      |
| ResNet50             | 0.84     | 0.85      | 0.83    | 0.84     | R$21,780.42      |

---

### VALE3.SA

| Model                | Accuracy | Precision | Recall  | F1 Score | Portfolio Value |
|----------------------|----------|-----------|---------|----------|-----------------|
| Logistic Regression  | 0.87     | 0.89      | 0.84    | 0.87     | **R$88,830.09**  |
| XGBoost              | 0.59     | 0.84      | 0.22    | 0.35     | R$16,404.33      |
| LSTM                 | 0.81     | 0.89      | 0.72    | 0.79     | R$61,597.02      |
| CNN1d                | **0.89** | **0.90**  | 0.86    | **0.88** | R$86,474.91      |
| CNN2d                | 0.80     | 0.72      | **0.98**| 0.83     | R$17,737.00      |
| ResNet50             | 0.76     | 0.68      | **0.98**| 0.80     | R$19,697.92      |
