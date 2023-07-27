# Bitcoin-Data-Analysis

The Python script performs data analysis and visualization on historical Bitcoin price data using various libraries. Here's a summary of the code:

The script begins by importing necessary libraries: pandas, numpy, seaborn, matplotlib.pyplot, chart_studio.plotly, plotly.graph_objs, and plotly.express.

Next, it reads the Bitcoin price data from a CSV file named "bitcoin_price.csv" and loads it into a pandas DataFrame (df). The script then prints some basic information about the DataFrame, including the first few rows, column names, shape, and data types.

The data is pre-processed by converting the "Date" column to the datetime format and checking the minimum and maximum dates. It also identifies any missing values in the DataFrame.

The code sorts the DataFrame in descending order based on the index and resets the index to create a new DataFrame named "data."

It then visualizes the stock price changes over time for the "Open," "High," "Low," and "Close" prices using four subplots and line plots with matplotlib.

Next, it attempts to create a candlestick chart (OHLC chart) using Plotly, representing the price movements of Bitcoin. However, the code snippet for initializing notebook mode is missing, which could cause errors.

The script continues by analyzing the closing price of Bitcoin, plotting the price over time and applying two different scalings: no scaling and logarithmic scaling.

Finally, the script resamples the closing price data on a yearly, quarterly, and monthly basis to calculate the mean closing price for each period and plots the mean prices on separate figures.

Overall, this code provides a comprehensive analysis and visualization of historical Bitcoin price data.
