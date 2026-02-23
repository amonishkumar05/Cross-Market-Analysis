# 📊 Cross-Market Analysis: Crypto, Oil & Stocks

## 📌 Project Overview

This project analyzes the relationship between Cryptocurrency markets, Crude Oil prices, and Stock Market indices using SQL and Streamlit.

The objective of this project is to understand cross-market trends and compare financial movements across different asset classes.

---

## 🛠️ Technologies Used

- Python
- Pandas
- SQLite (Database)
- SQL
- Streamlit
- Google Colab

---

## 📂 Dataset Description

The project uses:

- Cryptocurrency data (Bitcoin, Ethereum, etc.)
- Historical Oil price data
- Stock market data (S&P 500, NASDAQ, NIFTY)

The data is stored in SQLite database tables:

- `cryptocurrencies`
- `crypto_prices`
- `oil_prices`
- `stock_prices`

---

## 🗄️ Database Structure

The database contains separate tables for each market:

- Cryptocurrency master data
- Daily crypto prices
- Oil historical prices
- Stock market daily data

SQL joins are used to analyze cross-market relationships.

---

## 🔎 SQL Queries Implemented

The project includes multiple SQL queries such as:

- Top 3 cryptocurrencies by market cap
- Highest Bitcoin price
- Average oil price per year
- Monthly stock averages
- Bitcoin vs Oil comparison
- Bitcoin vs S&P 500 comparison
- Ethereum vs NASDAQ comparison

---

## 📊 Streamlit Dashboard

The Streamlit application includes:

### 🏠 Home Page
Project overview and dataset description.

### 🔍 Filters Page
Filter market data by date range and visualize trends.

### 🧮 Queries Page
Run predefined SQL queries and view results dynamically.

---

## ▶️ How to Run the Project

1. Open the project notebook in Google Colab.
2. Run all cells to create and populate the database.
3. Run the Streamlit app.
4. Use the Cloudflare link to access the dashboard.

---

## 🎯 Conclusion

This project demonstrates how SQL can be used for financial data analysis and how cross-market insights can be visualized using Streamlit.

It provides practical experience in:
- Data collection
- Database design
- SQL query execution
- Data visualization
- Dashboard development
