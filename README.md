# VaR-Analysis-Brent-Oil-Python & Excel

Value at Risk (VaR) is a statistical measure that estimates the maximum potential loss that an investment portfolio or a specific asset can experience within a given time period, with a given probability or confidence level.

The code calculates the VaR using a historical simulation approach. The VaR is computed as the nth percentile of the returns distribution, where n is determined by the chosen confidence level. In this case, the confidence level is set to 0.95 or 95%.

To calculate VaR, the code first calculates daily returns by taking the percentage change of the closing prices. It then computes the mean and standard deviation of the returns. The VaR is then computed using the numpy.percentile function, which calculates the nth percentile of a distribution.

Finally, the code prints the VaR and plots it along with the daily returns. The plot helps visualize the distribution of returns and how the VaR relates to it over time. If the returns fall below the VaR line, it suggests that the investment is underperforming and may pose a risk.

The Excel file also represents the VaR analysis for Brent oil using historical simulation and MonteCarlo simulation models. 

Both models take into account daily P&Ls and calculates given confidential levels.
