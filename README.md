# NIFTY 50 Stock Market Analysis

## Overview
This project analyzes historical stock price data of NIFTY 50 companies using Python. The objective is to evaluate stock performance, measure risk, analyze relationships between stocks, and construct a diversified investment portfolio.

---

## Colab Notebook
You can view and run the project directly on Google Colab:

https://colab.research.google.com/drive/1TvUQ44IH_lhIwcHcQqK92xFIMZE1G50_?usp=sharing

---

## Objectives
- Evaluate stock performance using return metrics  
- Measure risk using volatility  
- Analyze relationships between stocks using correlation  
- Construct a diversified portfolio to reduce risk  

---

## Tech Stack
- Python  
- Pandas, NumPy for data analysis  
- Matplotlib, Seaborn for data visualization  

---

## Dataset
The dataset contains historical closing prices of NIFTY 50 stocks.

- Rows represent dates (time series data)  
- Columns represent stock prices of individual companies  

---

## Methodology

### Data Preparation
- Loaded dataset using Pandas  
- Converted the Date column into datetime format  
- Set Date as index for time series analysis  

### Data Cleaning
- Checked for missing values  
- Removed columns with inconsistent or missing data  

### Return Analysis
- Calculated daily percentage returns using price data  
- Identified top and bottom performing stocks  

### Risk Analysis
- Calculated volatility using standard deviation of returns  
- Classified stocks based on risk levels  

### Correlation Analysis
- Computed correlation matrix using returns  
- Visualized relationships using a heatmap  
- Identified sector-wise clustering of stocks  

### Portfolio Construction
- Selected stocks from different sectors  
- Built a diversified portfolio to reduce overall risk  
- Visualized portfolio performance  

---

## Key Insights

### Performance
- Stocks such as BAJAJ-AUTO and BAJAJFINSV showed strong performance  
- Some stocks showed consistent lower returns  

### Risk
- High volatility stocks indicate higher risk  
- Banking stocks showed relatively lower volatility  

### Correlation
- Stocks within the same sector (e.g., banking, IT) are highly correlated  
- Cross-sector stocks show lower correlation, supporting diversification  

---

## Conclusion
The analysis demonstrates that:
- Both return and risk must be considered for investment decisions  
- Diversification across sectors reduces overall portfolio risk  
- Correlation analysis is essential for building efficient portfolios  

---

## Future Improvements
- Portfolio optimization using Sharpe Ratio  
- Predictive modeling using machine learning techniques  
- Development of interactive dashboards using Power BI or Tableau  

---

## How to Run

Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn
