# Summary of What the Code Does:

-Downloads stock data and splits it into training and test sets.
-Trains multiple regression models (Linear, Lasso, Ridge, SVR) to predict stock prices based on historical data.
-Evaluates the performance of each model using MSE, RMSE, and R² scores.
-Tunes the SVR model using GridSearchCV.
-Saves the best-performing model (Ridge) for future use.
