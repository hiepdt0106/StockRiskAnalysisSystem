# StockRiskAnalysisSystem
End-to-end stock risk analysis and price prediction system using PySpark, K-Means, and ML

# Overview
This project presents a **stock market analysis system** that focuses on **risk analysis** and **stock price prediction** using historical stock data.

The main goal of the project is to:
- Analyze statistical characteristics of stock prices
- Measure and compare **risk levels** between different stocks
- Apply machine learning techniques to **cluster stocks by risk**
- Build a basic **stock price prediction model**

The project is implemented primarily using **PySpark** to demonstrate scalable data processing.

## Project Objectives
- Process and analyze historical stock price data
- Extract statistical features for financial analysis
- Perform **risk analysis using clustering techniques**
- Predict stock prices based on historical data
- Visualize analytical results to support interpretation

## Methodology

### 1. Data Loading & Preprocessing
- Load historical stock price data into PySpark DataFrames
- Handle missing values and invalid records
- Store intermediate datasets using **Parquet format** for efficiency

### 2. Feature Engineering
- Compute statistical indicators such as:
  - Mean stock price
  - Standard deviation (volatility)
- Aggregate features by stock symbol using PySpark operations

### 3. Risk Analysis with K-Means Clustering
- Apply **K-Means clustering** on statistical features
- Group stocks into different clusters representing **risk levels**
- Interpret clusters based on volatility and price behavior

### 4. Stock Price Prediction
- Use historical price-related features to predict stock prices
- Apply regression-based machine learning models
- Evaluate prediction performance using **RMSE and R² metrics**

### 5. Data Visualization
- Visualize stock price trends
- Plot clustering results for risk comparison
- Display prediction outcomes to support analysis

---

## Technologies Used
- **Python**
- **PySpark**
- **Scikit-learn**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Jupyter Notebook**

---

## Results & Discussion
- Stocks are successfully clustered into multiple **risk groups** based on volatility
- Risk clustering helps distinguish low-risk and high-risk stocks
- The prediction model demonstrates reasonable performance on historical data
> Due to the high volatility of financial markets and the influence of external factors (news, investor sentiment), prediction accuracy is inherently limited.

## Future Improvements
- Further optimize and extend the use of financial indicators such as RSI and MACD
- Improve feature selection to better leverage technical indicators in prediction models
- Apply advanced time-series models such as LSTM for improved forecasting
- Deploy the system as a simple analytical dashboard


## Notes This project is developed for **academic and learning purposes**, focusing on practical applications of data science and machine learning in financial analysis




---
