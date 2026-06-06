# 📈 Stock Market Analysis and Risk Assessment 💹

## 🎯 Project Overview

This project analyzes selected **NIFTY 50 stocks** using Python to evaluate performance, measure risk, and identify relationships between stocks.
The objective is to apply **data analysis and financial concepts** to transform historical market data into **actionable investment insights** 📊.

# ❓ Problem Statement

Investors often face challenges in:

- 📊 Identifying stocks with strong historical performance  
- ⚠️ Measuring investment risk across different assets  
- 📉 Comparing returns relative to risk exposure  
- 🔗 Understanding stock relationships for diversification  
- 🧠 Making data-driven investment decisions instead of intuition  

This project addresses these challenges using **quantitative stock market analysis**.

# 🎯 Objectives

- ✅ Collect historical stock price data  
- ✅ Analyze stock returns over time  
- ✅ Measure volatility (risk) of stocks  
- ✅ Evaluate risk-adjusted performance (Sharpe Ratio)  
- ✅ Study correlations between stocks  
- ✅ Visualize insights using charts & heatmaps  
- ✅ Generate investment insights based on data  

# 🗂️ Dataset

## 📌 Stocks Analyzed

| Company | Ticker |
|----------|----------|
| HDFC Bank | HDFCBANK.NS |
| ICICI Bank | ICICIBANK.NS |
| Infosys | INFY.NS |
| Reliance Industries | RELIANCE.NS |
| Tata Consultancy Services | TCS.NS |

### 🌐 Data Source
Yahoo Finance (via yfinance)

### 📅 Analysis Period
Start Date: 2023-01-01  
End Date: 2025-01-01

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|----------|
| 🐍 Python | Data Analysis |
| 🐼 Pandas | Data Manipulation |
| 🔢 NumPy | Numerical Computation |
| 📈 Matplotlib | Visualization |
| 🎨 Seaborn | Statistical Visualization |
| 💹 yfinance | Market Data Collection |
| 🌍 GitHub | Version Control |

# 🔄 Project Workflow

## 📥 1. Data Collection
Stock data was collected using the **yfinance API**.

### Observation:
- Includes Open, High, Low, Close, Volume  
- Closing price used for all analysis  

## 📈 2. Return Analysis

Daily returns were calculated to measure stock performance.

### Formula:
Daily Return = (Current Price - Previous Price) / Previous Price

### Insights:
- 📈 Positive → price increase  
- 📉 Negative → price decrease  
- ⚡ Higher magnitude → higher volatility  

## ⚠️ 3. Risk Analysis

Risk is measured using **standard deviation of returns**.

### Formula:
Risk = Standard Deviation of Returns

### Insight:
- Higher risk = higher volatility  
- Lower risk = more stable stock  

## ⚖️ 4. Risk-Adjusted Return

Measures return per unit of risk.

### Formula:
Risk Adjusted Return = Total Return / Risk

## 🏆 5. Sharpe Ratio

Measures performance relative to volatility.

### Formula:
Sharpe Ratio = Mean Return / Standard Deviation

## 🔗 6. Correlation Analysis

Used to understand relationships between stocks.

### Insights:
- High correlation → move together  
- Low correlation → diversification benefit  

## 🌡️ 7. Correlation Heatmap

- Dark colors → strong correlation  
- Light colors → weak correlation  

# 📊 Results Summary

| Metric | Best Performer |
|----------|----------|
| 🚀 Highest Return | ICICI Bank |
| 🛡️ Lowest Risk  | ICICI Bank |
| ⚖️ Best Risk-Adjusted Return | ICICI Bank |
| 🏆 Highest Sharpe Ratio | ICICI Bank |


# 💡 Key Insights

- 📌 Stocks in same sector show strong correlation  
- 📌 Higher returns often come with higher risk  
- 📌 Diversification reduces portfolio risk  
- 📌 Banking stocks performed strongly in this period  

# 📈 Business Impact

This project helps investors:

- 📊 Compare stocks objectively  
- ⚖️ Understand risk vs return tradeoffs  
- 🔄 Improve diversification strategies  
- 📈 Make data-driven investment decisions  

# ⚠️ Limitations

- Historical data ≠ future performance  
- Market conditions can change unexpectedly  
- External economic factors not included  
- Taxes and transaction costs ignored  

# 🚀 Future Improvements

- 📊 Portfolio Optimization  
- 📈 Efficient Frontier Analysis  
- 📉 CAPM & Beta Calculation  
- 📊 Interactive Dashboard (Streamlit / Power BI)  
- 🤖 Automated Data Pipeline  
- ⚡ Real-time Market Analysis  

# ▶️ How to Run

## 1. Clone Repository
git clone <repository-link>

## 2. Install Dependencies
pip install pandas numpy matplotlib seaborn yfinance

## 3. Run Notebook
Open `analysis.ipynb` and execute all cells.

# 📁 Project Structure

Stock_Market_Analysis/
│
├── analysis.ipynb
├── README.md
├── requirements.txt
└── outputs/

# 👩‍💻 Author

Akanksha Kumari
📊 Finance | 📈 Data Analytics | 💹 Quantitative Analysis  

# ⭐ If you like this project, don’t forget to give it a star!
