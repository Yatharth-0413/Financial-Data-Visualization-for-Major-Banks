# Financial-Data-Visualization-for-Major-Banks

## Project Overview

This project analyzes the stock performance of major banks (Bank of America, CitiGroup, Goldman Sachs, JPMorgan Chase, Morgan Stanley, Wells Fargo) from January 1, 2006, to January 1, 2016. The analysis includes fetching stock data, examining closing prices, calculating returns, visualizing data, and performing technical analysis. This project provides insights into the financial crisis and its impact on bank stocks, using various data visualization techniques and statistical measures.

## Data Collection

Stock data is fetched using the Yahoo Finance API via the yfinance library. The data covers the period from January 1, 2006, to January 1, 2016.

## Libraries Used

- pandas
- numpy
- yfinance
- matplotlib
- seaborn
- cufflinks
- plotly

## Steps Performed

1. **Data Collection**: Fetched stock data for the banks from Yahoo Finance.
2. **Data Preparation**: Created individual DataFrames for each bank and concatenated them into a single DataFrame with multi-level columns.
3. **Exploratory Data Analysis (EDA)**:
   - Analyzed the maximum closing and opening prices.
   - Calculated daily returns and visualized them using pairplots.
   - Identified dates with the best and worst single-day returns.
   - Calculated the standard deviation of returns to assess risk.
4. **Visualizations**:
   - Plotted closing prices for each bank.
   - Analyzed moving averages.
   - Created heatmaps and clustermaps of stock correlations.
5. **Technical Analysis (Optional)**:
   - Created candle plots.
   - Plotted simple moving averages.
   - Plotted Bollinger Bands.

## How to Run

1. Install the required libraries:
   ```bash
   pip install pandas numpy yfinance matplotlib seaborn cufflinks plotly
2. Run the Jupyter notebook or Python script.
