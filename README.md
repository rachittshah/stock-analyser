# portfolio-analyzer

This is a Portfolio Analyzer tool built using Python's Streamlit library. It allows users to input the names or symbols of the stocks in their portfolio, along with a start and end date for the data analysis. The tool then retrieves historical closing prices for those stocks from the National Stock Exchange of India (NSE) using the nsepy library and performs various analysis on the data.

The tool first displays the symbols of the stocks in the portfolio and then shows a historical dataframe of the closing prices for the selected timeframe. It also displays a line chart of the closing prices for better visualization. Additionally, it calculates the correlation matrix between the stocks in the portfolio, which can be useful in understanding the relationship between the stocks.

To run:

- Clone the repo using ```git clone https://github.com/rachittshah/stock-analyser```
- Install requirements using ```pip3 install -r requirements.txt```
- To run the app locally: ```streamlit run streamlit_app.py```

Deployed version: [link](https://rachittshah-stock-analyser-streamlit-app-o9pa16.streamlit.app/)
