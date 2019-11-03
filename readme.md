This project suggests the top 10 stocks for investment listed under NASDAQ-100.


This project analyzes a total of 101 stocks and chooses the top 10 stocks which are predicted to increase the most in value in the next 6 month duration. The suggestions are generated by analyzing the stock trend using different forecasting models, and selects the best model for each stock to predict the stock trend in future.

For all of our analysis, the daily stock Closing Prices are used for each stock.

Setup:
------

Run the scripts in install.txt to install the necessary libraries in R.

Run:
----

Open R and run the scripts in r-scripts.txt to generate the top suggested stocks.
The results are saved in results/ folder.

After a successful run, the results folder would contains the following:
- **stockdata-*.png** files containing the stock trend for the entire duration for each stock.
- **forecasts-*.png** files containing the forecasts predicted by different models for each stock.
- **results.txt** containing the name of the best model for each stock.
- **results-*.png** files containing the forecast with the best chosen model.
- **top-suggestions.txt** containing the top suggested stocks for investment.
