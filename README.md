# 🌍 Global COVID-19 Data Analysis

## 📌 Project Overview

The COVID-19 pandemic impacted countries differently in terms of infections, mortality, healthcare burden, and vaccination progress.

This project performs an end-to-end Exploratory Data Analysis (EDA) of global COVID-19 data using the Our World in Data (OWID) dataset. The analysis focuses on understanding pandemic trends, comparing countries fairly using population-adjusted metrics, and evaluating mortality through Case Fatality Rate (CFR).

---

## 🎯 Objectives

The primary objectives of this project are:

- Analyze global COVID-19 case and death trends.
- Compare pandemic impact across countries.
- Calculate and evaluate Case Fatality Rates (CFR).
- Identify countries with the highest mortality burden.
- Compare countries using per-million metrics.
- Explore vaccination progress and global pandemic patterns.
- Generate actionable insights from public health data.

---

## 📂 Dataset

**Source:** Our World in Data (OWID)

The dataset contains:

- Country and continent information
- Daily and cumulative COVID-19 cases
- Daily and cumulative deaths
- Population statistics
- Vaccination metrics
- Testing indicators
- Hospitalization information

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔍 Analysis Performed

### 1. Data Cleaning & Preparation

- Removed aggregate entities (World, Asia, Europe, etc.) for country-level comparisons.
- Handled missing values appropriately.
- Selected relevant features for analysis.

### 2. Global Pandemic Trend Analysis

- Global cases over time
- Global deaths over time
- Pandemic wave identification

### 3. Case Fatality Rate (CFR) Analysis

Calculated CFR using:

CFR = (Total Deaths / Total Cases) × 100

Used CFR to compare mortality severity across countries.

### 4. Deaths per Million Analysis

Compared countries using population-adjusted mortality metrics to ensure fair comparisons.

### 5. Country-Level Comparisons

Analyzed trends across major countries including:

- United States
- India
- Brazil
- United Kingdom
- Germany
- South Africa

### 6. Continental Heatmap Analysis

Visualized COVID-19 waves and intensity across continents over time.

---

## 📈 Key Findings

- More than **775 million confirmed cases** were reported globally.
- Over **7 million deaths** were recorded worldwide.
- The global Case Fatality Rate (CFR) was approximately **0.91%**.
- The United States recorded the highest number of total cases and deaths.
- Peru experienced the highest mortality burden relative to population size.
- Yemen recorded the highest Case Fatality Rate among analyzed countries.
- Pandemic intensity and timing varied significantly across continents.

---

## 📊 Executive Summary

| Metric | Value |
|----------|----------|
| Global Cases | 775.9 Million |
| Global Deaths | 7.06 Million |
| Global CFR | 0.91% |
| Highest CFR Country | Yemen |
| Highest Deaths per Million | Peru |
| Most Total Cases | United States |
| Most Total Deaths | United States |

---

## 💡 Insights

- Population-adjusted metrics provide fairer comparisons than raw totals.
- CFR helps assess disease severity beyond case counts.
- Pandemic waves occurred at different times across continents.
- Mortality burden varied significantly between countries.
- Vaccination progress was uneven across regions.

---

## 🚀 Future Improvements

- Interactive dashboard using Power BI or Tableau.
- Predictive modeling of future outbreaks.
- Vaccination effectiveness analysis.


---

## 📁 Repository Structure

```text
COVID19-Pandemic-Analysis-EDA/
│
├── notebooks/
│   └── COVID19_Analysis.ipynb
│
├── images/
│  └──  plots
│
├── README.md
├── requirements.txt
├── LICENSE

```

---

## 👤 Author

**Sakshi Patil**
