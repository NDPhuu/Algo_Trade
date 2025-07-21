# 📈 Algorithmic Trading with Python

This project explores multiple algorithmic trading strategies using Python, focusing on the Vietnamese stock market (VN30 and HNX indices). It combines equal-weight strategies, value-based stock selection, and technical indicators for backtesting.

---

## ⚖️ Equal-Weight Strategy with VN30

- The **equal-weight approach** gives the same weight to each stock in a portfolio, regardless of the company's size or market capitalization.
- Applied to the VN30 index, this helps diversify the portfolio and reduce concentration risk from large-cap stocks.
- Smaller stocks may offer higher upside potential, and equal-weighting allows capturing these opportunities.
- The [`vnstock3`](https://pypi.org/project/vnstock3/) Python library is used to fetch VN30 data **without requiring API keys** or web scraping.

---

## 💰 Quantitative Value Strategy

- This strategy follows a **value investing** philosophy: selecting stocks that are undervalued based on financial metrics (e.g., P/E ratio, P/B ratio, etc.).
- The algorithm identifies the **10 most undervalued stocks in the VN30** based on a custom value score.
- An **equal-weight portfolio** is then constructed with these 10 stocks.
- The model also calculates suggested trades for rebalancing the portfolio periodically.

---

## 🔁 Technical Strategy & Backtesting (HNX Index)

- A trading strategy is developed using popular technical indicators:
  - **RSI (Relative Strength Index)**
  - **MACD (Moving Average Convergence Divergence)**
  - **EMA (Exponential Moving Average)**
  - **Bollinger Bands**
- The strategy is **backtested on HNX-listed stocks** using historical data from **01/01/2024 to 30/06/2024**.
- Performance metrics such as cumulative returns, Sharpe ratio, and drawdown will be evaluated.

---

## 📌 Status

- [x] Equal-weight VN30 strategy implemented  
- [x] Value scoring model completed  
- [x] Backtesting on HNX data  
- [ ] Portfolio rebalancing automation *(Coming soon)*  
- [ ] Streamlit dashboard for visualization *(Planned)*

---

## 🛠️ Tools & Libraries

`Python` | `vnstock3` | `pandas` | `numpy` | `matplotlib` | `backtesting.py` | `ta-lib` (optional)

---

## 📬 Contact

Feel free to reach out if you're interested in this project or want to collaborate:

📧 Email: ducphu.tc10@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/ndphu109/)
