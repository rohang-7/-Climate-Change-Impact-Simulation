![Climate Impact Simulation Banner](https://github.com/rohang-7/Climate-Change-Impact-Simulation/blob/main/Cluster%20Map.png?raw=true)

#  Climate Change Impact Simulation (Melbourne, Australia)

This project analyzes real-time and historical weather data to simulate and visualize the **impact of climate change in Melbourne**.  
Using live data from the **OpenWeatherMap API**, it explores temperature variations, rainfall trends, and urban heat zones — applying **machine learning (DBSCAN & KMeans)** and **forecasting (Prophet)** to predict climate patterns and identify risk-prone regions.

The goal is to help understand how +1.5°C and +2.0°C global warming scenarios could affect city-level climate dynamics, guiding sustainability and resilience planning.

---

## Project Overview

- Collected and cleaned live weather data from **OpenWeatherMap API** (JSON-based).  
- Built a dataset combining **temperature, humidity, rainfall, wind, and pressure** metrics.  
- Applied **DBSCAN clustering** to detect **heatwave-prone and cool zones** across Melbourne.  
- Forecasted temperature and rainfall using **Facebook Prophet** (time-series forecasting).  
- Simulated **warming scenarios (+1.5°C and +2.0°C)** aligned with IPCC climate targets.  
- Created **interactive visualizations and heatmaps** for spatial and temporal insights.

---

## Key Findings

- **Urban Heat Zones:** Detected clusters of elevated temperature, primarily in dense suburbs.  
- **Tree Coverage Impact:** Areas with higher vegetation (urban forests) showed lower heat intensity.  
- **Rainfall Forecast:** The Prophet model predicts variable rainfall trends with potential decline post-2030.  
- **Temperature Trend:** Notable +1.8°C increase simulated across Melbourne by 2050 under high-emission scenarios.  
- **Heat Index:** "Feels-like" temperatures rise significantly beyond measured values, highlighting humidity’s role.  

This project showed how **data, weather APIs, and analytics** can reveal crucial insights about our planet’s future.

---

## Tools & Libraries

- **Python:** pandas, numpy, matplotlib, seaborn  
- **Geospatial:** geopandas, folium, shapely  
- **Clustering:** scikit-learn (DBSCAN, KMeans)  
- **Forecasting:** Prophet  
- **Data Source:** OpenWeatherMap API  
- **Environment:** Google Colab / Jupyter Notebook  

---

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/rohang-7/Climate-Change-Impact-Simulation.git
   cd Climate-Change-Impact-Simulation


## Future Work

Integrate satellite and air-quality data (NASA / AQI APIs).
Build an interactive Streamlit dashboard for live city-level updates.
Expand analysis across multiple Australian cities.
Combine environmental and social impact metrics (energy demand, health exposure).
