# SOR Patient Analysis Project
**SOR Patient Analysis Project** is a project focused on analyzing patient admission data for the Emergency Department (SOR). The main goal is to predict and visualize the number of patients.

## Features
- **Load and merge** prediction results from XGBoost and ARIMA models.
- **Analyze patient data** by visualizing total and average patient counts across various periods (monthly, daily, weekly, yearly).

### Main Functions:
- `plotMonthCounts()`: Visualizes the number of patients per month for selected years.
- `plotMonthSumCounts()`: Plots the total number of patients for each month.
- `plotMonthSumCountsPeriod()`: Plots the total number of patients over a specified period (Nd, 1w, 1m, 1y).
- `plotMonthAverageCountsPeriod()` Plots the average number of patients over a specified period (Nd, 1w, 1m, 1y).

### Files:
- `Praktyki_SOR.ipynb`: Main Jupyter Notebook containing the analysis, predictions, and visualizations.
