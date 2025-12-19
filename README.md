# Stock Market Analysis

Technical and fundamental analysis of stock market data using Python and Excel. Includes technical indicators, simple trend forecasting, and basic risk analysis.

## 1. Project overview

This project shows end-to-end analysis of stock price data:

- Download daily OHLCV data for selected stocks.
- Perform exploratory data analysis (EDA) and visualizations.
- Calculate common technical indicators (SMA, EMA, RSI, MACD, Bollinger Bands).
- Build a simple forecasting model to predict future prices.
- Evaluate basic risk metrics such as volatility and drawdown.
- Prepare a cleaned dataset for Excel / Power BI dashboards.

## 2. Tech stack

- **Python**: pandas, numpy, matplotlib, seaborn, yfinance, scikit-learn, statsmodels
- **Jupyter Notebook** for analysis
- **Excel / Power BI** for reporting dashboards

## 3. Setup

```bash
# 1. Clone the repository
git clone https://github.com/deeepanbe/stock-market-analysis.git
cd stock-market-analysis

# 2. Create and activate virtual environment
python -m venv .venv
.venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt
```

## 4. How to run

1. Open the `notebooks` folder in Jupyter / VS Code.
2. Run `01_download_and_eda.ipynb` to download stock data.
3. Run `02_technical_indicators.ipynb` to calculate indicators.
4. Run `03_simple_forecasting.ipynb` to train a forecasting model.

## 5. Files

- `notebooks/`: Jupyter notebooks for analysis
- `data/`: Input and processed CSV files
- `images/`: Exported charts and visualizations
- `src/`: Reusable helper functions
- `requirements.txt`: Python dependencies

## 6. Future work

- Add more assets and sectors.
- Experiment with advanced models (Prophet, LSTM).
- Build an interactive Power BI dashboard for risk and return.
- Automate daily data refresh.
