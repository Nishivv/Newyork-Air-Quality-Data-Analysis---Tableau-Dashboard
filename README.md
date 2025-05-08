# 🌤 New York Air Quality Data Analysis – Tableau Dashboard

This project visualizes and analyzes air quality trends in New York using Tableau. It highlights the correlation between solar radiation and temperature, enabling interactive exploration through dynamic filters and binning.

## 📊 Dashboard Overview

![Dashboard Screenshot](d1a14818-43b2-4ea7-9387-fe11cf894f5a.png)

### Key Features:
- **Correlation Plot:** Interactive scatter plot showing the relationship between Solar Radiation (`Solar.R`) and Temperature (`Temp`), color-coded by Month.
- **Automated Histogram:** Binned distribution of selected measures (e.g., `Solar.R`), with adjustable bin size via slider.
- **Dynamic Parameters:** Dropdown to switch between different measures (like Ozone, Wind, Solar.R).
- **Month Filter:** Heat-colored scale to observe seasonal patterns.


## 📁 Dataset Summary

| Column    | Description                     |
|-----------|---------------------------------|
| Ozone     | Ozone concentration (ppb)       |
| Solar.R   | Solar Radiation (Langley)       |
| Wind      | Wind speed (mph)                |
| Temp      | Temperature (°F)                |
| Month     | Month of observation (numeric)  |
| Day       | Day of the month                |


## 🛠 Tools Used

- **Tableau Public** – Interactive dashboard and visualization
- **Microsoft Excel** – Data preparation
- **CSV Dataset** – Extracted from NYC environmental records (sampled)


## 📈 Insights Extracted

- Positive correlation between **Solar Radiation** and **Temperature**.
- Certain months (like July–August) show denser and higher temperature clusters.
- Histogram reveals Solar.R distribution skewed toward mid and high range values.


## 📎 Files in Repo

- `NY_air_quality_data.csv` – Cleaned dataset
- `dashboard_screenshot.png` – Visual representation of the Tableau dashboard
- (Optional) `.twbx` or `.twb` – Tableau workbook (if not corrupted)


## 🔍 How to Use

1. Open the dataset in Tableau or Excel.
2. Recreate visualizations using filters:
   - Drag `Solar.R` to Columns
   - Drag `Temp` to Rows
   - Add `Month` as a color filter
   - Use `Bins` and Parameters for interactivity


## 📌 Author

Made with 📊 by Nishi Vijayvargiy
Feel free to connect on [LinkedIn](https://www.linkedin.com/in/nishi-vijayvargiya-849577192/) or share feedback!
