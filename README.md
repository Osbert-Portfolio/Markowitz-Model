# 📈 Markowitz Portfolio Optimization Model

## 📌 Overview
This project implements **Modern Portfolio Theory (MPT)** using the **Markowitz Model** to optimize portfolio allocation by balancing risk and return. It retrieves historical stock data, calculates expected returns, risk, and optimizes portfolio weights to achieve an efficient frontier.

## 🚀 Features
### 📊 Data Collection
✅ Fetches historical stock data using **Yahoo Finance (yfinance)**.
✅ Processes closing prices for selected stocks.
✅ Computes daily and annual returns.

### 📈 Portfolio Optimization
✅ Calculates **expected returns and risk (standard deviation)** for each stock.
✅ Uses **Markowitz’s Efficient Frontier** to optimize asset allocation.
✅ **Minimizes portfolio variance** using **SciPy’s optimization functions**.
✅ Visualizes the **Efficient Frontier** using **Matplotlib and Seaborn**.

## 🛠 Technologies Used
- 🐍 **Python Libraries:** Pandas, NumPy, Matplotlib, Seaborn, SciPy
- 📊 **Financial Data API:** Yahoo Finance (yfinance)
- ⚡ **Optimization Algorithm:** SciPy’s `minimize()` for portfolio weight optimization
- 📓 **Jupyter Notebook:** Interactive data exploration and modeling

## 📂 How to Use
1️⃣ Ensure `yfinance` is installed and functional.
2️⃣ Run the notebook to fetch stock data and compute returns.
3️⃣ Optimize the portfolio using Markowitz’s Efficient Frontier.
4️⃣ Interpret the results and visualize the Efficient Frontier.
