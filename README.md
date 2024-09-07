# Tesla Stock Price Prediction Using Linear Regression

This project focuses on predicting Tesla's stock closing prices using linear regression based on historical stock data from 2010 to 2020. By analyzing stock features like open, high, low prices, and volume, the project demonstrates how machine learning can be applied to financial data to predict future stock prices.

## Overview

The goal of this project is to develop a linear regression model that can accurately predict Tesla's closing stock prices using key stock market indicators. This involves data preprocessing, training a machine learning model, and evaluating its performance using statistical metrics.

## Key Steps

1. **Data Collection**: The dataset used for this analysis consists of Tesla stock data between 2010 and 2020. The data includes features such as date, open price, high price, low price, closing price, adjusted closing price, and trading volume.

2. **Data Preprocessing**: 
   - The dataset was cleaned and inspected to ensure all values were valid. 
   - Key features such as the opening price, highest price, lowest price, and trading volume were selected as input variables (X), while the closing price was used as the target variable (y).

3. **Data Visualization**: Pair plots were generated to visualize the relationships between different stock features, helping to understand correlations in the data.

4. **Model Training**: 
   - The data was split into training and testing sets to evaluate model performance.
   - A linear regression model was trained using the selected input features. This step involved fitting the model to the training data to learn the relationship between stock prices and the selected features.

5. **Model Prediction**: 
   - The trained model was used to predict Tesla's closing prices on the test dataset.
   - A scatter plot of predicted values vs actual test values was created to visually assess the model’s accuracy.

6. **Error Calculation**: The performance of the model was evaluated using several error metrics:
   - **MAE (Mean Absolute Error)**: Measures the average magnitude of errors in the predictions.
   - **MSE (Mean Squared Error)**: Measures the average squared difference between actual and predicted values.
   - **RMSE (Root Mean Squared Error)**: Provides a sense of how much error is typically in the predictions, in the same units as the data.

7. **Residual Analysis**: A residual plot was generated to check if the residuals (differences between actual and predicted values) followed a normal distribution, indicating the model's goodness of fit.

## Insights

- **Model Performance**: The model performed well, with low error rates (MAE, MSE, and RMSE) indicating that linear regression was a suitable algorithm for predicting Tesla's closing prices over the test period.
- **Residual Distribution**: The residuals followed a nearly normal distribution, confirming the model's fit was appropriate for the dataset.
- **Feature Importance**: The high correlation between input features (open, high, low prices, and volume) and the closing price helped the model achieve good predictive performance.

## Conclusion

This project demonstrates how linear regression can be applied to financial stock data to predict closing prices. Although stock markets are complex and influenced by numerous factors, this analysis shows that historical data can provide valuable insights into stock price trends and can be used to make reasonably accurate predictions.
