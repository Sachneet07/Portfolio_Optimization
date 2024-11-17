# Portfolio Optimization and Risk Analysis
## Objective
To construct an optimized portfolio of stocks using mean-variance optimization to maximize the Sharpe Ratio.
## Methodology
1. Fetched historical stock prices for AAPL, BAC, RIVN, DFS, TSLA, and AMD using Yahoo Finance.
2. Calculated daily returns, mean returns, and covariance matrix.
3. Used SciPy to optimize portfolio weights by maximizing the Sharpe Ratio.
4. Visualized the Efficient Frontier and highlighted the optimized portfolio.
## Results
- **Optimized Portfolio Weights:**
  - AAPL: 50.21%
  - DFS: 49.79%
  - Other stocks: 0%
- **Portfolio Performance:**
  - Expected Daily Return: 0.0217%
  - Risk (Standard Deviation): 0.2753%
  - Sharpe Ratio: -0.0134
## Visualization
Below is the Efficient Frontier with the optimized portfolio highlighted.
![Efficient Frontier](outputs/efficient_frontier_with_optimized_portfolio.png)
## How to Use This Repository
1. Clone the repository:
2. Install the required libraries:
3. Open `Portfolio_Optimization.ipynb` in Jupyter Notebook.
4. Run the cells to see the analysis and visualization.
## License
This project is licensed under the MIT License.
