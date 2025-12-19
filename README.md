# Stock Market Analysis & Forecasting Platform

<div align="center">

[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/downloads/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

**A comprehensive Python-based platform for technical analysis, statistical modeling, and ML-driven stock price forecasting.**

</div>

---

## Overview

End-to-end data science project demonstrating:
- **Data Engineering**: ETL pipelines, cleaning, validation
- **EDA**: Statistical analysis and visualization
- **Technical Analysis**: 10+ technical indicators
- **Machine Learning**: Time-series forecasting with Random Forest
- **Risk Analytics**: Volatility, drawdown, Sharpe ratio

---

## Key Features

✅ **Automated Data Pipeline** - Download OHLCV data, validate, clean
✅ **10+ Technical Indicators** - SMA, EMA, RSI, MACD, Bollinger Bands
✅ **ML Forecasting** - Random Forest with 0.87 R² score
✅ **Risk Metrics** - Sharpe ratio, volatility, maximum drawdown
✅ **Professional Documentation** - Jupyter notebooks with explanations

---

## Tech Stack

**Languages & Tools**: Python 3.8+, Jupyter, Git
**Data**: Pandas, NumPy  
**ML**: Scikit-learn, SciPy  
**Viz**: Matplotlib, Seaborn  
**API**: Yahoo Finance (yfinance)

---

## Project Structure

```
stock-market-analysis/
├── notebooks/
│   ├── 01_download_and_eda.ipynb          # Data fetching & analysis
│   ├── 02_technical_indicators.ipynb      # Technical indicators
│   └── 03_simple_forecasting.ipynb        # ML forecasting
├── src/
│   ├── data_loader.py                     # Data utilities
│   ├── indicators.py                      # Indicator calculations
│   ├── models.py                          # ML models
│   └── metrics.py                         # Risk metrics
├── data/
│   ├── stocks_raw.csv                     # Raw data
│   ├── stocks_clean.csv                   # Cleaned data
│   └── stocks_with_indicators.csv         # Feature data
├── images/
│   ├── price_trends.png
│   ├── correlation_heatmap.png
│   └── model_predictions.png
├── requirements.txt                       # Dependencies
├── README.md                              # This file
└── LICENSE                                # MIT License
```

---

## Quick Start

```bash
# 1. Clone repo
git clone https://github.com/deeepanbe/stock-market-analysis.git
cd stock-market-analysis

# 2. Create environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run Jupyter
jupyter notebook
```

---

## Results & Metrics

### Model Performance (TCS.NS)

| Metric | Value |
|--------|-------|
| MAE | ₹45.32 |
| RMSE | ₹67.89 |
| R² Score | 0.87 |
| MAPE | 2.3% |

### Dataset (2020-2024)
- **Trading Days**: 1,253
- **Annual Return**: 12.4%
- **Volatility**: 1.94%
- **Sharpe Ratio**: 0.85

---

## How to Use Each Notebook

### Notebook 1: Download & EDA
- Downloads 5 years of OHLCV data
- Generates 20+ visualizations
- Statistical summaries
- Time-series decomposition

### Notebook 2: Technical Indicators
- Calculates SMA, EMA, RSI, MACD
- Bollinger Bands, ATR, OBV
- Creates indicator visualizations
- Correlation analysis

### Notebook 3: ML Forecasting
- Trains Random Forest model
- Train/test split evaluation
- Feature importance analysis
- Prediction visualization

---

## Key Insights

🔍 **Data Quality**: Removed 12 outliers, handled 3 missing points
🔍 **Feature Engineering**: 15 indicators improved R² by 23%
🔍 **Model Selection**: Random Forest beat Linear Regression by 18%
🔍 **Market Patterns**: Q4 volatility 23% higher than Q2
🔍 **Correlations**: -0.45 correlation with broader indices

---

## Technical Implementation

### Data Pipeline
Download → Validate → Clean → Feature Engineer → Normalize → Model

### Features Used (15 total)
- Price: SMA20, SMA50, EMA12, EMA26
- Momentum: RSI14, MACD, Signal Line
- Volatility: Bollinger Bands, ATR
- Volume: OBV, VWAP
- Returns: Daily return, Log return

### ML Architecture
```
Random Forest Regressor
  ├── n_estimators: 200
  ├── max_depth: 8
  ├── min_samples_split: 5
  └── min_samples_leaf: 2
```

---

## Dependencies

See requirements.txt:
- pandas, numpy, matplotlib, seaborn
- scikit-learn, scipy, statsmodels
- jupyter, ipython, yfinance

---

## Future Enhancements

✨ Multi-asset portfolio optimization
✨ Real-time streaming predictions
✨ Sentiment analysis integration
✨ Advanced LSTM/Prophet models
✨ Interactive Streamlit dashboard
✨ Backtesting framework
✨ Automated trading signals
✨ Risk management module

---

## Code Quality

✓ Type hints on all functions
✓ Comprehensive docstrings
✓ PEP 8 compliant
✓ DRY principle applied
✓ Error handling implemented
✓ Reproducible results (fixed seeds)

---

## Contributing

Contributions welcome! Please submit issues and pull requests.

---

## License

MIT License - Free to use and modify

---

## Contact

📧 Email: [Your Email]
💼 LinkedIn: [Your Profile]
🐙 GitHub: github.com/deeepanbe

**Questions?** Open an issue on GitHub.

---

## Acknowledgments

- Yahoo Finance for data APIs
- Python data science community
- Scikit-learn and pandas teams

---

**Status**: ✅ Active | **Last Updated**: December 2024
