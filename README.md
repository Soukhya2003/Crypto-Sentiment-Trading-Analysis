# Crypto Sentiment Trading Analysis

## About the Project

This project explores how market sentiment influences cryptocurrency trading behavior. By combining the Fear & Greed Index with historical trading data, the goal was to understand whether traders behave differently during periods of fear and greed.

The analysis focuses on trader activity, leverage patterns, and performance variations across different sentiment conditions.

---

## Problem Statement

Cryptocurrency markets are highly volatile and often driven by emotional cycles. This project investigates:

- Does trader performance differ during Fear vs Greed market conditions?
- Do traders change their trading behavior based on sentiment?
- How does leverage usage vary across sentiment cycles?

---

## Dataset

The analysis is based on two datasets:

1. Fear & Greed Index Dataset  
   - Daily market sentiment classification (Fear, Greed, Neutral)
   - Timestamp-based sentiment values

2. Historical Crypto Trading Dataset  
   - Execution price  
   - Trade size (tokens)  
   - Buy/Sell side  
   - Account-level transaction data  
   - Timestamped trading records  

**Note:** Due to GitHub’s 25MB file size limit, a reduced sample of the trading dataset is uploaded. The full dataset (~45MB) was used during analysis.

---

## Methodology

- Data cleaning and preprocessing
- Timestamp conversion and date alignment
- Calculation of notional trade value (Size × Execution Price)
- Leverage proxy estimation using percentile ranking
- Daily aggregation of trading metrics (volume, trade count, buy/sell ratio)
- Merging trading metrics with daily sentiment data
- Sentiment-based performance comparison
- High vs Low leverage trader segmentation

---

## Key Observations

- Trading behavior varies across different sentiment phases.
- High-leverage traders show stronger performance shifts during extreme sentiment conditions.
- Trading activity increases during emotionally driven market periods.
- Sentiment-based analysis provides deeper insight into risk-taking patterns.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Conclusion

This project demonstrates how combining sentiment indicators with transaction-level trading data can uncover behavioral finance patterns and performance differences in cryptocurrency markets.
