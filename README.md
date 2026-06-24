# COVID-19 Global Data Analysis 🌍

A data analysis project that explores global COVID-19 trends using Python and real-world data from **Our World in Data**.

---

## 📊 What This Project Does

- Downloads the COVID-19 dataset automatically from Kaggle
- Cleans and prepares the data for analysis
- Finds the top 10 most affected countries
- Calculates death rates and cases per million people
- Draws 5 charts to visualize the results
- Shows an interactive world map

---

## 📁 Project Structure

```
covid-analysis/
│
├── covid_analysis.py        ← Main Python script (run this)
└── README.md                ← This file

Output charts (created after running the script):
├── chart1_top10_cases.png       ← Top 10 countries by total cases
├── chart2_death_rate.png        ← Top 10 countries by death rate
├── chart3_continent_pie.png     ← Cases split by continent
├── chart4_time_series.png       ← Daily new cases over time
└── chart5_world_map.html        ← Interactive world map (open in browser)
```

---

## 🗂️ Dataset

**Source:** Our World in Data — COVID-19 Dataset
**Kaggle Link:** https://www.kaggle.com/datasets/caesarmario/our-world-in-data-covid19-dataset

The dataset is downloaded automatically when you run the script. No manual download needed.

---

## 🛠️ Libraries Used

| Library | Purpose |
|---------|---------|
| `kagglehub` | Download dataset automatically from Kaggle |
| `pandas` | Load, clean, and analyze the data |
| `matplotlib` | Draw bar charts and line charts |
| `seaborn` | Make charts look nicer |
| `plotly` | Draw the interactive world map |

---

## ▶️ How to Run

**Step 1 — Install libraries:**
```bash
pip install kagglehub pandas matplotlib seaborn plotly
```

**Step 2 — Set up Kaggle API (first time only):**
1. Go to kaggle.com → Profile → Settings → API
2. Click **Create New Token** — downloads `kaggle.json`
3. kagglehub reads it automatically — no extra setup needed

**Step 3 — Run the script:**
```bash
python covid_analysis.py
```

All 5 charts will be saved in the same folder automatically.

---

## 📈 Results and Insights

- The **USA** recorded the highest total number of COVID-19 cases globally
- **Europe** and **North America** were the most affected continents
- Death rates varied by country — some exceeded 5% while others stayed below 1%
- The time series chart clearly shows multiple COVID-19 waves from 2020 to 2023
- Cases per million is a fairer comparison than raw numbers because it adjusts for population size

---

## 🧠 Skills Demonstrated

- ✅ Downloading real-world data using Kaggle API
- ✅ Data loading and exploration with pandas
- ✅ Data cleaning — handling missing values and filtering rows
- ✅ Feature engineering — death rate, cases per million
- ✅ GroupBy aggregation and sorting
- ✅ Time series analysis with 7-day rolling average
- ✅ Bar charts and pie charts with matplotlib and seaborn
- ✅ Interactive choropleth world map with plotly

---

## 👤 Author

**Muhammad Ahmad**
BS Information Technology — [University of Sargodha]
(https://github.com/ahmadsheikhbhk)
(https://www.linkedin.com/in/ahmadsheikh21)# COVID-19-Global-Data-Analysis
A data analysis project that explores global COVID-19 trends using Python and real-world data from Our World in Data.
