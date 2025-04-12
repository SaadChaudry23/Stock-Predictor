# Stock Price Predictor
A machine learning model that predicts the next day’s S&P 500 closing price using historical market data and engineered indicators.

## Features
- Data cleaning and preprocessing
- Feature engineering (technical indicators)
- Multiple ML models evaluated (Linear Regression, Random Forest, XGBoost)
- Backtesting with sliding window
- Performance comparison with visualizations

## Tools Used
Python, Pandas, Scikit-learn, yfinance, Matplotlib, Streamlit

## How to Improve this Model
- Use other indices around the world that open before the US markets open. So it might be worth looking at those prices and seeing if you can actually correlate them right. So for example, if an index on the other side of the world increases, does the snp500 increase?
- Add in news possibly? --> bit harder to do tbh
- Look at the big sectors of the snp500. 
