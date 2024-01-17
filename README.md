# Stock-Market-Price-Prediction-Model
The provided code is a Python script for a stock market price predictor using linear regression. It involves data visualization, exploratory data analysis, and predictions. The code provides a comprehensive analysis of stock market data, builds a linear regression model for prediction, and offers a user-friendly interface for making predictions.
Note: The Tkinter GUI part requires user interaction and input, and it's designed to predict stock prices based on the chosen date and the number of days for predictions.
### Data Loading and Cleaning:
Imports necessary libraries (NumPy, Pandas, Matplotlib, Seaborn). Loads stock market data from a CSV file ('INFY.NS.CSV'). Checks for data types, null values, and drops rows with null values. Converts the 'Date' column to datetime format.
## Univariate Analysis:
Uses boxplots to visualize the statistical distribution of columns ('Open', 'High', 'Low', 'Close', 'Adj Close', 'Volume'). Utilizes distribution plots to analyze the distribution of each column.
## Bivariate Analysis:
Creates scatter plots to visualize the bivariate distribution between each pair of columns.
## Outlier Detection and Removal:
Identifies and removes outliers using the z-score method for the 'Volume' column.
## Correlation Analysis:
Generates a correlation matrix to identify relationships between columns. Visualizes the correlation matrix using a heatmap.
## Prediction Model:
Defines a linear regression model to predict stock prices. Evaluates different numbers of samples for predictions. Plots RMSE and R2 score against the number of samples to identify optimal parameters.
## Predictions on Test Data:
Uses the trained model to predict stock prices on the test data. Calculates root mean squared error (RMSE) and visualizes actual vs. predicted prices.
## User Interface (Tkinter):
Creates a simple GUI for users to input a date and the number of days for predictions. Implements functionality to predict and display results based on user input.
