---

# House Price Prediction Model

## Overview
This Jupyter notebook focuses on creating a machine learning model to predict house prices using TensorFlow. It employs various data preprocessing techniques and neural network configurations for effective learning and prediction.

## Data Preparation
The process begins with importing essential libraries like TensorFlow, NumPy, and pandas. The dataset loaded contains attributes like property type, location, and price. Data transformation is carried out using `MinMaxScaler` for numerical data and `OneHotEncoder` for categorical data.

## Model Development
The model is split into training and test datasets to evaluate its performance on unseen data. A neural network model is defined using TensorFlow's Keras API, consisting of dense layers configured specifically for regression tasks.

## Training and Evaluation
The model is compiled with the mean absolute error as the loss metric and trained on the normalized data. Various architectures are tested to optimize the model's performance, focusing on practical machine learning application in the real estate sector.

## Conclusion
The notebook not only guides through the model building but also discusses different strategies for improving model accuracy and handling real-world data in the context of house price prediction.

---
