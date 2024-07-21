# Pairs-Trading-strategy

The main aim of this project is to create a pairs trading strategy using the cointegration approach. Following is the basic theory and steps to be followed to implement this starategy 

**Basic Steps -:**

- **1)** Creating a universe of stocks on which all of the analysis will be done
- **2)** Selecting all the pairs of stocks from this universe of stocks and performing a cointegration test on these stocks
- **3)** Using linear regression, we find out the factor beta for each pair of selected stocks, and thus we obtain a stationary time series
- **4)** Normalize this stationary time series by replacing X by (X-mu)/sigma.
- **5)** Formulating a buy/sell rule based on the stationary time series.

**Extensions of this project -:**

- **1)** Rather than considering only pairs of stocks from a universe of stocks, we can consider portfolios of stocks
- **2)** Creating a portfolio of these pairs(of portfolios/single assets) and assigning different weights to each pair
- **3)** Rather than using a simple buy/sell rule, we can use a more mathematically involved buy/sell rule to maximize our profits
- **4)** Using the Copula Approach rather than the cointegration approach can also be tried
- **5)** Replacing the worst performing pairs in a cyclic manner can also be done.
