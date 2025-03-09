# Stock Price Prediction using LSTM

## Overview
This project focuses on predicting stock closing prices 5 days into the future using deep learning models, particularly LSTM (Long Short-Term Memory). The solution includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and predictions.

## Key Findings
- **Trends and Seasonality**: Identified patterns in stock prices, including upward and downward trends.
- **Feature Engineering**: Used scaled 'Close' prices and created sequences for time-series prediction.
- **Model Performance**: LSTM performed well with an RMSE of approximately 26.64.
- **Limitations**:
  - Additional features like trading volume and technical indicators could enhance accuracy.
  - Alternative models (GRU, XGBoost, or ARIMA) could be explored.
  - More hyperparameter tuning could improve generalization.

## Dataset
The dataset consists of historical stock prices with the following columns:
- **Date**: The date of the stock price record.
- **Open, High, Low, Close**: Stock price details for the day.
- **Volume**: Number of shares traded.

## Steps to Reproduce
1. **Install Dependencies**:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn tensorflow
   ```
2. **Run the Jupyter Notebook**:
   - Open `stock_price_prediction.ipynb` in Jupyter Notebook or Google Colab.
   - Run all cells sequentially to load data, train the model, and generate predictions.
3. **View Predictions**:
   - Predictions are saved in `predictions.csv`.
   - A visualization compares actual vs. predicted stock prices.

## Future Improvements
- Experiment with alternative models (GRU, ARIMA, XGBoost).
- Tune hyperparameters for better performance.
- Use additional financial indicators as features.



