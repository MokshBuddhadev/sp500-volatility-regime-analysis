# S&P 500 Volatility Regime Analysis

## Project Overview
This project analyzes historical S&P 500 index data to identify distinct market regimes based on volatility and risk characteristics using unsupervised machine learning. The objective is to uncover hidden structure in market behavior rather than forecast future prices.

## Objectives
- Transform raw price data into meaningful financial features  
- Quantify market risk using rolling volatility measures  
- Engineer stress-related indicators  
- Apply clustering techniques to detect market regimes  
- Interpret and visualize regime behavior  

## Dataset
Daily historical S&P 500 index data obtained using Yahoo Finance.

## Feature Engineering
The following features were created:
- Daily Returns  
- 20-day Rolling Volatility  
- 50-day Rolling Volatility  
- 20-day Rolling Average Return  
- Drawdown (distance from historical peak)  

## Methodology
1. Data acquisition and cleaning  
2. Computation of daily returns  
3. Rolling volatility calculation  
4. Stress feature engineering  
5. Feature selection and standardization  
6. K-Means clustering  
7. Regime interpretation and visualization  

## Results
Three distinct market regimes were identified:
- Calm Regime (low volatility, positive average returns)  
- Transition Regime (moderate volatility, mixed returns)  
- Stress Regime (high volatility, negative returns, deep drawdowns)  

## Tools and Libraries
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  
- Jupyter Notebook  

## Key Takeaways
- Market behavior changes over time and is not stationary  
- Periods of high volatility and drawdowns tend to cluster  
- Unsupervised learning can effectively identify hidden market states  

## Future Work
- Optimize number of clusters  
- Add macroeconomic indicators  
- Explore regime-based trading strategies  
