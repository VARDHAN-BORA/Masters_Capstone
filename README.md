# 🚲 Evaluating the Impact of Congestion Pricing on Citi Bike Operations

## Project Overview
This project aims to quantitatively assess the impact of New York City's congestion pricing policy on Citi Bike usage in Manhattan. By integrating Citi Bike trip data with weather and urban features, we use advanced statistical and machine learning models to analyze shifting mobility patterns and propose data-informed policy recommendations.

## Objectives
- Perform a comprehensive assessment of Citi Bike trip data before and after the implementation of congestion pricing.
- Analyze changes in ride frequency, average trip duration, and spatial distribution of station-level usage.
- Evaluate the influence of newly installed bike stations on redistributing ridership demand.
- Develop actionable insights and policy recommendations using AI-driven forecasting and optimization techniques.

## Methodology
We adopt a multi-model framework involving:
- **Data Collection & Feature Engineering**: Merging historical ride data (2021–2024) with weather records and urban features within a 500m radius of stations.
- **Time Series & Machine Learning Models**: Including ARIMA, SARIMAX, Prophet, Random Forest, XGBoost, and LSTM.
- **Geospatial Analysis**: Heatmaps, clustering, and proximity analysis to identify usage shifts across Manhattan.
- **Model Evaluation & Policy Simulation**: Comparing model performance and simulating outcomes under various congestion pricing scenarios.

## Installation & Requirements
- Python 3.8 or later
- Recommended tools: Jupyter Notebook / Google Colab
- Install dependencies:
  ```bash
  pip install -r requirements.txt
