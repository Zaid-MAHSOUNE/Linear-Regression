# Linear Regression Analysis

This Python script conducts Linear Regression analysis using different methods (Covariance, Least Squares, Gradient Descent) to model the relationship between temperature and sales, as well as generate and analyze synthetic data.

## Overview

The script includes the following functionalities:

1. **Data Preparation**: Initializes and uses temperature and sales data, as well as generates synthetic data for analysis.

2. **Linear Regression Methods**:
    - **Covariance Method**: Calculates coefficients using the covariance method for linear regression.
    - **Least Squares Method**: Applies linear regression using the least squares method.
    - **Gradient Descent Method**: Utilizes gradient descent to compute coefficients.

3. **Visualization**: Displays plots showcasing the relationship between X (temperatures or generated data) and Y (sales or synthetic data) with the linear regression line.

4. **Prediction**: Predicts sales based on temperature values using the least squares method.

5. **Evaluation Metrics**:
    - **R-squared (Coefficient of Determination)**: Measures the goodness of fit of the regression model.
    - **Root Mean Square Error (RMSE)**: Quantifies the differences between predicted values and actual values.

## Usage

1. Ensure you have Python installed on your system.
2. Copy and paste the provided code into a Python environment or an IDE like Jupyter Notebook or Spyder.
3. Run the script to perform the Linear Regression analysis.
4. Interpret the plotted results and view the calculated metrics for each method.

## Dependencies

- NumPy: A library for numerical computations in Python.
- Matplotlib: A plotting library for creating visualizations.

Ensure you have these dependencies installed in your Python environment to run the script successfully.

Install dependencies using pip:

```bash
pip install numpy matplotlib
