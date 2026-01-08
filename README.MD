# Global EV Stock Growth Analysis (2010–2023)

This project analyses global electric vehicle (EV) adoption trends between 2010 and 2023, with a focus on **China**, **Europe**, and the **United States**.

The analysis combines **Python-based data cleaning** with **Tableau visual analytics** to compare:
- Absolute EV stock growth
- Share of global EV stock over time

---

## 📊 Dataset

- **Source:** Kaggle  
- **Dataset:** Global EV Sales (2010–2024)  
- **Link:** https://www.kaggle.com/datasets/patricklford/global-ev-sales-2010-2024

The dataset contains annual EV sales and stock figures by region and country.  
Only officially reported and aggregated values were used.

---

## 🎯 Project Objectives

- Clean and prepare raw EV sales and stock data
- Focus on the three largest EV markets:
  - China
  - Europe
  - United States
- Compare:
  - Absolute EV stock growth
  - Global EV stock share (%)
- Build a clear, readable Tableau dashboard suitable for portfolio presentation

---

## 🧰 Tools & Technologies

- **Python**
  - pandas
  - numpy
- **Tableau**
  - Line charts
  - Small multiples
  - Dashboard layout and formatting
- **CSV**
  - Cleaned dataset exported for Tableau

---

## 🧹 Data Cleaning (Python)

The raw dataset was cleaned using Python before being imported into Tableau.

### Key steps:
- Loaded raw CSV data from Kaggle
- Standardised column names
- Converted year and EV stock values to numeric types
- Removed rows with missing or invalid values
- Filtered data to:
  - China
  - Europe
  - United States
- Created calculated fields for:
  - Cumulative EV stock
  - Global EV stock share (%)
- Exported a cleaned CSV for Tableau analysis

---

## 📈 Data Visualisation (Tableau)

Two main visual analyses were created:

### 1. Global EV Stock Share by Region
- Shows how each region’s share of global EV stock evolved over time
- Highlights China’s rapid acceleration after 2019

### 2. EV Stock Growth by Region (Small Multiples)
- Absolute EV stock growth shown separately for each region
- Makes scale differences readable without distortion

---

## 🔍 Key Insights

- China’s EV stock growth accelerates sharply after 2019
- By 2023, China’s total EV stock is roughly **double Europe’s**
- The United States lags behind both China and Europe in absolute stock
- Visual separation (small multiples) improves interpretability versus a single combined chart

---

## 📁 Project Structure

