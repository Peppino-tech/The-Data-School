🔋 Global EV Stock Growth Analysis (2010–2023)

A data analytics project analysing global electric vehicle (EV) adoption trends using Python for data cleaning and Tableau for visual storytelling.

The project focuses on China, Europe, and the United States, comparing:

Absolute EV stock growth

Share of global EV stock over time

📌 Project Overview

Electric vehicle adoption has accelerated rapidly over the last decade, with significant regional differences.
This project explores how EV stock has evolved globally, highlighting China’s rapid acceleration after 2019 and the widening gap with other major markets.

The workflow follows a real-world data analytics pipeline:

Raw data ingestion

Data cleaning and transformation in Python

Visual analysis and dashboard creation in Tableau

📂 Data Source

Dataset: Global EV Sales (2010–2024)

Provider: Kaggle

Link: https://www.kaggle.com/datasets/patricklford/global-ev-sales-2010-2024

Notes:

Only officially reported, aggregated figures were used

The analysis window was restricted to 2010–2023

World totals were excluded from some visualisations to avoid distortion

🎯 Objectives

Clean and prepare raw EV sales and stock data

Focus on the three largest EV markets:

China

Europe

United States

Compare:

Absolute EV stock growth

Global EV stock share (%)

Build a clear, readable Tableau dashboard suitable for portfolio presentation

🛠 Tools & Technologies

Python

pandas

numpy

Tableau

Line charts

Small multiples

Dashboard layout and formatting

CSV

Cleaned dataset exported for Tableau

🧹 Data Cleaning (Python)

The raw dataset was cleaned and prepared in Python before being imported into Tableau.

Key steps:

Loaded raw CSV data from Kaggle

Standardised column names

Converted year and EV stock values to numeric types

Removed rows with missing or invalid values

Filtered the dataset to:

China

Europe

United States

Created derived fields:

EV stock by region

Global EV stock share (%)

Exported a cleaned CSV for Tableau analysis

📊 Visual Analysis (Tableau)

The Tableau dashboard includes:

1. Global EV Stock Share by Region (2010–2023)

Shows how each region’s share of global EV stock has evolved

Highlights China’s sharp acceleration after 2019

2. EV Stock Growth by Region (Absolute Values)

Small multiples comparing absolute EV stock growth

Makes scale differences between regions immediately clear

Design choices:

Consistent axes to avoid misleading comparisons

Labels shown only at line ends for clarity

Millions and percentage formats applied across charts

💡 Key Insights

China’s EV stock growth accelerates sharply after 2019

By 2023, China’s EV stock is roughly double Europe’s

The United States shows steady growth but lags significantly behind

Global EV adoption is increasingly concentrated in a small number of regions

📁 Project Structure
global-ev-stock-analysis/
│
├── data/
│   ├── raw/                # Original Kaggle dataset (unchanged)
│   └── processed/          # Cleaned dataset used in Tableau
│
├── python/
│   └── data_cleaning.ipynb # Python data cleaning script
│
├── tableau/
│   ├── dashboard.twbx      # Tableau workbook
│   └── screenshots/        # Dashboard images
│
├── README.md

🚀 How to Use

Clone the repository

Review the Python notebook to see the data cleaning process

Open the cleaned CSV in Tableau

Explore the interactive dashboard