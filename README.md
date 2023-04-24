# StocksCode

FetchStockPrice.py 
--> will fetch symbols from Column A from the Excel File -> Get the Current Share Price data from the URL https://www.google.com/finance/quote/{}?hl=en -> Put the Result in Column B of same sheet.



Improvements
1. Fetch Symbols from the NSE Website 
2. Filter Symbols 
  a. some strategy 
  b. some market capital etc. 
3. Put the filtered Symbol in another sheet
4. Get the share price of last No of Year(in property file) with some specific interval(property file) from API , or Google Finance. 
5. Get 1 Minute Share Price as well



ToDo - Sort Stocks based on 
1. Last Trade Price. 
2. Market Capital / LTP -> PE ratio
3. Weekly Breakout -> then based on LTP or based on Reward Ratio
4. Monthly Breakout -> then based on LTP or based on Reward Ratio
5. Moving Average , Exponenential Moving Average
6. 52 Week High - 5 % , 2% , 1% 
7. 52 Week Low + 5 % , 10% 
8. continuous 3 day gainers
9. continuous 5 day gainers
10. 3 Day high , 5 day high , Month High , 2 Month High , 6 Month High
11. Moving from Support1 -> Resistance1 
12. Moving from Resistance -> Resistance2
13. 
