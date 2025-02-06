# ausplots_tsa
# Project Overview
This project analyzes **Digital Earth Australia (DEA) Fractional Vegetation Cover (FVC)** dataset (2010 - 2024) using **STAC API** for remote sensing time-series analysis. The script retrieves, processes, and visualizes **historical FVC trends**. 

# Features
- **STAC API Querying**: Retrieve DEA FVC dataset.
- **Cloud Masking**: Apply Landsat Fmask for data quality enhancement.
- **Spatial Masking**: Extract site-specific data.
- **Spatio-temporal Compositing**: Compute a median value for a given site for a given time. 
- **Time Series Analysis**: Smoothing, decomposition, and trend detection.
- **Probabilistic and Statistical Tests**: Mann-Kendall Trend analysis, RBEAST Change detection.
- **Advanced Visualization**: Polar and Spiral Plots for seasonal assessment.
