# Task 5 — Sales Prediction Using Python

**Track:** Data Science
**Internship:** Oasis Infobyte Summer Internship Program (OIBSIP)
**Author:** Vivek Raj Jha

## Objective
Build a regression model that predicts product sales based on advertising spend across different media channels (TV, Radio, Newspaper).

## Tech Stack
- Python
- pandas
- scikit-learn
- matplotlib / seaborn
- Jupyter Notebook

## Dataset
The classic **Advertising.csv** dataset (200 records) — advertising budgets (in thousands of dollars) across TV, Radio, and Newspaper, along with resulting product sales (in thousands of units). Included in this folder as `Advertising.csv`.

## What This Notebook Covers
- Data loading and EDA: null check, descriptive statistics, pairplot of all features
- Individual scatter plots: Sales vs. TV, Radio, and Newspaper spend
- Correlation matrix heatmap
- Train/test split (80/20)
- Baseline Linear Regression model
- Additional Random Forest Regressor model for comparison
- Evaluation using MAE, RMSE, and R² score
- Residual plot for the best-performing model
- Interpretation: which advertising channel has the highest impact on sales (via coefficients and feature importance)

## How to Run
1. Install dependencies:
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```
2. Open the notebook:
   ```
   jupyter notebook Sales_Prediction.ipynb
   ```
3. Run all cells from top to bottom.

## Files in This Folder
- `Sales_Prediction.ipynb` — full notebook with code, outputs, and explanations
- `Advertising.csv` — the dataset used
- `pairplot.png` — pairplot of advertising spend vs sales
- `scatter_plots.png` — individual scatter plots per channel
- `correlation_heatmap.png` — correlation matrix heatmap
- `actual_vs_predicted.png` — actual vs predicted sales for both models
- `residual_plot.png` — residual plot for the best-performing model
- `README.md` — this file

## Results Summary
Both Linear Regression and Random Forest models achieve strong R² scores, confirming advertising spend is a good predictor of sales. **TV spend has the strongest impact on sales**, followed by **Radio**, while **Newspaper spend shows minimal impact** — see the notebook for exact metrics and coefficient/feature-importance analysis.
