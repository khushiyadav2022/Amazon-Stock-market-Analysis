# Amazon-Stock-market-Analysis
Helps traders to gain an insight into the economy, stock market, or securities. 

**STOCK MARKET DATA & VISUALISATION**<br>

1 - Fetch the data with different interval and period
It takes the following parameters:
1. ticker: The name of the tickers you want the stock market data for. If you want
stock market data for multiple tickers then separate them by space
2. period: The number of days/month of stock market data required. The valid
frequencies are 1d, 5d, 1mo, 3mo, 6mo, 1y, 2y, 5y, 10y, ytd, max
3. interval: The frequency of the stock market data. The valid intervals are 1m, 2m,
5m, 15m, 30m, 60m, 90m, 1h, 1d, 5d, 1wk, 1mo, 3mo

2 - Resample Stock Data<br>

Convert 1-minute data to 1-hour data or Resample Stock Data 
During strategy modelling, you might be required to work with a custom frequency of
stock market data such as 15 minutes or 1 hour or even 1 month.
If you have minute level data, then you can easily construct the 15 minutes, 1 hour or
daily candles by resampling them. Thus, you don't have to buy them separately.
In this case, you can use the pandas resample method to convert the stock market
data to the frequency of your choice. The implementation of these is shown below
where 1-minute frequency data is converted to 10-minute frequency data.

3 - Visualizing the Stock Data using matplotlib<br>

To visualize the adjusted close price data, you can use the matplotlib library and
plot method.
improve the plot by resizing, giving appropriate labels and adding grid lines for
better readability.

Summary<br>
- Stock analysis is a process followed by traders to evaluate and understand the value of a security or the stock market.<br>
- Stock analysis follows the idea that analysts can create methodologies to select stocks by studying past and present data.<br>
- Fundamental analysis and technical analysis are two broad types of stock analysis.<br>
[Notebook](https://github.com/khushiyadav2022/Amazon-Stock-market-Analysis/blob/1b277f731c0e5bc0b9a4aed815174cd691970b8b/amazon-stock-market-analysis%20(1).ipynb)
