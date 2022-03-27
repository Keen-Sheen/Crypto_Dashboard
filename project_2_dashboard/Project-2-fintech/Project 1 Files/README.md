# A Wild Ride into Cryptocurrencies

Cryptocurrencies have made impulsive moves in the last three years.

Over three years, there have been pre-pandemic & post-pandemic effects on markets & significant value changes for digital assets. The evolution of blockchain and cryptocurrencies will change our future in the way we work, live, find value, and how technology creates a faster experience in doing business.

## Cryptocurrency Dashboard

Take a journey into how we explored the top 50 cryptocurrencies based on market capitiliazation while observing the annual performance of a $1000 investment in a custom portfolio of the top 6 altcoins.

In our process, we utilized various Python packages & APIs to extract cryptocurrency data and analyze daily and annual performance of the altcoin portfolio both historically and prospectively (via Monte Carlo simulations).  We then created visualizations and a Panel dashboard to tell the story.

Work was done in a Jupyter Lab notebook using Python. We imported several packages to satisfy our calculations. We then used the free crypto API to select the top 50 cryptocurrencies based on market capitalizations. After exploring this data, we went even further to pull the OHLVC 'Open', 'High', 'Low', 'Close', 'Volume' for each crypto using CCXT. Part of this process involved using try & except logic to determine base currency denominations for each cryptocurrency, then using the TQDM function to show a progress bar while the crypto data was extracted using the CCXT API.  We then appended the crypto price data to a list and then converted it into a Pandas dataframe for use in our analysis.

Beyond extracting the data, we created a portfolio of 6 Altcoins with an initial investment of $1000. We established variables for the initial total investment, portfolio weights, & number of days invested. We then created a function to determine the units purchased of each crypto as of the investment date. Finally, we created a custom Pandas dataframes of portfolio data to use for interactive charts, plots & Monte Carlo simulations.

Portfolio dashboard includes:

- Annual 2021 price chart for each crypto with widget
- One-year daily % returns of all crypto with widget
- One-year portfolio USD value of each portfolio holding
- One-year total portfolio value in USD
- Monte Carlo simulation outcomes (100 simulations over 365 days)
- Monte Carlo simulation histogram
- Mnte Carlo simulation custom outcomes (10 simulations at once)


