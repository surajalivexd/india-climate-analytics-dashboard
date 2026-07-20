# india-climate-analytics-dashboard
India Climate Analytics Dashboard (2000–2024)

An end-to-end data analytics project exploring 25 years of daily weather data across 10 major Indian cities — from raw data to pivot table analysis to an interactive Power BI dashboard.

Objective

To analyze long-term temperature and rainfall patterns across India's major cities and answer questions like:

Which cities are warming the fastest over the last 25 years?
How intense and volatile is the monsoon across different regions?
What does the seasonal rainfall and temperature calendar look like for each city?
Data source

Daily weather records for 10 Indian cities from 2000–2024, sourced from Kaggle. The fact table contains 91,320 daily records across 18 columns (~1.64 million cells), covering metrics like max/min temperature, precipitation, and derived indicators.

Tools used
Excel — data cleaning, feature engineering (year/month/season columns, anomaly percentage via VLOOKUP/XLOOKUP, heatwave flags using PERCENTILE.INC), and pivot table analysis
Power BI — interactive multi-page dashboard with DAX measures, conditional formatting, slicers, and combo charts
Pivot tables → dashboard pages
Pivot table	Power BI visual	What it shows
Warming Trend	Line chart	Year-over-year avg. max temperature by city
Monsoon Intensity	Clustered column chart	Total rainfall by year and city
Monsoon Volatility Matrix	100% stacked bar chart	Proportion of rain-day categories (heavy/light/moderate/no rain) per city
City Climate Profile	Matrix (heatmap)	Avg. rainfall and avg. temperature by month × city
Annual Climate Calendar	Combo chart (climograph)	Monthly rainfall (bars) vs. avg. temperature (line)
