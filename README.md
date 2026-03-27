# 🌦️ Weather Data Simulation & Visualization

 Overview

This project generates a synthetic daily weather dataset for the year **2023** and performs exploratory data analysis through visualizations. It simulates key weather attributes such as temperature, rainfall, humidity, and general weather conditions.

---

Technologies Used

* **Python**
* **Pandas** – data manipulation
* **NumPy** – random data generation
* **Matplotlib** – plotting
* **Seaborn** – advanced visualization

---
 Dataset Description

The dataset contains the following columns:

| Column      | Description                                        |
| ----------- | -------------------------------------------------- |
| Date        | Daily dates for 2023                               |
| Temperature | Simulated temperature (°C)                         |
| Rainfall    | Simulated rainfall (mm)                            |
| Humidity    | Simulated humidity (%)                             |
| Condition   | Weather condition (Sunny, Rainy, Cloudy, Overcast) |
| Month       | Extracted month from Date                          |
| Season      | Derived season based on month                      |

---

 Season Mapping

Seasons are assigned based on month:

* **Winter** → December, January, February
* **Spring** → March, April, May
* **Summer** → June, July, August
* **Autumn** → September, October, November

---
 Visualizations

### 1. Daily Temperature Trends

* Line plot showing temperature variation throughout the year.

### 2. Total Rainfall by Season

* Bar chart aggregating rainfall across seasons.

### 3. Temperature Distribution

* Histogram displaying frequency distribution of temperature.

### 4. Temperature vs Humidity

* Scatter plot illustrating the relationship between temperature and humidity, categorized by season.

### 5. Annual Weather Conditions

* Pie chart showing proportion of different weather conditions.

---
 How to Run

1. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn
```

2. Run the script in a Python environment.

---

 Key Insights (Example)

* Seasonal rainfall patterns can be observed clearly.
* Temperature distribution helps identify variability and extremes.
* Scatter plot highlights correlation trends between humidity and temperature.
* Pie chart provides an overview of dominant weather conditions.

---
 Output

* Multiple plots displayed using Matplotlib.
* Useful for practicing data analysis and visualization techniques.

---

 Future Improvements

* Use real-world weather datasets.
* Add time-series forecasting.
* Include interactive dashboards (e.g., Plotly, Dash).
* Perform statistical analysis and anomaly detection.

---
 License

This project is for educational and demonstration purposes.
