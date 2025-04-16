# Volatility Model Calibration

This repository contains code and analysis for calibrating volatility models, particularly focusing on implied volatility calculation, SVI (Stochastic Volatility Inspired) model implementation, and stress testing.

## Project Overview

This project demonstrates the implementation of various volatility models and calibration techniques including:
- Black-Scholes model for option pricing
- Implied volatility calculation using Newton-Raphson method
- SVI model implementation and optimization
- Generalized SVI model calibration
- Stress testing of volatility models

## Files Description

- `notebook_Volatility_Model_Calibration.ipynb`: Jupyter notebook containing all code implementations and analysis
- `Final_Report_Volatility_Model_Calibration.pdf`: Comprehensive report detailing the results of the analysis
- `Rules_Volatility_Model_Calibration.pdf`: Instructions and requirements for the project

## Requirements

The project requires the following Python libraries:
- numpy
- pandas
- scipy
- matplotlib

## Methodology

The project follows these key steps:
1. Calculate implied volatility from market option prices
2. Interpolate and smooth volatility curves
3. Implement SVI and generalized SVI models
4. Calibrate model parameters using optimization techniques
5. Perform stress tests to evaluate model stability
6. Compare results between different model implementations

## Running the Code

To run the analysis:
1. Open the Jupyter notebook `notebook_Volatility_Model_Calibration.ipynb`
2. Ensure all required libraries are installed
3. Execute the cells sequentially

## Key Features

- Implied volatility calculation and visualization
- Volatility skew analysis
- Parameter optimization using Nelder-Mead algorithm
- SVI model implementation
- Stress testing with arbitrage condition verification

## Results

For detailed results and analysis, please refer to the `Final_Report_Volatility_Model_Calibration.pdf` document included in this repository.

## Instructions

For a complete understanding of the project requirements and evaluation criteria, see the `Rules_Volatility_Model_Calibration.pdf` file.
