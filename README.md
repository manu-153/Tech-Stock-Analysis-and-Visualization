# Tech Stock Analysis and Visualization

## Project Overview

This project provides an in-depth analysis and visualization of historical stock prices for major technology companies. The analysis includes plotting historical prices, calculating moving averages, evaluating daily returns, and examining correlations between different tech stocks.

## Companies Analyzed

- Amazon.com, Inc. (AMZN)
- Apple Inc. (AAPL)
- Google LLC (GOOG)
- Microsoft Corporation (MSFT)

## Project Details

### Data Collection

- **Data Source**: Yahoo Finance
- **Date Range**: From the beginning of the previous year to the current date

### Key Features

- **Historical Price Plotting**: Visualize the historical adjusted closing prices for each tech stock.
- **Moving Averages**: Calculate and plot moving averages over different time periods (10, 20, 50 days) to identify trends.
- **Daily Returns**: Compute and plot daily returns to assess stock volatility.
- **Correlation Analysis**: Evaluate and visualize the correlations between different stocks' returns and closing prices.
- **Scatter Plots**: Analyze the relationship between expected return and risk.

### Implementation

1. **Data Retrieval**: 
   - Historical stock data for the selected companies is fetched using the `yfinance` library.

2. **Data Preparation**:
   - Data is cleaned and processed, including calculating moving averages and daily returns.
   - Data is visualized using `matplotlib` and `seaborn` for comprehensive insights.

3. **Visualization**:
   - Historical price trends, moving averages, daily returns, and correlation heatmaps are plotted.
   - Scatter plots are used to show the relationship between expected returns and risk.

## Project Structure

- `stock_analysis.py`: Contains the code to fetch data, compute metrics, and generate visualizations.
- `requirements.txt`: Lists the necessary packages to run the project.

## Results

- **Visualizations**: 
  - Historical price trends and moving averages for each company.
  - Daily returns and their distributions.
  - Correlation heatmaps of stock returns and closing prices.
  - Scatter plots of expected return versus risk.

- **Performance Metrics**:
  - No specific performance metrics are included, but insights into stock trends and relationships are provided through the visualizations.

## Future Improvements

- **Enhanced Analysis**:
  - Include additional technical indicators (e.g., RSI, MACD) for a more comprehensive analysis.
  - Perform sentiment analysis of financial news to augment predictions.

- **Extended Data**:
  - Expand the analysis to include more companies or other asset classes (e.g., commodities, currencies).

- **Interactive Visualizations**:
  - Develop interactive web-based visualizations for more dynamic exploration of the data.


