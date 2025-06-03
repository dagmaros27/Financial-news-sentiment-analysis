# 📊 Financial News Sentiment & Stock Price Analysis

This repository contains the work for a financial analytics challenge at **Nova Financial Solutions**. The primary goal is to analyze financial news data and correlate sentiment with historical stock price movements of major tech companies.

---

## 🚀 Project Overview

**Business Objective**:
Enhance predictive analytics capabilities by analyzing how financial news sentiment affects stock market movements, and provide actionable insights to guide investment strategies.

**Companies Analyzed**:

- Apple (AAPL)
- Amazon (AMZN)
- Google (GOOGL)
- Meta (META)
- Microsoft (MSFT)
- Nvidia (NVDA)
- Tesla (TSLA)

## 📂 Project Structure

.
├
├── notebooks/
│ ├── financial_news_analysis_eda.ipynb
│ ├── financial_data_quantitative_analysis.ipynb
│ └── news_sentiment_analysis.ipynb
├── utils/
├── requirements.txt
└── README.md

## ✅ Tasks

### Task 1: Exploratory Data & Sentiment Analysis

- Performed EDA on financial news dataset
- Analyzed headline lengths, publisher distribution, and temporal trends
- Used NLTK for basic text processing and extracted frequent keywords
- Prepared foundation for sentiment analysis

### Task 2: Technical Indicators & Price Data

- Loaded and cleaned stock price data for 7 companies
- Applied technical analysis indicators (Moving Average, RSI, MACD) using **TA-Lib**
- Calculated financial metrics using **PyNance**
- Visualized stock trends and indicator overlays

### Task 3: Correlation between News Sentiment and Stock Movement

- Aligned financial news and stock price datasets by date, normalizing timestamps for consistency.
- Conducted sentiment analysis on news headlines using **NLTK** and **TextBlob** to quantify the tone (positive, negative, neutral) of each article.
- Calculated daily stock returns by computing the percentage change in daily closing prices.
- Performed correlation analysis to statistically test the relationship between daily news sentiment scores and stock returns.
- Aggregated daily sentiment scores (e.g., average) when multiple articles appeared on the same day.
- Determined the Pearson correlation coefficient between aggregated daily sentiment scores and stock daily returns.

---

## 📊 Tools & Libraries Used

- `pandas`, `matplotlib`, `seaborn` – Data wrangling & visualization
- `nltk`, `TextBlob` – Natural language processing and sentiment analysis
- `TA-Lib` – Technical indicators
- `PyNance` – Financial metrics and analysis tools
- `jupyter` – Notebooks for exploratory and analytical work

---

## 📝 Setup Instructions

1. Clone the repository:
   ```bash
   git clone [https://github.com/dagmaros27/Financial-news-sentiment-analysis.git](https://github.com/dagmaros27/Financial-news-sentiment-analysis.git)
   cd financial-news-sentiment-analysis
   ```
2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Add the data file to the `data/` directory:

   - Download the financial news dataset and place it in the `data/` directory.

5. Launch Jupyter notebooks:
   ```bash
   jupyter notebook
   ```
6. Open the notebooks in your browser and start analyzing!

```bash
# Launch Jupyter Notebook
jupyter notebook
```
