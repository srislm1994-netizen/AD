Project Summary
This project builds a system to forecast values in a time series using a Transformer neural network and compares its performance to a traditional LSTM benchmark. The workflow is as follows:

Synthetic Data Creation:
A synthetic dataset is generated with five correlated features plus a target variable, explicitly designed to include trends, seasonality, and noise—matching real-world business data shapes.​

Preprocessing:
Features and targets are scaled for effective neural network training. Data is split into training and test sets and formatted for sequence-based modeling.​

Custom Positional Encoding:
The code includes a custom positional encoding layer for the Transformer, allowing it to fully understand time relationships within sequences—an advantage for time series problems.​

Model Design and Training:
Two models are implemented:

A Transformer network tailored for time series.

A simple LSTM network acting as a baseline.
Training uses best practices, including learning rate scheduling and gradient clipping to keep learning stable.​

Evaluation:
Both models are tested on unseen data and metrics like RMSE and MAE are calculated, giving a clear sense of prediction quality.​

This end-to-end project demonstrates how modern deep learning approaches can be applied to time series forecasting, and gives you a foundation for further experimentation or business problem-solving.






