# Experimental Capacitance Estimation via Data Analysis

## Overview
This project analyzes experimental charge–voltage data obtained from a parallel-plate capacitor
to estimate its capacitance at two different plate separations (4 mm and 6 mm).
The analysis combines fundamental experimental physics with data analysis techniques using Python.

## Physical Background
For a capacitor, the electric charge and the applied voltage are related by:
$ Q = C V $
This linear relationship allows the capacitance to be determined as the slope of a linear fit
of charge versus voltage.

## Dataset
The dataset consists of experimental measurements of electric charge for four different voltage values.
For each voltage and plate separation, the charge was measured three times to reduce random errors.
The data were collected during a university-level experimental physics course.

## Data Analysis Methodology
The following steps were performed:
- Loading and cleaning the data from an Excel file
- Averaging repeated charge measurements
- Performing linear regression using the least squares method
- Residual analysis to evaluate fit quality
- Estimating the uncertainty in the capacitance

## Results
Capacitance values were obtained for both plate separations.
The results show the expected decrease in capacitance when the distance between the plates increases,
consistent with electrostatic theory.

## Tools
- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab

## How to Run
1. Upload the Excel dataset to Google Colab
2. Open the notebook and run all cells
3. All plots and numerical results will be generated automatically

## Author
Undergraduate student in Engineering Physics  
Experimental data analysis project
