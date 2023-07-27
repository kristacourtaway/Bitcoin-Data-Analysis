# Bitcoin-Data-Analysis

This Python code is a data analysis and visualization script that works with historical Bitcoin price data. The script uses various libraries such as pandas, numpy, seaborn, matplotlib, and Plotly to load, preprocess, analyze, and visualize the data.

Here's a summary of what the code does:

It imports essential libraries for data analysis and visualization, including pandas, numpy, seaborn, matplotlib, chart_studio.plotly, plotly.graph_objs, and plotly.express.

The code reads Bitcoin price data from a CSV file named "bitcoin_price.csv" and stores it in a pandas DataFrame (df). The code then displays some basic information about the DataFrame, such as the first few rows, column names, shape, and data types.

The script performs data preprocessing, converting the "Date" column to the datetime format, checking the minimum and maximum dates, and identifying any missing values.

It creates a new DataFrame "data" by sorting the original DataFrame in descending order based on the index and resetting the index.

The script then proceeds to visualize the stock price changes over time using matplotlib. It plots four line charts (Open, High, Low, and Close) in a 2x2 subplot arrangement.

The code attempts to create a candlestick chart (OHLC chart) using Plotly, representing the price movements of Bitcoin over a sample of 50 data points. However, there is an import statement for notebook mode initialization that is commented out, which needs to be resolved for the code to function correctly.

Next, the script analyzes the closing price of Bitcoin and plots the price over time. It also creates two subplots, one without any scaling and the other with logarithmic scaling.

Finally, the script resamples the closing price data on a yearly, quarterly, and monthly basis and calculates the mean closing price for each period. It then plots the mean prices for each period.

In summary, this Python script performs data exploration and visualization on historical Bitcoin price data. It visualizes the stock price changes using matplotlib and creates a candlestick chart using Plotly. Additionally, it provides insights into the closing price trends over different time intervals using resampling techniques.
