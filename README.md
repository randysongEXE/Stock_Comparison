# Stock_Comparison

This is a simple stock comparison dashboard that uses the Bokeh library in Python to visualize stock data. The user inputs two stock tickers and a date range, and the program generates candlestick charts for those two stocks within the specified date range.

Prerequisites
------
- Bokeh library 
- yfinance library 
- numpy 

Installation
-------
You can install the necessary libraries with pip:
- pip install bokeh yfinance numpy

Usage
------
To successfully run this code, it must be done through a Bokeh server. To set this up, navigate to your IDE's terminal or the command prompt and find the correct directory that the .py file is located in. Next, use this command prompt:
- bokeh serve --show main.py

If your file is named differently, please make according changes to "main.py" in the command line.

Once this is completed, the dashboard should appear on your screen. Enter the ticker symbol of the stocks that you want to compare, set the date, and click "load data". This should generate two seperate candlestick charts which you can then compare.
