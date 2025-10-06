# A Study on Risk Neutral Density Estimation using Support Vector Regression

## Project Overview

This project focuses on estimating Risk Neutral Density (RND) using Support Vector Regression (SVR). Risk Neutral Density is a key concept in financial modeling used to assess the probability distribution of future asset prices implied by option prices. By applying SVR, this project aims to predict option prices and derive the RND, demonstrating how machine learning techniques can be leveraged in quantitative finance.

### Key Highlights:

- Implemented SVR from scratch in Python.
- Applied financial data analysis on real datasets.
- Explored the relationship between option prices and RND.

## Repository Structure

Organize your repository to make it clean and professional:

```plaintext
risk-neutral-density-svr/
│
├── data/                   # Original and processed datasets
│   ├── csv files/                # Raw dataset files
│                           # Cleaned and prepared datasets for modeling
│
├── Project-Code/              # Optional Jupyter notebooks for EDA or experimentation
│                                # Python scripts
│                               # SVR implementation and RND estimation
│
├── Project Report/                # Plots, charts, and outputs
│
├── README.md               # Project overview and instructions
└── requirements.txt        # Python dependencies
```
## Purpose and Skills Showcased

This project demonstrates:
Machine Learning: SVR modeling from scratch
Python Programming: Data processing, modeling, and visualization
Financial Analytics: Risk Neutral Density estimation
Data Analysis: Cleaning, feature selection, and visualization of results

## Project Steps / Workflow

Data Collection: Use historical option prices and underlying asset data.
Data Cleaning & Validation: Handle missing values, outliers, and normalize the data.
Feature Engineering: Select relevant features for SVR modeling.

## SVR Modeling:

Implement SVR using Python (no external libraries for core SVR).
Train and test the model on historical option data.
Risk Neutral Density Estimation:
Derive the RND from the predicted option prices.
Visualize the density curves.
Evaluation: Compare estimated RND with theoretical or market-implied densities.

## Visualization & Insights:

Plot predicted vs actual option prices.
Visualize the RND curves for different strikes/maturities.
Key Visualizations
Predicted vs Actual Option Prices (Line Plot / Scatter Plot)
Risk Neutral Density Curves (PDFs for different maturities/strikes)
Error Metrics (RMSE / MAE) comparison
Optional: Heatmaps to explore feature importance or model performance

## Conclusion

This project demonstrates the application of Support Vector Regression for estimating Risk Neutral Density in financial markets.

## Key takeaways:

SVR can effectively capture the nonlinear relationships in option pricing.
The derived RND provides insights into market expectations of future asset price distributions.
The methodology can be extended to other derivatives or financial instruments for predictive modeling.
Potential Extensions:
Experiment with other kernel functions in SVR.
Compare SVR results with other ML techniques like Random Forest or Neural Networks.
Use RND estimates for derivative pricing or risk management.

