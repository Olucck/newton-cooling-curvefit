# newton-cooling-curvefit
This repository contains a Python program developed to perform an analysis of Newton's Cooling Experiment. The program utilizes the SciPy library for curve fitting, along with Matplotlib for data visualization.
Newton's Cooling Experiment Analysis

Overview:
This Python program has been developed to analyze experimental data from Newton's Cooling Experiment, providing insights into temperature changes over time. It utilizes the SciPy library for curve fitting and Matplotlib for data visualization.

Features:
Data Input:

The program initiates by defining time (x) and temperature (y) data from Newton's Cooling Experiment. Users can replace the example data with their own experimental values.
Fitting Function:

A mathematical function for curve fitting is encapsulated in the func function. It represents the cooling behavior over time and includes parameters for initial temperature (T0), ambient temperature (Ta), and a decay constant (k).
Curve Fitting:

Using the curve_fit function from SciPy, the program fits the experimental data to the defined function. The initial guess for parameters (T0, Ta, k) is set as [0, 0, 0].
Data Visualization:

Matplotlib is employed to generate a scatter plot, overlaying the experimental data with the curve fit. The resulting plot visually represents the cooling trend observed in Newton's experiment.
Parameter Extraction:

The program extracts the fitted parameters (T0fit, Tafit, kfit) from the curve fitting results.
Error Calculation:

Utilizing the covariance matrix, the program calculates errors associated with each fitted parameter (error_T0, error_Ta, error_k).
Results Display:

The program prints the fitted parameters and their corresponding errors, offering a quantitative understanding of the cooling behavior observed in Newton's experiment.
Usage:
Users should replace the example data with their own time and temperature values from Newton's Cooling Experiment.
Running the program provides a visual representation of the cooling trend and yields fitted parameters with associated errors.
