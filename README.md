# 🚲 Citi Bike Forecasting in a Post-Congestion Pricing NYC

In January 2025, New York City became the first U.S. metropolis to implement congestion pricing, dramatically reshaping how people move through Manhattan. As car tolls reshuffle commuting patterns, Citi Bike — NYC’s flagship bike-share program — is witnessing a significant shift in demand. This project explores that transformation.

We present a data-driven framework to forecast Citi Bike usage across Manhattan stations by integrating four years of ride history (2021–2024), real-time weather conditions, and rich urban contextual features like proximity to transit hubs, malls, parks, and residential zones.

This study doesn’t stop at forecasting. We also dig deep into *why* ridership changes — identifying which urban features matter most, how new stations are redistributing demand, and what strategies can help the system adapt more effectively to post-congestion pricing behaviors.

### What We Did:
- Merged historical Citi Bike trip data with urban and weather features
- Evaluated 16 forecasting models including ARIMA, SARIMAX, Prophet, XGBoost, Random Forest, and LSTM
- Analyzed ride frequency, trip duration, and geospatial redistribution of usage
- Simulated the impact of newly added stations in high-traffic zones
- Generated policy recommendations for optimizing station allocation and resource planning

### Key Insights:
- **LSTM models** consistently outperformed traditional models in predicting station-level demand
- Proximity to **metro stations, parks, and retail areas** had the strongest effect on trip volumes
- The introduction of new bike stations around the Central Business District helped **relieve pressure** on previously overloaded hubs
- The forecasting framework can support **real-time planning**, especially during major policy shifts like congestion pricing

### Why It Matters:
With micromobility becoming a central pillar of urban transport, especially in the face of climate policies and congestion controls, understanding — and anticipating — demand is no longer optional. Our work offers a scalable template for cities worldwide aiming to future-proof their bike-sharing infrastructure.

---


🔍 Paper and technical details included in this repository.

