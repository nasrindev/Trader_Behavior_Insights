# Trader Behavior Analysis & Bitcoin Market Sentiment

## Overview
This project explores the relationship between trader performance and Bitcoin market sentiment. The analysis is performed using historical trader data from Hyperliquid and the Bitcoin Fear/Greed Index. The goal is to uncover hidden patterns and provide insights that can help drive smarter trading strategies.

## Datasets
1. **Historical Trader Data** (`historical_data.csv`)
   - Columns include: account, coin, execution price, size, side, timestamp, start position, closed PnL, leverage, etc.
   - Source: [Google Drive Link](https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing)

2. **Bitcoin Market Sentiment** (`fear_greed_index.csv`)
   - Columns include: timestamp, value, classification, date
   - Source: [Google Drive Link](https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing)

## Methodology
1. **Data Cleaning**
   - Standardized column names and removed spaces
   - Converted timestamps to datetime format
2. **Daily Aggregation**
   - Calculated total PnL, average PnL per trade, and trade count per day
3. **Merge**
   - Merged trader data with market sentiment data on date
4. **Exploratory Data Analysis (EDA)**
   - Summary statistics, correlation, and distribution plots
5. **Advanced Analysis**
   - Time series analysis of total and cumulative PnL
   - Boxplots and histograms by sentiment
   - Statistical testing (T-test) to evaluate differences in PnL between Fear and Greed days
6. **Insights**
   - Traders’ performance varies with market sentiment
   - Visualizations highlight trends in profits and trade activity

## Key Findings
- Average total PnL differs between Fear and Greed days
- Traders tend to make more/less trades depending on market sentiment
- Cumulative PnL visualization shows overall profit trends over time

## Visualizations
- Daily Total PnL vs Market Sentiment (line plot)
- Distribution of PnL (histogram)
- Trade Count by Sentiment (boxplot)
- Correlation Matrix
- Cumulative PnL with Fear/Greed highlights

## How to Run
1. Download both datasets from the links above.
2. Open the Jupyter Notebook `Trader_Behavior_Analysis.ipynb`.
3. Run all cells sequentially to reproduce the analysis and visualizations.

## Author
**Nasrin Sultana**  
Email: nasriinsultana18@gmail.com
# Trader_Behavior_Insights
