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

---

## 📂 Project Structure

.
├── data/
│ ├── financial_news.csv
├── notebooks/
│ ├── task_1_eda_sentiment_analysis.ipynb
│ ├── task_2_technical_indicators.ipynb
│ └──
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

---

## 📊 Tools & Libraries Used

- `pandas`, `matplotlib`, `seaborn` – Data wrangling & visualization
- `nltk` – Natural language processing
- `TA-Lib` – Technical indicators
- `PyNance` – Financial metrics and analysis tools
- `jupyter` – Notebooks for exploratory and analytical work

---

## 📝 Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/dagmaros27/Financial-news-sentiment-analysis.git
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
