#  Bitcoin Price Reaction to Global News & Economic Events — ML Based Insight

##  Project Overview
In recent times, Bitcoin has acted as a sensitive indicator of global investor sentiment, reacting sharply to economic shocks, Fed policy changes, tariff wars, and more. This project explores the behavior of Bitcoin (BTC) prices in response to such macroeconomic events using a basic yet highly effective Machine Learning model.

We use **Linear Regression** to predict BTC price movement and observe the **impact of economic indicators like Tariff hikes, NFP reports, strategic reserves release, and ETF movements** on BTC pricing and volatility.

---

##  Dataset
- Historical Bitcoin price data till **31st Dec 2024**
- Source: Yahoo Finance via yfinance API
- Columns: `Date`, `Open`, `High`, `Low`, `Close`, `Volume`, `Adj Close`

---

##  Key Components

###  Exploratory Data Analysis (EDA)
- Summary statistics
- Missing value check
- BTC price trends over time
- Volatility pattern visualization

###  Model: Linear Regression
- Input: Last known `Close` value
- Output: Predicted `Close` for next 20 days
- Accuracy achieved: **97.34% (R² Score)**

###  Real-World Impact Considered
-  $3+ trillion wiped from US stock market amid tariff tensions
-  $200+ billion pulled out of crypto market
-  USD devaluation against major currencies
-  Gold prices surged, acting as a hedge
-  BTC showed volatility spikes and dips aligned with:
  - NFP surprise data
  - Trump-era tariff revival speculation
  - Fed interest rate direction
  - Delay and speculation in BTC ETF approvals

---

##  Visualization Highlights
- Actual vs Predicted BTC Prices
- Yearly BTC price movement with event markers
- Future 20-day BTC forecast plotted

---

##  Conclusion

This project is a data-driven attempt to understand the **interplay between macroeconomic news and BTC price behavior**. The ML model is **not an investment recommendation** but an analytical tool to explore potential patterns in volatile markets.

In real markets, news, sentiment, and regulatory decisions play a massive role. Thus, this project acts as a **foundation for deeper financial modeling, forecasting, or trading strategy simulations.**

---

##  Technologies Used
- Python
- Pandas, NumPy
- Scikit-Learn
- Matplotlib, Seaborn
- yfinance

---

##  Author: Manoj Nailwal

-  Email: [manojnailwal1234567@gmail.com](mailto:manojnailwal1234567@gmail.com)  
-  LinkedIn: [linkedin.com/in/manoj-nailwal-70988024a](https://linkedin.com/in/manoj-nailwal-70988024a)  
-  GitHub: [github.com/manojnailwal](https://github.com/manojnailwal)  
-  HackerRank: [hackerrank.com/manojnailwal1231](https://www.hackerrank.com/manojnailwal1231)

---

>  **Disclaimer:** This model is educational and not meant for real-world financial advice or trading.
