# Pairs-Trading-strategy

The main aim of this project is to create a pairs trading strategy using the cointegration approach. Following is the basic theory and steps to be followed to implement this starategy 

**Basic Steps -:**

-  Creating a universe of stocks on which all of the analysis will be done
-  Selecting all the pairs of stocks from this universe of stocks and performing a cointegration test on these stocks
-  Using linear regression, we find out the factor beta for each pair of selected stocks, and thus we obtain a stationary time series
-  Normalize this stationary time series by replacing X by (X-mu)/sigma.
-  Formulating a buy/sell rule based on the stationary time series.

**Extensions of this project -:**

-  Rather than considering only pairs of stocks from a universe of stocks, we can consider portfolios of stocks
-  Creating a portfolio of these pairs(of portfolios/single assets) and assigning different weights to each pair
-  Rather than using a simple buy/sell rule, we can use a more mathematically involved buy/sell rule to maximize our profits
-  Using the Copula Approach rather than the cointegration approach can also be tried
-  Replacing the worst performing pairs in a cyclic manner can also be done.
