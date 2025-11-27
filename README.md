# Weather Data Visualizer - Asmit

## Assignment Overview
This project is a mini assignment for the course **Programming for Problem Solving using Python**.  
The goal is to analyze and visualize **daily weather data of Delhi** to understand climate patterns and trends over 5 years.

---

## Dataset
- **Source:** Daily Delhi Climate dataset (CSV format)  
- **Columns:**
  - `date` – Date of observation
  - `meantemp` – Mean daily temperature (°C)
  - `humidity` – Mean daily humidity (%)
  - `wind_speed` – Average wind speed (km/h)
  - `meanpressure` – Mean daily pressure (hPa)
- **Cleaned Dataset:** `data/Cleaned_DailyDelhiClimate.csv`  

---

## Tools Used
- Python 3  
- Jupyter Notebook  
- Libraries: Pandas, NumPy, Matplotlib, Seaborn  

---

## Project Structure
weather-data-visualizer-Asmit/
│
├─ data/
│ ├─ DailyDelhiClimateTrain.csv
│ └─ Cleaned_DailyDelhiClimate.csv
│
├─ images/
│ ├─ Daily_Temperature.png
│ ├─ Humidity_vs_Temperature.png
│ ├─ Monthly_Temperature.png
│ └─ Temp_Humidity_Combined.png
│
├─ notebook/
│ └─ Weather_Analysis.ipynb
│
└─ report/
└─ Summary.md 


---

## Analysis & Visualizations
1. **Daily Mean Temperature** – Line chart showing temperature trends over 5 years.  
2. **Humidity vs Temperature** – Scatter plot to explore correlation between humidity and temperature.  
3. **Average Monthly Temperature** – Bar chart displaying seasonal variations.  
4. **Temperature & Humidity Combined** – Line chart showing relationship between temperature and humidity over time.  

---

## Insights
- Temperature rises during summer months and falls during winter.  
- Humidity has some correlation with temperature trends.  
- Seasonal patterns are evident in monthly average temperature.  
- Wind speed and pressure show minor fluctuations without strong seasonal patterns.  

---

## How to Run
1. Open `notebook/Weather_Analysis.ipynb` in Jupyter Notebook.  
2. Run cells **in order** from top to bottom to load data, clean, analyze, and visualize.  
3. All cleaned data and plot images are saved in the respective folders (`data/` and `images/`).  

---

ASMIT