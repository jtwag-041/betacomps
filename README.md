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

Demo (click on GIF to enlarge view in new tab)

![runtointeractive_betacomps](https://github.com/jtwag-041/betacomps/assets/48776287/709280db-1cea-4df6-99ef-84e4787c640b)

Note: if levered beta is not found, levered beta and unlevered beta = 0. If debt = 0, both debt ratios will = 0.

