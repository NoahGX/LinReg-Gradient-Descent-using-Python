# Linear Regression

## Overview
This collection of Jupyter Notebooks demonstrates the implementation and optimization of Linear Regression models using Python. `Lin_Reg-1` focuses on using both the Normal Equation and Gradient Descent methods to train models on real data. `Lin_Reg-2` explores linear regression through practical coding examples and gradient descent, using synthetic datasets to understand model performance and optimization.

## Features
- **Normal Equation Method**: Direct computation of weights that minimize the loss without iteration.
- **Gradient Descent Method**: Iterative adjustment of weights to minimize the loss, suitable for both real and synthetic datasets.
- **Interactive Parameters**: Adjust learning rates and observe the effects on model convergence.
- **Visualization of Performance**: Plots illustrating the model's predictions, fit, and loss reduction graphs.

## Usage
Run each cell sequentially and modify parameters in the Gradient Descent sections as desired to explore different outcomes.

## Prerequisites
- Python 3.x
- Jupyter Notebook or Jupyter Lab
- Libraries: `numpy`, `matplotlib`, `pandas`

## Input
- `Lin_Reg-1` uses a dataset named `sat_gpa.csv`, with 105 rows and 3 columns: Math SAT score, Verb SAT score, and University GPA.
- `Lin_Reg-2` operates on a synthetic dataset generated within the notebook. Parameters of the dataset generation function can be modified for experimentation.

## Output
- Final weights for Linear Regression models.
- Predicted values and visualizations of model fits.
- Loss metrics (e.g., MSE) to evaluate model performance across both notebooks.

## Notes
- For `Lin_Reg-1`, ensure the dataset `sat_gpa.csv` is in the proper directory or adjust the path accordingly.
- Different learning rates can significantly affect the performance and speed of the Gradient Descent method in `Lin_Reg-1`, so experimentation is encouraged.
- `Lin_Reg-2` is basic in order to illustrate concepts using synthesized data for clear understanding and requires modifications for production use.