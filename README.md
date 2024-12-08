# flight_price_prediction
This project implements a machine learning model to predict airline ticket prices based on various features such as flight duration, days left until the flight, the number of stops, and airline type. The dataset has been preprocessed and normalized to improve the performance of the model.

The main objective is to accurately predict the normalized price of a flight, helping to analyze pricing trends and provide insights for potential pricing optimization.

Features:

Dataset: Includes features like flight duration, days left, airline categories (AirAsia, Indigo, etc.), and number of stops.
Preprocessing: Normalization, one-hot encoding for categorical features, and feature scaling.
Model: A neural network built using TensorFlow and Keras with mean squared error (MSE) as the loss function and mean absolute error (MAE) for evaluation.
Evaluation Metrics: Test MSE and MAE were used to validate the model's performance, achieving a low error rate.
Results:

Test MSE: 0.0019
Test MAE: 0.0279
Usage:
This project demonstrates how to preprocess a dataset, build a neural network, and evaluate its performance for regression tasks.

Future Work:

Improve model performance by experimenting with advanced architectures or feature engineering.
Expand the dataset with more features to capture complex relationships.
Deploy the model in a user-friendly interface for real-time predictions.
Languages & Libraries:

Python
TensorFlow / Keras
Scikit-learn
Pandas
NumPy
Matplotlib / Seaborn
