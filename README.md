# Stock Market Predictions using Machine Learning and Deep Learning Techniques: A Comparative Study
Stock market forecasting is challenging due to its dynamic nature, vast data, and complex investor behavior. This project explores machine learning and deep learning models, including Linear Regression, Random Forest, SVM, XGBoost, and LSTM, to predict stock prices using the Nifty50 dataset. Models are evaluated using metrics like MAE, RMSE, MAPE, and Confusion Matrix. The goal is to identify the most accurate model for effective stock price prediction. This contributes to better investment strategies and risk management for market participants.
# Dataset
The stock market data for this research was sourced from Yahoo Finance, focusing on stocks listed on the National Stock Exchange of India (NSE) with the ".NS" suffix. Yahoo Finance serves as a comprehensive media platform offering price data for a wide range of companies. The dataset provides detailed historical insights into NSE-listed stocks, covering the period from September 8, 2023, to the earliest available start date for each stock.
## Dataset Features
- Open
- High
- Low
- Close
- Adj Close
- Volume
## Stocks Used
- HDFCBANK
- RELIANCE
- ICICIBANK
- INFY
- ITC
- TCS
- LT
- KOTAKBANK
- AXISBANK
- SBIN
- TATAMOTORS
# Algorithms Used
## 1) LINEAR REGRESSION
<p align="center">
  <img src="https://github.com/user-attachments/assets/d3fd8ac3-4340-4ba1-8f76-d2a763026745" alt="Image 1" width="300"/>
  <img src="https://github.com/user-attachments/assets/e030aea7-12d3-4cfa-a1ef-543daf5f5952" alt="Image 2" width="300"/>
</p>
## 2) SUPPORT VECTOR REGRESSOR
<p align="center">
  <img src="https://github.com/user-attachments/assets/b8c2bd84-fd76-4eb9-81d7-f031882cc612" alt="Image 1" width="300"/>
  <img src="https://github.com/user-attachments/assets/e3679c94-bc3e-4d41-aff4-7c1a1523264a" alt="Image 2" width="300"/>
</p>

## 3) RANDOM FOREST
<p align="center">
  <img src="https://github.com/user-attachments/assets/1d336c4e-3a13-40fc-a702-6a7695d0f91c" alt="Image 1" width="300"/>
  <img src="https://github.com/user-attachments/assets/b310a347-0512-46e8-ad0c-80238d70668d" alt="Image 2" width="300"/>
</p>

## 4) XG BOOST
<p align="center">
  <img src="https://github.com/user-attachments/assets/11ada337-6962-4dcc-8961-026291b243df" alt="Image 1" width="300"/>
  <img src="https://github.com/user-attachments/assets/91a9a5fc-8491-4fd1-9101-c450a3f04da0" alt="Image 2" width="300"/>
</p>

## 5) LSTM
<p align="center">
  <img src="https://github.com/user-attachments/assets/a924db4e-8651-436a-ab9e-18e243bd9988" alt="Image 1" width="300"/>
  <img src="https://github.com/user-attachments/assets/1e56b768-0fe4-4f6f-a14b-d7474e1b6573" alt="Image 2" width="300"/>
</p>

# Conclusion

- **Linear Regression** achieved the lowest mean squared error (MSE) of **96.88** and the highest R-squared value of **0.9996**, indicating excellent accuracy.  
- **Support Vector Regressor (SVR)** exhibited a high MSE of **49395.95** and a moderate R-squared value, showing comparatively poorer performance and lower accuracy.  
- **Random Forest** and **XGBoost** demonstrated competitive performance with low MSE, high R-squared, and low MAE and MAPE values.  
- **LSTM** performed well with a low MSE and a high R-squared value but showed higher MAE and MAPE compared to other algorithms.  

```Linear Regression, Random Forest, and XGBoost are strong contenders for stock market prediction due to their accuracy and interpretability.```

