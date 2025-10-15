# FTSE 100 Daily Returns Analysis

This project calculates and visualizes daily percentage changes in the FTSE 100 index.

## What’s included
- **Data cleaning**
- **Daily % change calculation**
- **Line chart visualization**

## Key Takeaways
1. The FTSE 100 can show significant short-term moves.
2. Visualizing daily changes helps spot volatility and trends.
3. Python and Jupyter make quick, reproducible finance analysis easy.

---

**Skills demonstrated:** Python, Pandas, Matplotlib, Data Cleaning, Visualization

## How to run
1. Clone/download this repo.
2. Open `FTSE100_Daily_Returns.ipynb` in Jupyter Notebook.
3. Run all cells.

---

# Visualisations
# Python (Matplotlib)
! [Python Line Chart] (ftse100_pct_change)
*Daily % change in the FTSE 100 calculated and plotted using Python (Matplotlib).*  
<img width="2400" height="1200" alt="ftse100_daily_pct_change" src="https://github.com/user-attachments/assets/f5d6663a-ccea-42a3-99e4-783b5bfd0cab" />

# Excel
![Excel Line Chart](images/excel_returns_chart.png)

*Equivalent Q1 daily % change chart created in Excel for comparison.*  
<img width="517" height="286" alt="image" src="https://github.com/user-attachments/assets/0741bce8-070b-4c48-9f6c-6995eec0557a" />

### Why both Python and Excel?
Excel: Quick, intuitive and used widley in industry practice and for smaller datasets

Python: Excellent and great for large data, for data analysis can work well with larger datasets, better for automation.

Key Insights

Small Average Moves, Occasional Spikes:
The FTSE 100’s average daily return is close to 0%, meaning the index tends to move in small increments day to day. However, there are occasional sharp rises or drops—these spikes often reflect major economic data releases or geopolitical news.

Volatility Exists Even in Stability:
The standard deviation (volatility) of daily changes is around 1%, indicating moderate short-term market swings. This level of fluctuation is typical for large indices like the FTSE 100 and highlights how even “stable” markets have daily uncertainty.

Largest Moves Define Market Sentiment:
The biggest single-day gain was roughly +{max_gain:.2f}%, while the largest drop reached about {max_loss:.2f}%. These moments tend to cluster around macroeconomic events, underlining how market sentiment can shift quickly within days.

Conclusion

This analysis shows that while the FTSE 100 is relatively stable in aggregate, daily returns can fluctuate noticeably. Regular visualization of these changes helps identify volatility clusters and provides a clearer picture of how external events impact UK market performance.
