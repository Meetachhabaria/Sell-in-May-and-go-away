**Introduction**

In the world of stock trading, a well-known adage exists: Sell in May and go away. The strategy suggests that investors should divest their equity holdings in May and re-enter the market at the end of October.

 This advice exists because more people are likely to take vacations during summer months. Ultimately, the result is low participation in the market, which makes it riskier to invest in.

Some investors and researchers have proven that this theory works while others feel it is better to stay in the market all year round.


With this project, we try to inspect the soundness of this advice.


> “*We look at the present through a rear-view mirror. We march backwards into the future*.” -Marshall Mcluhan


 The best way to check the validity of this strategy is to ask investors and have them confirm or deny it. But, it is not sensible.
Fortunately, this task is easier to execute with python coding and historical data.



By the end of the code, we will be able to conclude the effectiveness of this advice, and whether it works for all kinds of investors or not.





> **Methodology**: We will use python3 to process the data obtained from Fama-French.

**Our fundamental goals are threefold**: 

> First, we check whether seasonality has any effect on returns and volatility of the market.

> Second, we will analyze this strategy on a rolling basis to test whether certain parameters (return, risk, and risk-to-return ratio (sharpe ratio)) of this strategy defeat the market or not. 

> Finally, we will consider whether this strategy is still effective under the influence of specific circumstances (taxes, other special events).


