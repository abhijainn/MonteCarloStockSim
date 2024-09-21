# Monte Carlo Stock Simumation

This project implements a Monte Carlo Stock Simulation to predict future stock prices based on historical data. The simulation uses random sampling from a normal distribution to model the variability in stock returns. Additionally, the Cholesky decomposition is applied to the covariance matrix to introduce correlations between stock returns.


<h2>How it Works</h2>

1. Edit "stockList" to incorporate relevant stocks. All stock data is from Yahoo finance
2. Set the number of simulations ("mc_sims"), the simulation timeframe ("timeframe"), and the initial portfolio value ("startingPortfolio").
3. Run Monte Carlo Simulations
   1. Generate random samples, which represent changes in stock price
   2. Apply Cholesky Decomposition to incorporate covariances in the random samples
4. Calculate Daily Returns
5. Calculate cumulative returns and store in "simulations" matrix
