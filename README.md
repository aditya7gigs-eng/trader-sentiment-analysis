Trader Sentiment Analysis

This project analyzes the relationship between trader performance and Bitcoin market sentiment.
The goal is to understand how different sentiment phases (fear, greed, extreme greed, neutral) influence trading outcomes and suggest strategies.

📂 Dataset

The datasets are hosted on Google Drive due to size limitations:

Historical Trading Data CSV

Fear & Greed Index CSV

👉 Download them and place in the same folder as the notebook before running.

📒 Notebook

The main analysis is inside the Jupyter notebook:

EDA.ipynb

🔄 Project Steps

Data Loading & Cleaning

Imported historical trading data and Fear & Greed sentiment index

Handled missing values and aligned timestamps

Exploratory Data Analysis (EDA)

Checked distributions of PnL, trade outcomes, and sentiment levels

Visualized trade counts across different sentiment labels

Win Rate Analysis

Split trades into wins/losses

Compared win rates across sentiment phases

Time Series Analysis

Plotted trader PnL trends against sentiment index over time

Observed volatility during extreme sentiment phases

Strategy Table

Summarized actionable trading strategies based on observed behavior, win rates, and sentiment conditions

📈 Key Results
🔹 Time Series Insight

Trader PnL trends compared with sentiment index show higher volatility during extreme sentiment periods.

🔹 Strategy Table
Sentiment	Observed Behavior	Win Rate	Suggested Action
Extreme Greed	SELL > BUY	~52%	Prefer shorts, caution longs
Greed	SELL dominant	~61%	Short aggressively
Fear	BUY dominant	~41%	Go long cautiously
Neutral	Mixed, weak edge	~32%	Avoid trading
🎯 Business Objective

Help traders align strategies with market psychology

Provide risk management insights (avoid trading during neutral phases)

Improve decision-making with data-driven sentiment analysis

👤 Author

Aditya
📌 GitHub: aditya7gigs-eng
