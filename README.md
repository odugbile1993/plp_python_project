# 🌍 COVID-19 Data Analysis Project

This project explores COVID-19 trends across **Kenya**, **United States**, and **India** using data from [Our World in Data (OWID)](https://covid.ourworldindata.org). The goal is to understand case progression, death rates, and vaccination trends through data cleaning, exploratory data analysis (EDA), and visualization.



## 📁 Dataset

- **Source**: [OWID COVID-19 Dataset](https://covid.ourworldindata.org/data/owid-covid-data.csv)
- **Format**: CSV
- **Coverage**: Global, daily updates per country



## 🛠️ Technologies Used

- **Python 3**
- **Pandas** – for data cleaning & manipulation  
- **Matplotlib & Seaborn** – for data visualization  
- **Plotly Express** – for interactive choropleth map (optional)
- **Jupyter Notebook / Google Colab**



## ✅ Project Workflow

### 1️⃣ Data Cleaning
- Filtered countries: `Kenya`, `United States`, `India`
- Converted date column to datetime
- Handled missing values via interpolation
- Computed derived columns (e.g. death rate)

### 2️⃣ Exploratory Data Analysis (EDA)
- Line plots for total cases and deaths
- Comparison of daily new cases
- Death rate trends across countries

### 3️⃣ Vaccination Analysis
- Trends in vaccination rollout
- Bar chart for % of fully vaccinated population

### 4️⃣ Optional: Choropleth Map
- Global view of total cases by country using Plotly

### 5️⃣ Insights Summary
- Markdown-based conclusions highlighting patterns, anomalies, and key takeaways



## 📊 Visual Outputs

- 📈 Line plots (cases, deaths, new cases)
- 📉 Death rate trends
- 📊 Bar charts (vaccination comparison)
- 🌍 Interactive map (if enabled)



## 📌 Key Insights (Example)

- The United States leads in both total cases and vaccination rollout.
- India saw the highest peak in daily cases during its second wave.
- Kenya had slower vaccination progress and relatively stable case trends.
- Death rates decreased after vaccine rollouts in all three countries.

*See full analysis in the notebook.*



## 📂 File Structure

```bash
├── covid_analysis.ipynb       # Main Jupyter Notebook
├── README.md                  # Project documentation
├── requirements.txt           # (Optional) Required packages
└── images/                    # (Optional) Saved plots

