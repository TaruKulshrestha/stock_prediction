Stock Price Prediction Using Random Forest
This repository implements a stock price prediction model using Random Forest Regressor. The model predicts the next day's closing stock price based on historical data with features like 'Open', 'High', 'Low', 'Close', 'Volume', and additional features like moving averages and percentage change.

Key Features:
Data Preprocessing: Date conversion, duplicate removal, and invalid range check.
Normalization: Scaling features using Min-Max scaling.
Feature Engineering: Includes 7-day moving average, percentage change, and lag features.
Model Training: Uses Random Forest Regressor to predict stock prices.
Model Evaluation: Evaluates using MAE, MSE, and R² metrics.
Hyperparameter Tuning: Optimizes the model using Grid Search.
Feature Importance: Visualizes which features are most important for prediction.
Model Saving: Saves the trained model for future use with joblib.
