Monte Carlo Simulation for NVIDIA Stock Price Prediction

This project applies Monte Carlo simulation to model and predict the future price trajectories of NVIDIA (NVDA) stock. The approach leverages stochastic modeling to capture market uncertainty and generate a distribution of possible future price paths rather than a single point estimate.

The core implementation is provided in the Jupyter Notebook train.ipynb, where historical NVDA price data is used to estimate statistical parameters (e.g., returns and volatility). These parameters are then used to simulate thousands of potential future price scenarios.

Technical Overview

Historical NVDA price data is processed to compute log returns

Empirical mean and volatility are estimated from historical data

Future price paths are simulated using random sampling

Monte Carlo trajectories are aggregated to analyze:

Expected future price behavior

Variance and uncertainty

Distribution of possible outcomes

Skills Demonstrated

Time-series analysis of financial data

Stochastic modeling and Monte Carlo methods

Probabilistic forecasting under uncertainty

Vectorized numerical computation with NumPy

Financial data handling with Pandas

Visualization of simulated price paths and distributions

Reproducible experimentation in Jupyter Notebook

Why This Project Is Relevant

Monte Carlo simulations are widely used in quantitative finance, risk management, and machine learning–driven forecasting. This project demonstrates the ability to:

Translate financial theory into executable models

Handle noisy, real-world time-series data

Quantify uncertainty instead of relying on deterministic predictions

Communicate results through clear visualizations

These skills are directly applicable to ML engineer, data scientist, and quantitative analyst roles.

How to Run
git clone https://github.com/CS-AI-LA/MonteCarloSimulation.git
cd MonteCarloSimulation/notebooks
jupyter notebook train.ipynb
