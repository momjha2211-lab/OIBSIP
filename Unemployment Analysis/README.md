# Task 2 — Unemployment Analysis with Python

**Track:** Data Science
**Internship:** Oasis Infobyte Summer Internship Program (OIBSIP)
**Author:** Vivek Raj Jha

## Objective
Perform exploratory data analysis on unemployment data to uncover regional and temporal trends, with a focus on the impact of the COVID-19 pandemic on unemployment rates in India.

## Tech Stack
- Python
- pandas
- matplotlib / seaborn
- Jupyter Notebook

## Dataset
State-wise monthly unemployment data for India, covering **February 2020 – October 2020** (pre-COVID and COVID-19 period). Includes: Region (state), Date, Estimated Unemployment Rate (%), Estimated Employed, and Estimated Labour Participation Rate (%). Included in this folder as `unemployment.csv`.

## What This Notebook Covers
- Data loading, shape inspection, null value check, and type conversion
- EDA: region-wise average unemployment rates, month-wise trends
- Time-series line chart: unemployment rate over time for the top 3 states
- Bar chart: top 10 states with the highest average unemployment rate
- Heatmap: correlation between unemployment rate, employment, and labour participation rate
- Pre-COVID vs. post-COVID comparison (mean rates for each period)
- National monthly trend chart
- Written observations after each visualization
- Conclusion with actionable insights

## How to Run
1. Install dependencies:
   ```
   pip install pandas numpy matplotlib seaborn jupyter
   ```
2. Open the notebook:
   ```
   jupyter notebook Unemployment_Analysis.ipynb
   ```
3. Run all cells from top to bottom.

## Files in This Folder
- `Unemployment_Analysis.ipynb` — full notebook with code, outputs, and explanations
- `unemployment.csv` — the dataset used
- `timeseries_top3_states.png` — unemployment rate trend for the top 3 states
- `top10_states_bar.png` — bar chart of top 10 states by average unemployment rate
- `correlation_heatmap.png` — correlation heatmap of key variables
- `pre_vs_post_covid.png` — pre-COVID vs. COVID period comparison
- `monthly_national_trend.png` — national average monthly unemployment trend
- `README.md` — this file

## Results Summary
National unemployment rose sharply during India's COVID-19 lockdown (April–May 2020) before gradually recovering through October 2020. States like Puducherry, Tripura, and Haryana consistently showed the highest unemployment rates — see the notebook for full regional and time-series analysis.
