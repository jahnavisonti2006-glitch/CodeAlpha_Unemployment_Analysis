# CodeAlpha Task 2 - Unemployment Analysis with Python

## Overview

This project analyzes unemployment trends in India using Python and
data analysis and visualization techniques.

This project was completed as part of the CodeAlpha Data Science
Internship.

## Objectives

- Analyze unemployment trends over time
- Compare unemployment rates between 2019 and 2020
- Analyze unemployment across different regions
- Compare rural and urban unemployment
- Study monthly unemployment patterns
- Visualize unemployment trends using graphs and heatmaps

## Dataset

Dataset: Unemployment in India

Columns include:

- Region
- Date
- Frequency
- Estimated Unemployment Rate (%)
- Estimated Employed
- Estimated Labour Participation Rate (%)
- Area

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Preprocessing

The following preprocessing steps were performed:

1. Loaded the dataset using Pandas
2. Cleaned column names
3. Removed duplicate records
4. Converted the Date column into datetime format
5. Converted numerical columns into numeric data types
6. Handled missing values
7. Created Year and Month features

## Analysis

The analysis includes:

- Overall unemployment statistics
- Monthly unemployment trend
- 2019 vs 2020 comparison
- Regional unemployment analysis
- Monthly pattern analysis
- Rural vs urban comparison
- Region-month heatmap

## Key Results

- Overall average unemployment rate: 11.79%
- Maximum unemployment rate: 76.74%
- Minimum unemployment rate: 0.00%
- Average unemployment rate in 2019: 9.40%
- Average unemployment rate in 2020: 15.10%
- Rural average unemployment rate: 10.32%
- Urban average unemployment rate: 13.17%

## Visualizations

The project contains the following visualizations:

1. Monthly unemployment trend
2. 2019 vs 2020 comparison
3. Regional unemployment analysis
4. Monthly unemployment pattern
5. Rural vs urban unemployment
6. Region-month heatmap

## Project Structure

```text
CodeAlpha_Unemployment_Analysis/
│
├── Unemployment_Analysis.ipynb
├── Unemployment in India.csv
├── README.md
│
├── graphs/
│   ├── 01_monthly_trend.png
│   ├── 02_covid_impact.png
│   ├── 03_region_analysis.png
│   ├── 04_monthly_pattern.png
│   ├── 05_urban_rural.png
│   └── 06_heatmap.png
│
└── report/
    └── Task_2_Unemployment_Analysis_Report.pdf
