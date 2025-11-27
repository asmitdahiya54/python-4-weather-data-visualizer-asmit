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
📊 NumPy Statistical Analysis

This project uses NumPy to compute statistical measures for understanding weather trends across months and years. After grouping the dataset by month, the following key statistics were calculated:

✔ Mean Temperature

Shows the average temperature for each month, helping identify warm and cold periods.

✔ Minimum & Maximum Temperature

Provides the temperature range, showing seasonal extremes.

✔ Standard Deviation

Indicates how much temperature fluctuates within each month.
Higher standard deviation = more variation in daily temperature.

Sample Output (Monthly Temperature Statistics)
	mean	min	max	std
2013-01	12.07	6.00	16.50	3.06
2013-02	16.86	13.66	20.80	1.84
2013-03	22.81	17.33	29.16	2.62
2013-04	28.89	24.60	32.12	2.11
2013-05	33.77	28.57	38.71	2.57
...
2016-12	17.67	14.00	21.20	1.79
2017-01	10.00	10.00	10.00	0.00
Insights from NumPy Analysis

Temperature consistently increases from January → June, showing pre-monsoon warming.

May & June have the highest mean temperatures.

January & December are the coldest months.

Months like April, May, June show higher standard deviation, meaning highly varying temperatures.

Some months (e.g., Jan 2017) show very low variation.

🧮 NumPy Functions Used

np.mean()

np.min()

np.max()

np.std()

Combined with Pandas groupby() for monthly aggregation.

ASMIT
