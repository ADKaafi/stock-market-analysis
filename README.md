# 📈 Stock Market Data Analysis

## 📌 Project Overview

This project performs an exploratory data analysis (EDA) of historical stock market data. The objective is to understand stock price movements, trading volume, daily returns, volatility, trends, and market performance over time.

The analysis uses Python and popular data analytics libraries to transform raw historical market data into meaningful insights through statistical analysis and visualization.

---

## 🎯 Objectives

The main objectives of this project are to:

* Analyze historical stock price trends
* Examine opening, closing, high, and low prices
* Analyze trading volume
* Calculate daily stock returns
* Measure market volatility
* Identify the best and worst trading days
* Analyze yearly and monthly performance
* Examine day-of-week performance
* Calculate moving averages
* Analyze maximum drawdown
* Measure cumulative returns
* Investigate relationships between market variables
* Identify important patterns and trends

---

## 📊 Dataset

The dataset contains historical daily stock market information.

### Dataset Features

| Column | Description                          |
| ------ | ------------------------------------ |
| Date   | Trading date                         |
| Open   | Opening stock price                  |
| High   | Highest price during the trading day |
| Low    | Lowest price during the trading day  |
| Close  | Closing stock price                  |
| Volume | Number of shares traded              |

The dataset contains **3,179 trading records** covering approximately **2014–2026**.

---

## 🛠️ Tools & Technologies

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 🔍 Data Analysis Process

### 1. Data Understanding

The dataset was inspected to understand:

* Number of records
* Number of columns
* Data types
* Date range
* Missing values
* Duplicate records
* Descriptive statistics

### 2. Data Cleaning

The following preprocessing steps were performed:

* Converted the `Date` column to datetime format
* Sorted records chronologically
* Checked for missing values
* Checked for duplicate records
* Created analytical time-based features

### 3. Feature Engineering

Additional variables were created, including:

* Year
* Month
* Quarter
* Year-Month
* Day of Week
* Daily Return
* Price Change
* Daily Trading Range
* Open-to-Close Difference
* High-Low Percentage
* Rolling Volatility
* Moving Averages
* Drawdown
* Cumulative Return

---

## 📈 Key Analysis Areas

### Stock Price Trends

Historical closing prices were analyzed to identify long-term upward and downward trends.

### Trading Volume

Trading volume was examined to identify periods of unusually high or low market activity.

### Daily Returns

Daily percentage returns were calculated to understand day-to-day market performance.

### Volatility

The standard deviation of daily returns was used to measure price volatility.

### Moving Averages

20-day, 50-day, and 200-day moving averages were calculated to identify short-, medium-, and long-term price trends.

### Drawdown Analysis

Maximum drawdown was calculated to measure the largest decline from a previous peak.

### Cumulative Return

Cumulative returns were calculated to show how the stock's value changed throughout the analyzed period.

### Time-Based Analysis

Performance was analyzed by:

* Year
* Month
* Quarter
* Day of Week

---

## 📊 Visualizations

The project includes visualizations such as:

* Closing Price Trend
* Opening vs Closing Price
* High and Low Price Trends
* Trading Volume
* Daily Returns
* Daily Return Distribution
* Rolling Volatility
* Moving Averages
* Annual Performance
* Monthly Performance
* Day-of-Week Performance
* Correlation Heatmap
* Drawdown
* Cumulative Return
* Volume vs Daily Return

---

## 📁 Project Structure

```text
stock-market-data-analysis/
│
├── data/
│   └── stock_market.csv
│
├── notebooks/
│   └── Stock_Market_Analysis.ipynb
│
├── analysis_outputs/
│   ├── cleaned_stock_data.csv
│   ├── stock_market_kpis.csv
│   ├── yearly_analysis.csv
│   ├── monthly_analysis.csv
│   ├── quarterly_analysis.csv
│   ├── weekday_analysis.csv
│   ├── best_trading_days.csv
│   ├── worst_trading_days.csv
│   └── highest_volume_days.csv
│
├── visualizations/
│
└── README.md
```

---

## 💡 Business & Analytical Questions

This analysis attempts to answer questions such as:

1. How has the stock price changed over time?
2. What was the highest closing price?
3. What was the lowest closing price?
4. Which periods experienced the highest trading volume?
5. What is the average daily return?
6. How volatile is the stock?
7. Which trading days produced the largest gains?
8. Which trading days produced the largest losses?
9. How does trading volume relate to daily returns?
10. What are the long-term price trends?
11. What was the maximum drawdown?
12. How did the stock perform across different years?
13. Are there noticeable differences between weekdays?
14. How does the closing price compare with moving averages?

---

## 📌 Important Note

This project is intended for **data analysis and educational purposes**. Historical market performance does not guarantee future results, and the analysis should not be interpreted as financial advice or a trading recommendation.

---

## 🚀 Future Improvements

Possible extensions include:

* Building a stock price prediction model
* Applying Linear Regression
* Applying Random Forest
* Applying XGBoost
* Time-series forecasting
* ARIMA modeling
* LSTM forecasting
* Technical indicators such as RSI and MACD
* Interactive dashboards using Power BI or Tableau
* Automated financial reporting

---

## 👨‍💻 Author

**Ahmed Kaafi Mohamoud**

Computer Science Student | Data Analytics Enthusiast

### Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis
* Statistical Analysis
* Feature Engineering
* Data Visualization
* Time-Series Analysis
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
