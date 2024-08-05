# MonteCarloStockSim
This project implements a Monte Carlo Stock Simulation to predict future stock prices based on historical data. The simulation uses random sampling from a normal distribution to model the variability in stock returns. Additionally, the Cholesky decomposition is applied to the covariance matrix to introduce correlations between stock returns.



<h1>Features</h1>

Random Sampling: Utilizes random variates from a multivariate normal distribution to simulate daily stock returns, ensuring a realistic modeling of stochastic processes.

Cholesky Decomposition: Implements Cholesky decomposition of the covariance matrix to incorporate inter-stock return correlations, preserving the historical variance-covariance structure.

Cumulative Return Computation: Employs cumulative product calculations to transform daily returns into cumulative returns over the simulation period, providing insights into portfolio growth trajectories.

Portfolio Simulation: Conducts multiple iterations of portfolio value simulations, capturing a broad spectrum of potential future outcomes based on current asset allocations and historical performance metrics.
