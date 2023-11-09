### About
<img width="819" alt="screenshot" src="https://github.com/ArcticKangaroo/CS50-Finance/assets/62847649/94e8eb81-0ec1-464e-b3aa-24df1a8eec46">
A web app for managing a stock portfolio, making transactions, and checking real-time stock prices using the IEX API.

#### Register
Allow a new user to register for an account, rendering an apology view if the form data is incomplete or if the username already exists in the database.

#### Index
The homepage displays a table of the logged-in user's owned stocks, number of shares, current stock price, value of each holding. This view also shows the user's imaginary "cash" balance and the total of their "cash" plus stock value.

#### Quote
Allows the user to submit a form to look up a stock's current price, retrieving real-time data from the IEX API. An error message is rendered if the stock symbol is invalid.

#### Buy
Allows the user to "buy" stocks by submitting a form with the stock's symbol and number of shares. Checks to ensure the stock symbol is valid and the user can afford the purchase at the stock's current market price with their available balance, and stores the transaction history in the database.

#### Sell
Allows the user to "sell" shares of any stock currently owned in their portfolio.

#### History
Displays a table summarizing the user's past transactions (all buys and sells). Each row in the table lists whether the stock was bought or sold, the stock's symbol, the buy/sell price, the number of shares, and the transaction's date/time.

### Technologies
    Python
    Flask  
    SQL
    HTML
    Bootstrap
