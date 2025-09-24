# Trader Sentiment Analysis

This project analyzes trader behavior based on sentiment and market data.

## 📂 Dataset
The datasets are hosted on Google Drive due to size limitations:

- [Historical Trading Data CSV](https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing)

- 
- [Fear Greed Index CSV]:(https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view)

Download them and place them in the same folder as the notebook before running.

## 📒 Notebook
The main analysis is in:  
- `EDA.ipynb`

## 🚀 How to Run
1. Clone the repository  
2. Download datasets from links above and put them in the repo folder  
3. Open the Jupyter notebook and run step by step
   
# Trader Performance vs Market Sentiment

This project explores how Bitcoin market sentiment (Fear, Greed, etc.) affects trader performance using historical trade data.  

## 📊 Steps in Analysis
- Data preprocessing (merge sentiment + trader data)
- Exploratory analysis (PnL, win rates by sentiment)
- Trade split analysis (BUY vs SELL)
- Time-series analysis (PnL vs Sentiment over time)
- Strategy recommendation table

## 🔑 Key Insights
- **Greed → Short aggressively**
- **Fear → Go long cautiously**
- **Extreme Greed → Prefer shorts, cautious longs**
- **Neutral → Avoid trading**

## 📂 Files
- `sentiment_analysis.ipynb` → Main notebook with code & visualizations  
- `fear_greed_index.csv` → Market sentiment data  
- `historical_data.csv` → Trader data  
- `README.md` → Project documentation  

## 💡 Business Impact
This analysis provides actionable trading strategies linked to market sentiment, helping optimize capital allocation and improve profitability.
