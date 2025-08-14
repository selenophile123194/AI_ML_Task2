# Task: Stock Market Data Analysis using yFinance

## 📌 Objective
The goal of this task is to fetch, analyze, and visualize historical stock market data using the `yfinance` Python library.  
We aim to observe stock trends, calculate basic statistics, and visualize performance over time.

---

## 📂 Dataset
- **Source:** Yahoo Finance API (via `yfinance` Python library)  
- **Fetched Data Includes:**
  - Open price
  - Close price
  - High & Low prices
  - Trading volume
  - Date range specified in the script

---

## 🛠 Steps Performed
1. **Installed and imported required libraries:**
   - `yfinance` for data retrieval
   - `pandas` for data handling
   - `matplotlib` and `seaborn` for visualizations

2. **Fetched historical data** for selected stock tickers (e.g., `AAPL`, `GOOG`, `MSFT`).

3. **Performed basic exploratory analysis:**
   - Checked first few rows of the data
   - Calculated moving averages (7-day, 30-day)

4. **Visualized stock trends:**
   - Close price over time
   - Moving average comparison

---

## 📊 Key Insights
- Moving averages provide a smoother trend line for better decision-making.
- Stocks exhibit clear upward or downward trends over selected time frames.
- High trading volume often coincides with major price changes.

---

## 📷 Sample Visualizations
| Stock Close Price Trend | Moving Average Trend |
| ----------------------- | -------------------- |
| ![Close Price](images/close_price.png) | ![Moving Average](images/moving_avg.png) |

---

## 📈 Possible Next Steps
- Add candlestick charts for better technical analysis.
- Include multiple stock comparisons in the same graph.
- Automate daily data fetching and analysis.

---

## 📚 References
1. **Yahoo Finance API Documentation**  
   🔗 [https://pypi.org/project/yfinance/](https://pypi.org/project/yfinance/)  
2. **Matplotlib Documentation**  
   🔗 [https://matplotlib.org/](https://matplotlib.org/)  
3. **Seaborn Documentation**  
   🔗 [https://seaborn.pydata.org/](https://seaborn.pydata.org/)  

---
