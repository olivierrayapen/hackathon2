# hackathon2
Data Exploration and Analysis from Public APIs
Analyzing the Environmental Impact of Vehicle Registration Trends on Air Quality in Mauritius

1. Introduction
As urbanization continues to expand across Africa, the number of vehicles on the roads is increasing rapidly. This rise in vehicle registrations is expected to have a significant impact on air quality, particularly in densely populated urban areas. This project aims to explore the correlation between vehicle registration trends and changes in air quality in Mauritius. By leveraging public APIs and vehicle registration data, this research will assess whether an increase in vehicle numbers is associated with deteriorating air quality.
2. Objective
The primary objective of this project is to analyze how trends in vehicle registrations correlate with air quality changes in Mauritius. This analysis will help to determine whether there is a significant impact of vehicle density on environmental conditions, which can provide valuable insights for policymakers and environmental agencies.
3. Methodology
Step 1:  API Selection:
OpenWeatherMap Air Pollution API: This API will be used to collect data on air quality, focusing on pollutants such as PM2.5, PM10, NO2, CO, and ozone in various regions.
Vehicle Registration Data Sources: Vehicle registration data will be sourced from national transport authorities, open data portals, or global automotive associations.
Step 2: Data Extraction
API Interaction: The data will be collected for the period from 2020 to the present.
Vehicle Registration Data Collection: Compile vehicle registration statistics for the same period from available sources.
Step 3: Data Cleaning and Preprocessing
Data Cleaning: extracted data will be cleaned and formatted consistently, addressing any missing values or anomalies.
Normalization: Normalize the data to account for differences in population density, urbanization rates, and vehicle types.
Step 4: Data Analysis
Correlation Analysis: Identify relationships between the number of vehicle registrations and levels of air pollution across different regions.
Time Series Analysis: Observe how air quality metrics have evolved in relation to changes in vehicle registrations over time.
Urban vs. Rural Comparison: Analyze the impact of vehicle registrations in urban areas versus rural areas, considering the differences in air quality patterns.
Step 5: Visualization
Heat Maps: Visualize air pollution levels across different regions and correlate these with vehicle density.
Line and Bar Charts: Illustrate trends in vehicle registrations and corresponding changes in air quality metrics over time.
Comparative Analysis: Visual comparisons between regions with high and low vehicle registration growth to highlight differences in air quality impact.
Step 6: Interpretation and Sharing
Conclusion: Summarize the key findings, identifying whether there is a significant relationship between the rise in vehicle numbers and air quality degradation.


# Hackathon2 Analysis

## Overview

This project analyzes the correlation between vehicle registrations and air pollution levels in Mauritius from 2020 to 2023. The analysis uses air pollution data obtained from the OpenWeatherMap API and vehicle registration data.

## Project Structure

- `air_pollution_data_2020_2023.csv`: Contains historical air pollution data from 2020 to 2023.
- `vehicle_registration_data_full.csv`: Contains vehicle registration data by type and year.
- `main.ipynb`: Jupyter Notebook containing the code for data analysis and visualization.
- `requirements.txt`: List of Python packages required to run the analysis.

