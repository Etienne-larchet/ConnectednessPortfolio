# Connectedness Portfolio

This project analyzes the connectedness of commodity markets and performs portfolio optimization using both covariance and DYIC (Dynamic Connectedness Index) matrices.

# Usefull links
- https://gabauerdavid.github.io/ConnectednessApproach/
- https://www.financialconnectedness.org/

## Features

- Fetches and cleans historical commodity data from Yahoo Finance using `yfinance`
- Computes rolling-window connectedness measures (DYIC) using VAR models
- Visualizes connectedness and portfolio performance
- Portfolio optimization using [PyPortfolioOpt] with both covariance and DYIC matrices
- Compares optimized portfolios with an equally weighted benchmark

## Project Structure

- `code.ipynb`: Main Jupyter notebook containing all code, analysis, and visualizations
- `pyproject.toml`: Project dependencies and configuration (uses Poetry)
- `poetry.lock`: Locked dependency versions

## Requirements

- Python >= 3.13
- See dependencies in [pyproject.toml](pyproject.toml)

## Getting Started

1. **Install dependencies**  
   Using [Poetry](https://python-poetry.org/):
   ```sh
   poetry install
   ```
   Using pip:
   ```sh
   pip install -r requirements.txt
   ```

2. **Run the notebook**  
   Open `code.ipynb` in VS Code or JupyterLab and run all cells.

## Main Packages Used

- `numpy`, `pandas`: Data manipulation
- `yfinance`: Downloading financial data
- `matplotlib`, `seaborn`: Visualization
- `statsmodels`: VAR modeling and connectedness analysis
- `pyportfolioopt`: Portfolio optimization

## Author

Etienne Larchet  
MIT License

---