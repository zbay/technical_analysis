# technical_analysis
This project contains some Excel 2013/VBA workbooks that help the user make sense of stock charts.

So far I've made:
* A MACD (Moving Average Convergence Divergence) tracker for US stocks. This helps identify changes in price momentum.
* A Stochastic Oscillator tracker for US stocks. This helps identify stocks trading closely to their recent historical highs or recent historical lows. Is there selling pressure or buying pressure in the market?
* A RSI (Relative Strength Index) tracker for US stocks. This helps identify unusually good and unusually poor stretches ripe for regression.

It is risky to depend on any technical indicator. That being said, if you have a solid grasp of the security's fundamentals, technical analysis will help you appropriately time your purchase or sale.

All of my projects so far make us of Quandl's free API, and cannot retrieve data more granular than the end-of-day OHLC. To use my workbooks will require a Quandl account, API key, and [the Excel Add-In](http://help.quandl.com/category/240-installation). 
