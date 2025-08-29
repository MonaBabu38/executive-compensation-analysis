# Executive Compensation and Firm Performance Analysis

This repository contains the analysis, code, and outputs for the project **“Executive Compensation and Firm Performance”**, completed as part of the COMP-1915 Big Data Analysis & Visualisation module.  
The study investigates how CEO pay (salary, bonus, equity incentives) relates to firm performance (ROE, EPS, stock returns, revenue growth) using panel regression techniques.

---

## Repository Structure

README.md → Project overview and instructions  
analysis.ipynb → Jupyter Notebook with all regression models & plots  
data_dictionary.md → Documentation of all variables used  

~ figures/ → Plots and visualisations  
- figure_5_1.png → Trends in CEO pay components  
- figure_5_2.png → Equity incentives vs ROE  
- figure_5_3.png → Non-linear pay-performance effect  

~ outputs/ → Regression outputs  
- regression_summary.txt → Summary of regression results  
- vif_results.csv → Variance Inflation Factor scores  

~ scripts/ → Optional Python scripts  
- regression_models.py → Script to run regression models outside Jupyter  

---

## Dependencies

The analysis uses the following Python libraries:  
- `pandas` (data handling)  
- `numpy` (numerical computing)  
- `matplotlib` (visualisation)  
- `statsmodels` (regression analysis)  
- `linearmodels` (panel data econometrics)  

Install all dependencies with:  
```bash
pip install pandas numpy matplotlib statsmodels linearmodels
