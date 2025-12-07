# Monte Carlo Option Pricing

This repository contains a Python project for pricing European call and put options using Monte Carlo simulations. The project also includes analytical Black-Scholes comparison, option Greeks calculation, and validation of put-call parity.

## Project Overview

The project demonstrates:

- Monte Carlo simulation of stock price paths using Geometric Brownian Motion (GBM)
- European option pricing (call and put)
- Variance reduction using control variates
- Comparison with analytical Black-Scholes prices
- Calculation of key option Greeks: Delta, Vega, Gamma
- Verification of put-call parity
- Visualization of simulated price distributions and sample GBM paths

## Files

- `MonteCarloOptionPricing.ipynb` — Jupyter notebook with full implementation, explanations, and plots.
- `MonteCarlo_OptionPricing_Report.md` – A shorter research paper version related to the project.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/deepanshmakkar/Monte-Carlo-Option-Pricing.git
cd Monte-Carlo-Option-Pricing
```

2. Install required packages:

```bash
pip install numpy pandas matplotlib yfinance scipy
```

## Usage

Open the notebook MonteCarloOptionPricing.ipynb in Jupyter Notebook or Jupyter Lab.

Run all cells sequentially to reproduce the simulation, option pricing, Greeks, and plots.

## Notes

This project is intended for educational and portfolio purposes.

Stock data is retrieved via yfinance and may change over time.

The notebook uses standard assumptions for European options and GBM modeling.

## License

This project is open-source and available under the MIT License.
