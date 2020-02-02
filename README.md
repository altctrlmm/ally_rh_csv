![Python package](https://github.com/altctrlmm/Robinhood-Watchlist-Stock-History/workflows/Python%20package/badge.svg)

# Robinhood-Watchlist-Stock-History
Download stock quote history from AlphaVantage for all the symbols in your Robinhood Default Watchlist to csv files. There is one file per symbol.

# How to Get Started

1. Run:<br/>
$ pip install -r requirements.txt

2. Open preferences.txt

3. Update:<br/>
A. Your free AlphaVantage API key<br/>
B. Your Robinhood email<br/>
C. Your Robinhood password<br/>
D. Your path to where to place the csv files.

4. Rename preferences.txt to preferences.py

5. Open dl_quotes.py and run it.

# When symbols fail
If symbols fail, you can re-run the code and download only the list of failed symbols. The list is provided by the code. You'll have to copy/paste the list, and comment/uncomment several lines. Detailed instructions are in the code.

# Example of the csv file (ALLY)
date,1. open,2. high,3. low,4. close,5. volume<br/>
2020-01-31,32.2,32.325,31.85,32.03,3968506.0<br/>
2020-01-30,31.74,32.495,31.69,32.45,4338968.0 

# Big Thanks
Big thank you to Robinhood for being the no-commission pioneer and also making an API available for free; 
also a big thanks to JMFernandes at <a href="https://github.com/jmfernandes/robin_stocks">https://github.com/jmfernandes/robin_stocks</a> for creating a python code for the Robinhood API. 