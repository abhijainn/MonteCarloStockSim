# Monte Carlo Stock Simumation

This project implements a Monte Carlo Stock Simulation to predict future stock prices based on historical data. The simulation uses random sampling from a normal distribution to model the variability in stock returns. Additionally, the Cholesky decomposition is applied to the covariance matrix to introduce correlations between stock returns.



<h2>Features</h2>

Random Sampling: Utilizes random variable from a multivariate normal distribution to simulate daily stock returns, ensuring a realistic modeling of stochastic processes.

Cholesky Decomposition: Implements Cholesky decomposition of the covariance matrix to incorporate inter-stock return correlations, preserving the historical variance-covariance structure.

Cumulative Return Computation: Employs cumulative product calculations to transform daily returns into cumulative returns over the simulation period, providing insights into portfolio growth trajectories.

Portfolio Simulation: Conducts multiple iterations of portfolio value simulations, capturing a broad spectrum of potential future outcomes based on current asset allocations and historical performance metrics.

<h2>How it Works</h2>

1. Edit "stockList" to incorporate relevant stocks. All stock data is from Yahoo finance
2. Set the number of simulations ("mc_sims"), the simulation timeframe ("timeframe"), and the initial portfolio value ("startingPortfolio").
3. Run Monte Carlo Simulations
   1. Generate random samples, which represent changes in stock price
   2. Apply Cholesky Decomposition to incorporate covariances in the random samples
4. Calculate Daily Returns
5. Calculate cumulative returns and store in "simulations" matrix
