# Wheeling
The Wheeler Strategy


# Step #1: Stock Selection 

* A profitable company that has solid cash flow
* Bullish, or at least neutral chart trend and analyst ratings
* Share price where the account can easily accept being assigned 100 shares if needed. (I stay away from sub-$10 stocks as a rule)
* A stable to bullish trending chart without wild gyrations (especially those caused by CEO tweets)
* A nice dividend is always a good thing, both that you may collect it if assigned the stock but also that dividend stocks tend to be more stable and predictable

# Step #2: Sell Cash Secured Puts

To start the wheel begins by selling short (naked) Puts, or (CSPs) Cash Secured Puts (indicating the account has the cash, or cash+margin to buy the shares if assigned. Be aware of any upcoming ER or other events that could cause a spike or movement in the stock and it is best to close or have the Put expire prior, in effect skipping it to then continue selling puts afterward if the stock still meets the criteria.

Selling Puts Process - Below is a suggested model, but details are up to the individual trader:

* Opening at 30 to 45 DTE offers a good premium as the theta/time decay starts to accelerate
* 70% Prob OTM (~.30 Delta) offers high probability of success while collecting a good premium
* The number of contracts is based on account size able to handle assignment
* Opening at 5% max risk to the account is good practice, and keeping ~50% of the trading account in cash helps manage market downturns, assignments and trading opportunities
* The Put can be closed at a 50% profit with a GTC Limit Order that can close automatically. A put can then be sold on the same stock, or another based on your opening criteria. Closing early will reduce early assignment and gamma risk to take the lower risk "easy" profit off the top
* Enter the Credits received, and any Debits paid to close or roll, on the Tracking P&L file
* Setting an alert in the broker app if the stock drops to the put strike price will signal it is time to review and consider rolling. Note that rolling seldom has to be done quickly, so this can be reviewed and managed later if needed, and many times the stock will dip and then move back up to negate needing to roll
* If challenged Roll out in time, and down in strike, for a net credit when possible. Roll for as long as a net credit is possible. See this post for details on rolling puts to help avoid assignment: https://www.reddit.com/r/Optionswheel/comments/lliy8x/rolling_short_puts_to_avoid_assignment/
* If a credit cannot be made, then it is best to let the put expire to take assignment of the stock
Puts can be sold, and rolled, over and over to collect as much premium and profits as possible with the shares rarely assigned. Those having frequent assignments should review the stock selection and trading processes as it should be uncommon to be assigned.

# Step #3: Sell Covered Calls

Using the tracking file to determine the net stock cost which may already be below where the stock is. As selling puts is usually the most profitable, some traders just sell the stock and move on to selling more CSPs or sell a very high-value ITM Call that is sure to be called away and adds to the profit.

If the net stock cost is above the current market price and you keep the stock, then the goal is to sell CC premium to continue adding to the Credits and lowering the net stock cost below where the stock is trading before it gets called away.

Selling CCs suggested process:

* Sell a Call 7 to 10 DTE at or above the net stock cost whenever possible. Note that I will settle for a lower premium to be at or above the net cost rather than sell below and risk being assigned for a loss. Allow the CC to expire, then sell another if the shares are not called away.
* If CCs cannot be sold at or above the net stock cost, then waiting until the share price rises may be needed. This is why it is noted to only trade on stocks you are good holding if needed.
* Track net Credits, plus any Dividends captured, on the tracking file to know the net stock cost.
* Continue selling CCs until the net stock cost is below the strike price at which time the stock can be left to be called away (some note that it cost less in fees to close the option and just sell the stock which accomplishes the same thing).
* Advanced Strategy - Some may consider selling a Covered Strangle, which is a CC with an added CSP that "doubles up" on the premiums to help the position recover faster.

* Note the risk of additional shares may be assigned, so it is critical to ensure the stock is still a good one to hold, the account has adequate capital to purchase additional shares, and that this does not make the stock position too much of a risk to the overall account.
* In addition to the double premiums, if more shares are assigned the net stock will average down quickly that can help repair the position more quickly.


# Step #4: Review and go back to Step #1 

This is why it is called the wheel as you start over again. The tracking file makes it easy to see the P&L, review the trade to verify the numbers and then look for the next, or same, stock to sell CSPs in Step #1.

As they say, rinse and repeat.
