# BMW Sales Analysis

<p align="center">
  <img src="https://images.unsplash.com/photo-1652967786766-2a9d7f3463f2?auto=format&fit=crop&fm=jpg&q=80&w=1200&h=360" alt="Close-up of a BMW car" width="760">
</p>

<p align="center">
  <strong>Exploring BMW sales trends, model performance, regional patterns, and pricing behavior.</strong>
</p>

A concise exploratory data analysis project using BMW sales data from 2010 to 2024.  
The goal is to understand sales volume patterns, model performance, regional differences, and sales classification trends.

## Project Overview

This project analyzes a BMW sales dataset containing 50,000 records across 11 columns, including model, year, region, fuel type, transmission, mileage, price, sales volume, and sales classification.

The analysis focuses on:

- checking dataset quality and structure
- exploring sales volume trends over time
- comparing sales volume across BMW models
- analyzing regional differences in High sales classification
- identifying whether the dataset shows realistic market patterns

## Data Source

The analysis uses the [BMW Dataset on Kaggle](https://www.kaggle.com/datasets/ayeshaseherr/bmw-dataset/data), stored locally as `data/BMW sales data (2010-2024).csv`.

The dataset includes BMW sales records from 2010 to 2024 with information about model, region, fuel type, transmission, mileage, price, sales volume, and sales classification.

## Key Findings

- The dataset contains no missing values or duplicate rows.
- Sales volume stays relatively stable between 2010 and 2024.
- The 7 Series has the highest total sales volume, while the M3 has the lowest.
- High sales are fairly evenly distributed across regions, with Europe slightly leading.
- Some patterns, such as similar pricing across models, suggest the dataset may be synthetic or simplified.

## Tools Used

- Python
- pandas
- matplotlib
- Jupyter Notebook

## Repository Structure

```text
bmw-analysis/
+-- data/
|   +-- BMW sales data (2010-2024).csv
+-- BMW_Sales_Analysis.ipynb
+-- README.md
```

## How to Run

1. Clone the repository.
2. Open `BMW_Sales_Analysis.ipynb` in Jupyter Notebook or JupyterLab.
3. Run the cells from top to bottom.

## Status

The project currently includes dataset overview, data quality checks, exploratory analysis, and final conclusions.

## Image Credit

Header image by [Ivan Kazlouskij](https://unsplash.com/photos/a-close-up-of-the-front-of-a-blue-bmw-car-rTQ3L4U8aZM) on Unsplash.
