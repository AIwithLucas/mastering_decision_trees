# Predicting Stock Prices

## Dataset Overview

    - get from yahoo finance or Quandl
    - predict Close Price of stock for next day

| **Feature Name** | **Data Type** | **Description**                                     |
| ---------------- | ------------- | --------------------------------------------------- |
| `Date`           | Date          | The date of the trading day (format: YYYY-MM-DD).   |
| `Open`           | Float         | The price of the stock at market opening.           |
| `High`           | Float         | The highest price the stock reached during the day. |
| `Low`            | Float         | The lowest price the stock reached during the day.  |
| `Close`          | Float         | The price of the stock at market close.             |
| `Volume`         | Integer       | The total number of shares traded during the day.   |

## Stock Focus: AMD

### Approach to Model Training

##### 1 Problem

    - predicting stock price is difficult due to market volatility & external influences

##### 2 Model Selection

    - Decision Tree Regressor would be optimal for non-linear relationship prediction

    - Consider advanced techniques like Random Forest & Gradient Boosting models

##### 3 Data Prep

    - ensure data is sorted by date

##### 4 Feature engineering

    - consider techniques like:
        - moving averages (5-day, 10-day)
        - volume trends (3-day rolling average of volume)
        - technical indicators (RSI, MACD, Bollinger Bands)
        - Calendar effects (day of week / month)

##### 5 Handling Temporal Dependence

    - use lag features (close price of previous n days as input features)
    - avoid data leakage where future data is used to predict past prices
