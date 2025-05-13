# 🚲 Evaluating the Impact of Congestion Pricing on Citi Bike Operations

## Project Overview
This project aims to quantitatively assess the impact of congestion pricing on Citi Bike usage in Manhattan using advanced statistical and machine learning techniques. With congestion pricing launched in January 2025, we explore how this policy shift affects urban micromobility, specifically the frequency, duration, and spatial distribution of Citi Bike rides.

## Objectives
- Perform a comprehensive assessment of Citi Bike trip data pre- and post-congestion pricing.
- Analyze variations in ride frequency, trip duration, and station utilization.
- Evaluate the impact of new bike stations on ridership redistribution.
- Develop data-driven policy recommendations leveraging AI-driven optimization techniques.

## Methodology
The project employs the following techniques:
- **Data Collection & Feature Engineering**  
  Integration of Citi Bike data (2021–2024) with daily weather data and urban features (e.g., parks, metro stations, malls) within 500m radius per station.
- **Time Series & Machine Learning Models**  
  Forecasting methods include ARIMA, SARIMAX, Prophet, Random Forest, XGBoost, Ridge Regression, and LSTM.
- **Geospatial Analysis**  
  Used to visualize station usage and proximity to key urban infrastructure using heatmaps and spatial clustering.
- **Policy Recommendations & AI Optimization**  
  Insights translated into actionable strategies for improving Citi Bike operations post-congestion pricing.

## Installation & Requirements
- Python 3.8 or later
- Required packages are listed in `requirements.txt`
- To install dependencies, run:
  ```bash
  pip install -r requirements.txt

## Results Summary
Best Performing Model: LSTM showed highest forecast accuracy at selected Manhattan stations.

Urban Feature Insights: Proximity to metro stations, parks, and malls had strong influence on trip counts.

Policy Recommendations: Redistribution of bike docks to high-demand zones can mitigate congestion-related surges.

## Team Members
Venkata Sai Vardhan Bora 

Praveen Kumar Govind Reddy 

Prudhvi Raj Maharana 

Andria Grace 
