# 📈 ADANIPORTS Stock Analysis Notebook

**Linear Regression model predicting opening prices from closing prices using NSE:ADANIPORTS stock data**

## ✨ Features
- **Data Preprocessing**: Mean imputation for missing `Deliverable Volume` & `Trades`
- **ML Pipeline**: Linear Regression (`Open ~ Close`) with MSE/R² evaluation
- **Financial Visualizations**:
  - Candlestick charts with 3/6/9 Moving Averages + Volume (mplfinance)
  - Residual analysis plots
  - Open vs Close scatter plots (matplotlib/seaborn)
  - Time series trend analysis

## 📊 Output
- **Model Metrics**: MSE, R² Score
- **Clean Dataset**: `ADANIPORTS_CLEANED.csv`

## 🛠️ Tech Stack
Python 3.8+ | scikit-learn | pandas | numpy | matplotlib | seaborn | mplfinance
