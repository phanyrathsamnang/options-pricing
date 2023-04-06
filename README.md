# options-pricing

Option is a financial contract that gives the owner the right, but not the obligation, to buy or sell a specific stock at a predetermined price (strike price) within a specified time frame. Both call and put options can be bought and sold on stock exchanges, providing investors with the ability to speculate on the direction of stock prices.

Similar to stock prices which are determined by supply and demand in the stock market, options price are determined by the desirability to buy or sell stocks at the strike price given market conditions. For example, as the price of the underlying asset increases, the price of a call option increases, while the price of a put option decreases.

In this notebook, we explore how different factors affect the price of put and call options. We first build some code to calculate price of call and put options using Black Scholes Model and Monte Carlos Simulation. We then make changes to the following factors to see its impacts on price of call and put options:

price of underlying assets
strike price
time to maturity
volatility of stock
risk-free interest rate
