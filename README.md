# U.S. Natural Gas Consumption Analysis (2014–2024)

![ChatGPT Image Apr 27, 2025, 06_16_13 AM](https://github.com/user-attachments/assets/bc7f7153-cb2d-41dd-afa6-e648781cc0d6)

## Overview
This project analyzes U.S. natural gas consumption data (2014–2024) to identify trends, seasonal patterns, and state-level insights. The dataset includes monthly consumption metrics across states and sectors (residential, commercial, industrial). Key tasks include data cleaning, feature engineering, and exploratory analysis and time series forecasting to derive actionable insights.


![image](https://github.com/user-attachments/assets/5f7d9bbe-5175-4c7f-a514-56aea4cae336)

![image](https://github.com/user-attachments/assets/513fa84d-0f71-4f61-932b-0947d751f10a)


## Key Features
- **Data Cleaning**: Handled missing values (476 null records) and duplicates.
- **Feature Engineering**: Created `date` and `year_quarter` columns for time-series analysis.
- **State-Level Insights**: Normalized state names and calculated descriptive statistics.
- **Seasonal Patterns**: Analyzed monthly consumption trends using `month_name`.
- **Visualization**: Generated heatmaps and summary statistics to highlight consumption patterns.

![image](https://github.com/user-attachments/assets/ab0332fb-9dcc-44d4-8c8f-bce141d4a991)


![seasonal_patterns](https://github.com/user-attachments/assets/3e32c4c7-a736-42ad-a532-1011711a22fd)


## Key Findings
- **Top Consumers**: Texas, California, and Florida showed the highest average consumption.
- **Seasonality**: Consumption peaked in winter months (January, December) due to heating demand.
- **Data Gaps**: Missing values were concentrated in 2023 and specific states (DC, Hawaii).

![image](https://github.com/user-attachments/assets/ef825807-2bbb-4172-b42d-c2418f6e8648)

![consumption_heatmap](https://github.com/user-attachments/assets/d4c24a15-0043-4883-82f8-680b7d3a863a)


---

## Technologies Used
- **Python Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Statsmodels
- **Data Processing**: Datetime conversion, missing value imputation, aggregation
- **Visualization**: Summary statistics, seasonal trend plots

---

# Advanced Time-Series Analysis
*Texas only*

## Commercial consumption forecast

![commercial_consumption_forecast](https://github.com/user-attachments/assets/7acaa358-0af4-4df6-b8cc-35bde78f953e)

Evaluation results: MAPE: 5.94%, RMSE: 1277.65
Projected YoY growth: 11.13%

## Residential consumption forecast

![residential_consumption_forecast](https://github.com/user-attachments/assets/1488ea1d-28a3-4d40-94a9-1bc2a9c73ca0)

Evaluation results: MAPE: 12.09%, RMSE: 4442.99
Projected YoY growth: 25.48%

## Industrial consumption forecast

![industrial_consumption_forecast](https://github.com/user-attachments/assets/66001401-e97e-4a2f-a90f-4c237ea016dd)

Evaluation results: MAPE: 4.60%, RMSE: 9414.43
Projected YoY growth: 5.79%

## Electrical consumption forecast

![electric_power_consumption_forecast](https://github.com/user-attachments/assets/8115ff70-d092-4d14-86ed-4b4a43f9a3c9)

Evaluation results: MAPE: 6.96%, RMSE: 14961.86
Projected YoY growth: 13.48%


## Installation
```bash
git clone https://github.com/shAd0re/gas-consumption-analysis.git
cd gas-consumption-analysis
pip install -r requirements.txt  # pandas, numpy, matplotlib, seaborn
