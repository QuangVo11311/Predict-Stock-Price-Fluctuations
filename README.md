# Predict-Stock-Price-Fluctuations

<h1 align="center">Predict stock price fluctuations using LSTM</h1>

<p align="center">
  This repository provides code and resources for predicting stock market trends using Long Short-Term Memory (LSTM) neural networks to forecast stock prices for informed investment decisions.
</p>

## Project Overview
In this project, we leverage historical stock market data to train an LSTM model. This model learns from past price and volume data of specific stocks, such as FPT, PNJ, MSN, and VIC, to predict future stock prices. LSTM networks are designed to capture long-term dependencies, making them highly effective for time series forecasting.

## Dataset
We use a dataset containing historical stock prices of four companies. This dataset includes features such as opening price, closing price, volume, etc. We preprocess the data, split it into training and test sets, and perform necessary data transformations.

## Model Training
The LSTM model is built using deep learning frameworks TensorFlow. We train the model on the training dataset, adjusting hyperparameters such as the number of hidden layers, the number of neurons per layer, and the learning rate. We employ techniques like regularization and dropout to prevent overfitting.

## Evaluation and Results
Once the model is trained, we evaluate its performance on the testing dataset. We compute various metrics such as mean squared error (MSE), root mean squared error (RMSE), and mean absolute error (MAE) to assess the model's accuracy. We visualize the predicted stock prices alongside the actual prices to gain insights into the model's performance.

## Contributing
We welcome contributions to enhance the project and make it even more effective. If you have any suggestions, bug fixes, or new features to add, please submit a pull request. We appreciate your contributions!

Thank you for visiting our project repository.
