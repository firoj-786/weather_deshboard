# 🌦 Weather Data Visualization using Python

This project uses a CSV file containing hourly weather data to visualize key weather trends such as temperature, apparent temperature, humidity, and wind speed over time.


The dataset includes the following columns:

- `Formatted Date`
- `Summary`
- `Precip Type`
- `Temperature (C)`
- `Apparent Temperature (C)`
- `Humidity`
- `Wind Speed (km/h)`
- `Wind Bearing (degrees)`
- `Visibility (km)`
- `Loud Cover`
- `Pressure (millibars)`
- `Daily Summary`

> ✅ Make sure your CSV is formatted correctly and named `weather_data.csv` (or change the filename in the code).

---

## 🚀 Features

- Converts and parses date/time column.
- Plots:
  - Actual Temperature vs Apparent Temperature
  - (Extendable to Humidity, Wind Speed, Pressure, etc.)
- Uses `Matplotlib` and `Seaborn` for attractive visuals.

---

## 🛠 Setup Instructions

1. **Clone the repository or download the code**

2. **Install dependencies**

```bash
pip install pandas matplotlib seaborn
📁 weather-visualizer/
│
├── weather_visualization.py   # Main Python script
├── weather_data.csv           # Your weather dataset
└── README.md                  # This readme file
