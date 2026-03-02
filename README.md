# Crypto Sentiment Trading Analysis

## About the Project

This project explores how market sentiment influences cryptocurrency trading behavior. By combining the Fear & Greed Index with historical trading data, the goal was to understand whether traders behave differently during periods of fear and greed.

The analysis focuses on trader activity, leverage patterns, and performance variations across different sentiment conditions.

---

## What Was Done

- Cleaned and prepared the Fear & Greed Index dataset
- Cleaned and processed historical crypto trading data
- Converted timestamps and aligned dates for accurate merging
- Calculated notional trade value (Size × Execution Price)
- Estimated a leverage proxy using percentile ranking
- Aggregated daily trading metrics (volume, trade count, buy/sell ratio)
- Merged trading metrics with sentiment data
- Compared trader behavior during Fear vs Greed periods
- Analyzed high-leverage vs low-leverage trader patterns

---

## Key Observations

- Trading behavior varies across different sentiment phases.
- High-leverage traders show stronger performance shifts during extreme sentiment conditions.
- Trading activity increases during emotionally driven market periods.
- Sentiment-based analysis provides deeper insights into risk-taking behavior.

---

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Conclusion

This project demonstrates how combining sentiment indicators with transaction-level trading data can reveal behavioral finance patterns and performance differences in cryptocurrency markets.
