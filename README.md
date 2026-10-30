# Road Accident Pattern Analysis, India (DA-022)

Domain: Road Safety Analytics

## Problem
Understand when and where recorded road accidents in India are more frequent, and how severity varies with time, weather, cause and road features.

## Dataset
Indian Road Accident Dataset (2022-2025) on Kaggle by Mansehaj Preet:
https://www.kaggle.com/datasets/sehaj1104/indian-road-accident-dataset-20222025

20,000 records and 24 columns (city, state, date, hour, weather, road type, cause, severity, casualties and more). No personal information.

## What this project does
- Cleans the data (duplicate ids, dates, hours, locations, missing values)
- Compares accidents by hour, weekday, month, weather, cause, road features and state
- Builds 10 interactive charts (most of them animated) and a map of India
- Reports data-quality gaps and limitations
- Generates a PDF report and an HTML dashboard

## Files
- Road_Accident_India_DA022 (1).ipynb: full analysis code (run in Google Colab)
- indian_roads_dataset.csv: raw dataset
- indian_roads_cleaned.csv: cleaned dataset with extra columns (Weekday, Month, Year, Period, Severe)
- Road_Accident_India_Report (1).pdf: static report
- Road_Accident_India_Dashboard.html: dashboard (open in Chrome, internet needed)

## How to run
1. Open the notebook in Google Colab.
2. Run all cells (Runtime > Run all). The notebook downloads the dataset from Kaggle; if that fails, upload indian_roads_dataset.csv to the Colab files panel and run again.

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, Plotly, Google Colab

## Note
Descriptive analysis only. Findings show patterns, not causes, and counts are not adjusted for traffic volume. The dataset's collection method should be checked on its Kaggle page.
