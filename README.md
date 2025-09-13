# auckland-temperatures
This is my project on forecasting Auckland Temperatures.

# Weather Forecast Analysis – Auckland January 2024  

## Project Overview  
This project analyzes and forecasts the **maximum hourly temperature in Auckland** during **January 2024**.  
The objectives are to:  
- Describe the main characteristics of the dataset.  
- Identify potential trends and periodicity.  
- Estimate the daily average temperature for **31 January 2024**.  
- Demonstrate the use of time series analysis tools in MATLAB.  

---

## Purpose  
Weather forecasting is essential for planning and decision-making.  
The purpose of this project is to model temperature patterns using statistical and computational techniques to understand short-term variations in Auckland’s summer climate.  

---

## Data  
- Dataset: `AKLJan2024Temp.csv` containing hourly maximum temperatures from **1 – 30 January 2024**.  
- Source:  MetService 

---

## Data Cleaning  
Steps taken:  
- Checked for missing or inconsistent values.  
- Removed anomalies outside Auckland’s expected summer range.  
- Converted timestamps into MATLAB-compatible date formats.  

---

## Modelling  
Techniques applied:  
- **Moving Averages** – smoothing short-term fluctuations.  
- **Curve Fitting / Regression / Extrapolation** – predicting 31 Jan 2024 average.  
- **Autocorrelation** – identifying repeating patterns.  
- **Fast Fourier Transform (FFT)** – detecting periodicity in temperature cycles.  

---

## Dashboards & Visualizations  
Key visual outputs include:  
- Time series plots of daily maximum temperatures.  
- Smoothed curves using moving averages.  
- Trend lines from regression models.  
- Autocorrelation plots.  
- FFT power spectrum for periodicity analysis.  

_All graphs include professional labels, titles, and legends._  

---

## Conclusion  
From the analysis:  
- The dataset’s variability and key characteristics were summarized.  
- Evidence for trends across January 2024 was explored.  
- An estimate for the average temperature on **31 Jan 2024** was provided.  
- Cyclical/periodic behavior was investigated.  

This project demonstrates how **MATLAB** can be used to model, visualize, and interpret climate data for short-term weather forecasting.  

---

## 📊 Report  
- [View Interactive Report (HTML)](https://justicebeaver26.github.io/auckland-temperatures/Temperatures.html)  

---

## Files Included  
- `Temperatures.mlx` → MATLAB Live Script code with analysis (downloadable).
- `Temperatures.html` → MATLAB Live Script exported as an html file.    
- `AKLJan2024Temp.csv` → Dataset.  

---
