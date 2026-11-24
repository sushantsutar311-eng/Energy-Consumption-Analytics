# Energy Consumption Analytics

## Project Overview
Energy Consumption Analytics is a data analytics project that explores household electricity consumption patterns using historical power consumption data. The project uses Python, SQL, and Power BI to transform raw electricity data into meaningful insights and interactive visualizations.

## Problem Statement
Understanding household electricity consumption over time helps identify usage patterns, peak consumption periods, and opportunities for better energy management. This project analyzes historical electricity usage to support data-driven decisions.

## Objectives
- Analyze household electricity consumption patterns.
- Calculate daily and monthly energy consumption in kWh.
- Identify peak and minimum consumption periods.
- Store processed results in a SQLite database.
- Build an interactive Power BI dashboard.

## Dataset
- Source: UCI Household Electric Power Consumption Dataset
- Records: Approximately 2.07 million
- Time period: December 2006 – November 2010
- Frequency: One-minute measurements
- Features: 9 original columns

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- SQL / SQLite
- Microsoft Power BI
- Git and GitHub

## Key Findings
- Average daily energy consumption: 26.15 kWh
- Maximum daily energy consumption: 79.56 kWh
- Minimum daily energy consumption: 4.17 kWh
- Average monthly energy consumption: 785.63 kWh
- Highest monthly consumption: 1,210.09 kWh (December 2007)
- Lowest monthly consumption: 205.74 kWh (August 2008)

## Project Structure
```text
Energy-Consumption-Analytics/
│
├── data/
├── notebooks/
│   └── energy_analysis.ipynb
├── outputs/
│   ├── daily_consumption.csv
│   ├── monthly_consumption.csv
│   ├── project_summary.csv
│   └── top_10_consumption_days.csv
├── screenshot/
├── energy_analytics.db
├── .gitignore
└── README.md
```

## Dashboard
The Power BI dashboard presents household energy consumption trends and key performance indicators.

Dashboard screenshots are available in the `screenshot` folder.

## How to Run
1. Clone this repository.
2. Install Python and the required libraries.
3. Open `notebooks/energy_analysis.ipynb`.
4. Run the notebook cells to explore the analysis.
5. Open the Power BI report to explore the dashboard.

## Conclusion
This project demonstrates how Python, SQL, and Power BI can be combined to analyze large-scale household electricity consumption data and generate useful insights for understanding energy usage patterns.

## Author
Sushant Sutar