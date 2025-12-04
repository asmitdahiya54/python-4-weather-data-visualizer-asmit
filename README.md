🌦️ Weather Data Visualizer — Delhi Climate Analysis
B.Tech CSE (Cybersecurity) — Data Analysis Lab Assignment
Author: Asmit
📌 Project Overview

This project analyzes 5 years of Daily Delhi Climate data using Pandas, NumPy.
It demonstrates skills in:

Data acquisition

Cleaning and preprocessing

Statistical analysis

Grouping and aggregation

Data visualization

Storytelling using markdown

Exporting cleaned datasets and charts

The goal is to understand temperature, humidity, wind speed, and pressure trends.

📂 Folder Structure
weather-data-visualizer-Asmit/
│
├── README.md
├── data/
│   ├── DailyDelhiClimateTrain.csv
│   └── Cleaned_DailyDelhiClimate.csv
│
├── images/
│   ├── Daily_Temperature.png
│   ├── Humidity_vs_Temperature.png
│   ├── Monthly_Temperature.png
│   └── Temp_Humidity_Combined.png
│
├── notebook/
│   └── Weather_Analysis.ipynb
│
└── report/
    └── summary.md 
	📘 Assignment Tasks
	
✅ Task 1: Data Acquisition & Loading

Dataset downloaded from Kaggle.

Loaded using Pandas.

Inspected using:

df.head()

df.info()

df.describe()

✅ Task 2: Data Cleaning & Preprocessing

Converted date column to datetime.

Removed/handled missing values.

Selected relevant columns:

Temperature

Humidity

Wind Speed

Pressure

Cleaned data exported as:
data/Cleaned_DailyDelhiClimate.csv

📊 Task 3: NumPy Statistical Analysis

Statistical computations done using NumPy after grouping by month:

Mean temperature

Minimum temperature

Maximum temperature

Standard deviation

✔ Sample Output (Monthly Statistical Summary)
Metric	Description
mean	Average monthly temperature
min	Lowest temperature recorded in the month
max	Highest temperature recorded
std	Monthly temperature variation

Insights from NumPy analysis:

Summer months (May–June) show highest mean temperatures (33–35°C).

Winter months (Dec–Jan) show lowest mean temperatures (10–15°C).

Standard deviation is high in transitional seasons (Mar–Apr), showing unstable weather.

Temperature follows a clear seasonal cycle every year.

📈 Task 4: Visualizations (Matplotlib)

All charts saved in the images/ folder.

## 📈 Daily Mean Temperature
![Daily Temperature](./images/Daily_Temperature.png)

## 🌡️ Humidity vs Temperature
![Humidity vs Temperature](./images/Humidity_vs_Temperature.png)

## 📅 Monthly Average Temperature
![Monthly Temperature](./images/Monthly_Temperature.png)

## 🔄 Combined Temperature + Humidity Plot
![Combined Plot](./images/Temp_Humidity_Combined.png)

📆 Task 5: Grouping & Aggregation

Using Pandas groupby + resample:

Grouped by month → mean temperature

Calculated monthly statistics

Time-series resampling for smoothing

📤 Task 6: Export & Storytelling

Cleaned dataset saved as CSV.

All plots saved as PNG.

Final summary included in notebook as Markdown.

Repository organized professionally.

📝 Summary of Findings

Temperature displays strong seasonal behavior (hot summers, cold winters).

Humidity inversely relates to temperature.

Pressure and wind speed remain relatively stable.

NumPy statistical analysis confirms clear yearly climate cycles.

Delhi summers show extreme high temperatures with low humidity.

🛠️ Technologies Used

Python

NumPy

Pandas

Matplotlib

Jupyter Notebook

📌 How to Run the Project

Clone the repository

Open notebook/Weather_Analysis.ipynb

Run all cells

View generated images in the images/ folder




