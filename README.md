# 📈 Stock Price Analyser

A simple and interactive Streamlit app that visualizes historical stock prices and trading volumes using data from **Yahoo Finance (via `yfinance`)**.

---

## 🔗 Live Demo

**[https://stockanalyser1.streamlit.app/](https://stockanalyser1.streamlit.app/)**  

---

## ⚙️ Features

- 🔍 Enter any stock ticker symbol (e.g., AAPL, TSLA, MSFT)
- 📆 Choose custom start and end dates for historical analysis
- 📊 View daily **closing prices** and **volume of shares traded**
- 🧾 Interactive DataFrame with full stock history for the selected period

---

## 🛠 Tech Stack

- `Streamlit` – UI and deployment
- `yfinance` – Live stock data from Yahoo Finance
- `pandas` – Data handling and manipulation
- `matplotlib` / Streamlit's `line_chart` – Chart rendering

---

## ▶️ How to Run Locally

### 1. Clone and install dependencies

```bash
pip install streamlit pandas yfinance
```

### 2. Run the app

```bash
streamlit run app.py
```

---

## 💡 Example Usage

- Input Ticker: `AAPL`
- Start Date: `2023-01-01`
- End Date: `2024-01-01`

You’ll get:
- A table of daily price and volume
- A line chart of daily **closing prices**
- A line chart of **traded volume**

---

## 🧾 Sample Output

```
### The Stock Prices of AAPL

| Date       | Open   | High   | Low    | Close  | Volume  |
|------------|--------|--------|--------|--------|---------|
| 2023-01-03 | 129.89 | 130.90 | 124.17 | 125.07 | 112117800 |
```

---

## 📦 Folder Structure

```
stock-price-analyser/
├── app.py
├── README.md
```

---

## 🙌 Acknowledgements

- [Yahoo Finance](https://finance.yahoo.com/)
- [`yfinance`](https://github.com/ranaroussi/yfinance)
- [Streamlit](https://streamlit.io/)
