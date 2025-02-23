
# Time Series Analysis Assignment

## Description

This project demonstrates time-series analysis techniques using a selected free dataset. The primary focus is on identifying anomalies within the dataset using the following methodologies:

1. **Simple Moving Average (SMA):**
   - Calculated using Pandas and visualized with Matplotlib.
   - Provides insights into overall trends by smoothing fluctuations in the data.

2. **Exponential Smoothing:**
   - Implemented using Statsmodels and visualized with Matplotlib.
   - Captures recent trends while assigning exponentially decreasing weights to older observations.

3. **Seasonal-Trend Decomposition:**
   - Conducted using the Prophet library.
   - Separates the time series data into seasonal, trend, and residual components to explore underlying patterns.

## Methods and Tools

- **Dataset:** Power Consumption Data (Hourly)
- **Libraries Used:**
  - `Pandas` for data manipulation.
  - `Matplotlib` for visualizations.
  - `Statsmodels` for exponential smoothing.
  - `Prophet` for seasonal-trend decomposition.

## Objectives

1. Perform and visualize the simple moving average to observe trends.
2. Apply exponential smoothing to identify anomalies with a focus on recent data points.
3. Decompose the time series data to analyze seasonal, trend, and irregular components.
4. Justify the use of each model in identifying anomalies.

## Results and Insights

- **Simple Moving Average:** Highlighted general trends but lacked sensitivity to recent changes, making it less effective for real-time anomaly detection.
- **Exponential Smoothing:** Detected anomalies by weighting recent data points more heavily, making it suitable for near-term trend identification.
- **Seasonal-Trend Decomposition:** Provided a detailed view of periodic trends and residual anomalies, offering comprehensive insights into the data structure.

## Conclusion

Each method has unique strengths for time-series analysis. While SMA is suitable for general trend analysis, exponential smoothing is more reactive to recent changes, making it ideal for detecting anomalies in real-time. Seasonal decomposition offers a granular understanding of the data, particularly useful for datasets with recurring patterns.
