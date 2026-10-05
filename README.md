# Traffic Volume Prediction with PyTorch

A deep learning time-series forecasting project using PyTorch and an LSTM neural network to predict hourly traffic volume.

## Project Overview

This project uses historical traffic and weather data to predict future traffic volume. The model uses sequences of previous time steps as inputs and predicts the traffic volume for the next time step.

## Technologies

- Python
- PyTorch
- Pandas
- NumPy
- LSTM neural networks

## Model

The model uses an LSTM network designed for sequential time-series data.

Training configuration:

- Sequence length: 24
- Hidden size: 64
- LSTM layers: 2
- Batch size: 64
- Optimizer: Adam
- Loss function: Mean Squared Error
- Epochs: 2

## Results

Final training loss:

0.0033

Test Mean Squared Error:

0.0024

The model achieved low error on both the training and test datasets.

## Skills Demonstrated

- Time-series sequence creation
- NumPy-to-PyTorch tensor conversion
- PyTorch DataLoader usage
- LSTM neural network development
- Regression modeling
- Model training and evaluation
- Mean Squared Error evaluation
