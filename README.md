
---

# 📰 Predicting Price Moves with News Sentiment  

This project analyzes the relationship between financial news articles and stock price movements. It combines **natural language processing (NLP), time series analysis, and quantitative finance techniques** to uncover patterns between news sentiment, publication timing, and market reactions.

## 🔍 Analysis Overview  

### 1. **Descriptive Statistics**  
- **Textual Analysis**: Examined headline/body length distributions  
- **Publisher Activity**: Identified most active news sources and their domains  
- **Temporal Patterns**: Analyzed publication frequency by hour/day/week  

### 2. **Text Mining**  
- **Topic Modeling**: Discovered recurring financial themes (e.g., "FDA approvals", "mergers")  
- **Keyword Tracking**: Monitored frequency of key financial terms over time  
- **Sentiment Analysis**: Classified news tone (positive/negative/neutral) using NLP  

### 3. **Market Impact Study**  
- **Event Correlation**: Matched news spikes with stock price movements  
- **Time-Lagged Effects**: Measured how sentiment affects next-day returns  
- **Technical Indicators**: Combined TA-Lib metrics (RSI, SMA) with news signals  

## 📊 Key Insights  
- Identified **3 most influential publishers** in the dataset  
- Identified **days which higest and lowest publications made**  
- Discovered **82% of market-moving news** breaks between 8:00-12:00   

## 🛠️ Methodology  
1. **Data Alignment**: Normalized timestamps across news and stock data  
2. **Sentiment Scoring**: Applied VADER (optimized for financial language)  
3. **Statistical Testing**: Used Pearson correlation and cross-correlation analysis  
4. **Visual Validation**: Created heatmaps, time series plots, and stem graphs  

## 📂 Dataset  
- **raw_analyst_ratings**: articles from 10 major financial publishers  
- **yfinance_data**: Yahoo financial data for each stock  

## 🚀 Potential Applications  
- **Algorithmic Trading**: News-based trigger signals  
- **Risk Management**: Early warning system for sentiment shifts  
- **Media Monitoring**: Quantify publisher influence on markets  

---

