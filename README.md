Overview
This project analyzes U.S. natural gas consumption data (2014–2024) to identify trends, seasonal patterns, and state-level insights. The dataset includes monthly consumption metrics across states and sectors (residential, commercial, industrial). Key tasks include data cleaning, feature engineering, and exploratory analysis to derive actionable insights.

Key Features
Data Cleaning: Handled missing values (476 null records) and duplicates.

Feature Engineering: Created date and year_quarter columns for time-series analysis.

State-Level Insights: Normalized state names and calculated descriptive statistics.

Seasonal Patterns: Analyzed monthly consumption trends using month_name.

Visualization: Generated heatmaps and summary statistics to highlight consumption patterns.

Key Findings
Top Consumers: Texas, California, and Florida showed the highest average consumption.

Seasonality: Consumption peaked in winter months (January, December) due to heating demand.

Data Gaps: Missing values were concentrated in 2023 and specific states (DC, Hawaii).

Technologies Used
Python Libraries: Pandas, NumPy, Matplotlib, Seaborn

Data Processing: Datetime conversion, missing value imputation, aggregation

Visualization: Summary statistics, seasonal trend plots

Installation
bash
git clone https://github.com/yourusername/gas-consumption-analysis.git
cd gas-consumption-analysis
pip install -r requirements.txt  # pandas, numpy, matplotlib, seaborn
Usage
Run gas_exp.ipynb to reproduce the analysis.

Explore the data.csv file for raw data inputs.

Refer to state_consumption_stats.csv for processed insights.

License
MIT License. See LICENSE for details.

