# 🧠 Kubicle Data Wrangling Capstone Projects – Fabricio González Guasque

This repository contains two capstone projects developed as part of the **Kubicle Data & Analytics – Data Wrangling Certification**.

The projects demonstrate the use of **Python**, **APIs**, **Pandas**, and **data cleaning techniques** applied to real-world datasets.

---

## 🚀 Project 1: Frost Risk Alert Automation for Vineyards

**📘 Certification Module:** *Python – Connecting to Live Data*  
**🗂️ File:** `automatizacion_heladas_vinedos.ipynb`

### 🔍 Objective:
To help a vineyard company (*Vino Veritas*) avoid financial loss by automating the detection of frost risk for 17 vineyards using real-time weather data.

### ✅ Key Features:
- API connection to **WeatherAPI** to fetch 3-day forecast data by coordinates (lat/long)
- Data wrangling and joining from:
  - Local CSV (vineyards)
  - Online HTML table (country codes)
  - Remote CSV (city geolocation)
- Data cleaning: country name normalization, null handling, merge diagnostics
- Automated pipeline to check min temperatures and issue frost alerts
- Dashboard built with **Streamlit + Folium** to visualize vineyard risk on a map

### 📷 Outputs:
- `vineyards_forecast.csv`: final dataset with frost risk predictions
- Interactive map showing vineyard location and alert level
- Bar chart of minimum temperatures for the next day

---

## 🥗 Project 2: Nutritional Data Cleaning – Fetch Cuisine

**📘 Certification Module:** *Python – Data Preparation*  
**🗂️ File:** `wrangle_nutritional_data.ipynb`

### 🔍 Objective:
Clean and consolidate inconsistent nutritional data from multiple food suppliers for the meal kit company *Fetch Cuisine*.

### ✅ Key Features:
- Connected to **7 remote datasets** via direct CSV URL links
- Applied **regular expressions** to clean mixed-format numeric values (e.g. "30g", "25 cal")
- Handled:
  - Negative and out-of-range values
  - Nulls (calculated missing values using other nutrients)
  - Duplicate rows and inconsistent categories
  - Incorrect calorie calculations using `Calories = Fat*9 + (others)*4`
- Final dataset: 241 fully cleaned rows

### 📷 Outputs:
- `ingredients_cleaned.csv`: clean, deduplicated, and normalized data ready for use

---

## 🧰 Tech Stack

- **Python** (3.11+)
- **Pandas**, **NumPy**, **Matplotlib**, **Folium**
- **Streamlit** for dashboarding
- **WeatherAPI** for live forecast data
- HTML scraping with `pandas.read_html()`
- Regex with `re` module for string cleaning

---

## 🧑‍💻 About Me

**Fabricio González Guasque**  
Python Developer & Data Analyst with a background in Agronomic Engineering.  
🔗 [LinkedIn](https://www.linkedin.com/in/fabriciogonzalezguasque) | [GitHub](https://github.com/Fabriciogg8)

---

## 📜 Certification

These projects were developed as part of the **Kubicle Data Wrangling Certification**  
Milestones completed:
- SQL for Data Analysis
- Python Data Preparation
- Live Data Integration
