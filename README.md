# betacomps

Takes a list of stock tickers listed on the tsx, nasdaq, and nyse to create a summary table of levered and unlevered betas.

The output table includes:
- company name
- levered beta (5y beta)
- equity market value (current market cap)
- debt (latest quarter)
- debt-to-equity ratio
- debt-to-capital ratio
- tax rate (4-yr average)
- unlevered beta

Demo of 11 non-grocery retailers listed on TSX. Computed in ~20 sec (click on GIF to enlarge view in new tab).

![runtointeractive_betacomps](https://github.com/jtwag-041/betacomps/assets/48776287/940fac68-666e-4a39-bd44-9ee4915a0845)


Note: If levered beta is not found, levered beta and unlevered beta = 0. If debt = 0, both debt ratios will = 0.

