# Market-Model
Using Statsmodels to perform frequentist linear regression 

An asset's Market Model (MM) is a standard time series regression of the the realized excess returns of the asset against the realized excess returns of the market. Excess returns are defined as returns in excess of some benchmark such as the risk-free rate. A security's MM is formulated as:

(R - F) = 𝛂 + 𝛃 (M - F) + 𝛔

Y = (R - F) is the outcome variable, X = (M - F) is the predictor variable, R is the realized return of a stock, F is the return on a risk-free asset (US treasury bill) , M is the realized return of a market portfolio (S&P 500), 𝛼 (alpha) is the expected stock-specific return, 𝛽 (beta) is the level of systematic risk exposure to the market, 𝛔 (sigma) is the unexpected stock-specific return

Note that an asset's MM is different from its Captial Asset Pricing Model (CAPM). Unlike the CAPM, an asset's MM has both an idiosyncratic risk term 𝛼 and an error term 𝛔 in its formulation. However, the systematic risk term beta of the asset is the same as the one calculated using the CAPM. The expected value of 𝛔 is zero. That is the reason it does not appear in the CAPM which formulates expected returns.

According to the CAPM which subscribes to the efficient market hypothesis, the intercept, or 𝛼, of an asset's MM has an expected value of zero. The asset's realized postive/(negative) 𝛼 shows that the market participants under priced/(overpiced) the security during the holding period.
