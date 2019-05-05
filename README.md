# Stock_Screener
Stock Screen based on Piotroski's F-Score and Quandl database. Inputs are the fundamental data of the thirty tickers and the outputs are the ranking and scores of each tickers

# Installaltion Instruction
   Install Anaconda
   Install Jupyter notebook
   Install pandas
   Install quandl
   Install Numpy
   
# Download Quandl
Sign up a free quandl account. Then you can get some sample data free from quandl.
The free data are fundamentals data of the tickers below:
ticker['AAPL','AXP','CAT','CSCO','CVX','DD','DIS','GE','GS','HD','IBM','INTC','JNJ','JPM','KO','MCD','MMM','MRK','MSFT','NKE','PFE','PG','TRV','UNH','UTX','V','VZ','WMT','XOM']

# Set up quandl api key
Replace the <you key> in api key set up with your own api key
quandl.ApiConfig.api_key=<you key>

# Run the stock_screener file
Then you will get the ranking and the scores of these stocks.





