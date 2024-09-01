# Bitfinex
To summarize, the assignment is described below:

Objective: Create an order execution and management system to trade on Bitfinex (v2)

Where to start:
•⁠  ⁠Create a new Bitfinex account (verify your email and setup 2FA)
•⁠  ⁠Create a sub account for paper trading (verify your email and setup 2FA)
•⁠  ⁠Generate a set of API Key and Secret for your paper account
•⁠  ⁠Top up your paper trading account with fake money (10,000 USD should be sufficient)

https://support.bitfinex.com/hc/en-us/articles/900001525006-Paper-Trading-at-Bitfinex-test-learn-and-simulate-trading-strategies

Functions:
- Place order (Submit order)
    - Place a limit order using symbol (tTESTBTC:TESTUSD) to buy 0.1 BTC for USD at a price higher than the best ask (order should not fill)
- Modify order (Order Update)
   - Modify the place order above (make sure the order does not fill)
- Cancel order
    - Cancel the order (from above)
- Get orderbook (Get Book for BTCUSD)
- View current positions (Retrieve positions)

Scope:
•⁠  ⁠Spot, futures and options
•⁠  ⁠All supported symbols

Focus:
- Full functionality of above functions with low latency

Advanced Bonus:
•⁠  ⁠Create a websocket server that clients can connect to and subscribe to a symbol by sending a message.
•⁠  ⁠The server should respond with a stream of messages with the orderbook updates for each symbol that is subscribed 
