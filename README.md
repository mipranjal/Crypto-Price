# Crypto-Price
This is a Streamlit app that retrieves cryptocurrency prices for the top 100 cryptocurrencies from CoinMarketCap.

## Installation
To run this app, please install the required dependencies using pip:

### Copy code
pip install streamlit pandas matplotlib seaborn BeautifulSoup4 requests Pillow
### How to Use the App
After installing the required dependencies, run the app by executing the following command:

arduino
Copy code
streamlit run app.py
When the app is launched, you will see a sidebar on the left-hand side of the screen with several input options:

Select currency for price: choose the currency unit for displaying cryptocurrency prices.
Cryptocurrency: select the cryptocurrencies you want to display data for.
Display Top N Coins: choose the number of coins you want to display data for.
Percent change time frame: select the time frame for percentage changes in price data (7 days, 24 hours, or 1 hour).
Sort values?: choose whether to sort the data by market capitalization.
The right-hand side of the screen will display a table with the price data for the selected cryptocurrencies. You can download this data in CSV format by clicking on the "Download CSV" button.

## Disclaimer
This app is for educational purposes only. Any insights gained from the data displayed in this app should not be considered financial advice. Use at your own risk!




