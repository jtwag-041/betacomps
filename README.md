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

Demo of non-grocery retailers listed on TSX (click on GIF to enlarge view in new tab)



Note: if levered beta is not found, levered beta and unlevered beta = 0. If debt = 0, both debt ratios will = 0.

