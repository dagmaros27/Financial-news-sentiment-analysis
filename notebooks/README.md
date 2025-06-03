# Financial News Exploratory Data Analysis (EDA) Report

## Task Overview

This report summarizes the exploratory data analysis (EDA) performed on a financial news dataset as part of the weekly assignment. The main objectives were:

- Set up a GitHub repository and use a dedicated branch (`task-1`) for the analysis.
- Commit work regularly with descriptive messages.
- Analyze the dataset using descriptive statistics, text analysis, time series analysis, and publisher analysis.

---

## 1. Descriptive Statistics

**Headline Lengths:**  
We analyzed the distribution of headline lengths to understand the typical size of news headlines. The histogram shows that most headlines are concise, with a moderate spread, indicating a preference for brief and informative titles in financial news.

**Articles per Publisher:**  
A bar chart of article counts per publisher revealed that a few publishers dominate the news feed, while many others contribute only occasionally. This highlights the importance of major financial news outlets in shaping market sentiment.

**Publication Trends Over Time:**  
A time series plot of articles published per day showed a significant spike in 2020, likely due to the COVID-19 pandemic and its impact on global markets. Article frequency has since stabilized but remains higher than pre-pandemic levels.

---

## 2. Text Analysis (Topic Modeling)

**Keyword and Phrase Extraction:**  
Using NLP techniques, we cleaned the headlines and generated a word cloud and bigram frequency chart. Common phrases included "price target", "stock moving", "market update", "initiates coverage", and "earnings report". These reflect the dataset's focus on financial performance, analyst opinions, and market events.

---

## 3. Time Series Analysis

**Publication Frequency:**  
Analysis of publishing times showed that most articles are released during weekdays, especially on Mondays and Fridays, aligning with the business week. The most active publishing hours are between 10:00 AM and 2:00 PM, which coincides with peak market activity.

**Event-Driven Spikes:**  
Spikes in article frequency often correspond to major market events or earnings seasons, indicating that news coverage intensifies during periods of high market volatility or significant financial announcements.

---

## 4. Publisher Analysis

**Top Publishers and Domains:**  
By extracting domains from publisher email addresses, we identified that `benzinga.com` is the most prolific source, followed by `gmail.com`. This suggests that both established financial news outlets and individual contributors (using Gmail) play key roles in disseminating market information.

**Content Differences:**  
While the dataset is dominated by a few publishers, further analysis could explore whether these sources differ in the types of news they report (e.g., breaking news vs. analysis).

## 5. Quantitative Analysis (Stock Price Data)

**Technical Indicator Analysis:**  
We analyzed historical stock data for major companies (AAPL, AMZN, GOOG, META, MSFT, NVDA, TSLA) using technical indicators:

- **Simple Moving Average (SMA 20):**  
  The 20-day SMA shows the general trend of the stock prices, with most stocks exhibiting a strong upward trend over the period.

- **Relative Strength Index (RSI):**  
  For most stocks, the RSI is above 70, indicating overbought conditions.

- **MACD (Moving Average Convergence Divergence):**  
  The MACD line is above the signal line for all three highlighted stocks (AAPL, META, MSFT), suggesting a bullish trend.

- **Bollinger Bands:**  
  Stocks are trading near the upper band, further suggesting overbought conditions.

**Summary of Findings:**

- The technical indicators collectively point to a strong bullish trend and possible overbought conditions for the analyzed stocks.
- These quantitative signals, combined with news sentiment and frequency, can provide valuable insights for trading strategies.

## Conclusion

The EDA provided valuable insights into the structure and content of financial news data:

- News coverage is concentrated among a few publishers.
- Headline content is focused on actionable financial topics.
- Publication timing aligns with market hours and events.
- Both institutional and individual sources contribute to the news flow.

These findings can inform downstream tasks such as sentiment analysis, event detection, and automated trading strategies.
