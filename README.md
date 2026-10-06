Electricity Consumption Analytics

Project Overview

This project analyzes electricity consumption data from three different zones using Python. The analysis identifies total power consumption, the highest-consuming zone, peak consumption hours, monthly consumption patterns, and weather-related factors.

Objective

* Analyze electricity consumption across three zones.
* Calculate total power consumption.
* Identify the highest-consuming zone.
* Find the peak consumption hour.
* Analyze monthly consumption trends.
* Create visualizations to understand consumption patterns.
* Generate business insights and recommendations.

Dataset

The dataset contains electricity consumption records collected at 10-minute intervals.

Dataset size: 52,416 rows and 9 columns.

Main Columns

* Datetime
* Temperature
* Humidity
* WindSpeed
* GeneralDiffuseFlows
* DiffuseFlows
* PowerConsumption_Zone1
* PowerConsumption_Zone2
* PowerConsumption_Zone3

Technologies Used

* Python
* Pandas
* Matplotlib
* Jupyter Notebook

Data Processing

A new calculated column was created:

Total Power Consumption = Zone 1 + Zone 2 + Zone 3

The dataset was also cleaned by checking missing values, duplicates, and converting the Datetime column into the correct format.

Analysis Performed

1. Total Power Consumption
2. Highest Consumption Hour
3. Highest Consumption Zone
4. Power Consumption by Zone
5. Monthly Consumption Analysis
6. Top 3 Highest Consumption Periods
7. Average Daily Consumption
8. Weather and Power Consumption Analysis

Visualizations

* Power Consumption by Zone — Bar Chart
* Zone Contribution — Pie Chart
* Monthly Power Consumption Trend — Line Chart
* Temperature vs Power Consumption — Scatter Plot

Key Insights

* Total power consumption is approximately **3.73 billion**.
* Zone 1 has the highest overall consumption.
* 8:00 PM is the highest consumption hour.
* July 2017 recorded the highest monthly consumption.
* Electricity consumption varies across different months and zones.

 Recommendations

* Focus energy-saving measures on Zone 1.
* Monitor electricity usage during peak evening hours.
* Plan energy requirements for high-consumption months.
* Continuously monitor all zones to identify unusual consumption patterns.

Project Files

* Electricity_Consumption_Analytics.ipynb — Jupyter Notebook containing the complete analysis.
* powerconsumption.csv — Dataset used for the analysis.

Conclusion

This project demonstrates how Python and data analysis techniques can be used to understand electricity consumption patterns and generate useful insights for improving energy efficiency.
