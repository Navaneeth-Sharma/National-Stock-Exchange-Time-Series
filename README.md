# Time Series - Finance

A notebook for stock price prediction using time series data. Explore the stock prices for different IT companies. Peform model driven analysis on the dataset. Check that if the future stock prices is forecastable. If forecast could me made, use different statiscal and ANNs to forecast the stock prices. Improve the model, make better forecasts.

## 1. Problem

Given, the record of stock prices in a particular year, forecast the future price. **(Time-Series Forecasting)**

## 2. Data

Source: https://www.kaggle.com/atulanandjha/national-stock-exchange-time-series

National Stock Exchange is an indian stock exchange in Mumbai.
Our dataset contains three csv files. Each resembling to INFOSYS, NIFTYITINDEX, and TCS, respectively.

**Timeline of Data recording** : 1-1-2015 to 31-12-2015.

### Data Dictionary

1. **Date** - date on which data is recorded
2. **Symbol** - NSE symbol of the stock
3. **Series**- Series of that stock | EQ - Equity
4. **Prev Close** - Last day close point
5. **Open** - current day open point
6. **High** - current day highest point
7. **Low** - current day lowest point
8. **Last** - final quoted trading price for a particular stock, during the most recent day of trading.
9. **Close** - Closing point for the current day
10. **VWAP** -volume-weighted average price is the ratio of the value traded to total volume traded over a particular time horizon
11. **Volume** - the amount of a security that was traded during a given period of time. For every buyer, there is a seller, and each
    transaction contributes to the count of total volume
12. **Turnover** - Total Turnover of the stock till that day
