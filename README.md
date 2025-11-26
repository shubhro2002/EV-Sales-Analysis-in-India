# EV-Sales-Analysis-in-India

This project presents a comprehensive analysis of Electric Vehicle (EV) sales across Indian states, using interactive Tableau dashboards. The goal is to uncover sales trends, identify top-performing regions, measure YoY growth, and visualize EV adoption patterns across the country.

## Project Overview

This Tableau project analyzes EV sales data using the following key components:

- Total EV Sales Overview

- Year-over-Year (YoY) Growth Analysis

- Top 10 States by EV Sales

- Best Performing State (KPI Card)

- EV Sales Over Time (Trend Line)

- Geographical Distribution of EV Sales (Map)

- Sales by EV Class

- Interactive Filters for Year Selection

The dashboards collectively provide deep insights into how EV adoption is evolving across India.

## Dataset Description

**Key Columns Used**

- Date

- Year

- Month / Month Short Name

- State

- EV Sales Quantity

- Vehicle Category

- Vehicle Class

- Vehicle Type

**Generated Fields**

- Latitude & Longitude (for map plotting)

- YoY Sales

- YoY % Growth


- Parameters:

  - Year Selected

  - Year Prior
 
## Data Preparation Steps

1. Data Cleaning

   - Removed null/unmapped states

   - Fixed state names for geocoding

   - Standardized month naming

   - Converted dates into proper Tableau date format

2. Calculated Fields Added

   - Sales - Selected Year

   - Sales - Prior Year

   - YoY % Growth

   - YoY Trend

3. Top N Filter Created

   - To display Top 10 states by EV sales.
  
## Insights Covered

Some key insights the dashboard enables:

- Which states are leading EV adoption?

- How fast is EV adoption growing year over year?

- Geographic clusters of high EV penetration.

- Which EV classes dominate sales (2W / 3W / 4W / Fleet EVs)?

- How the selected year's performance compares to previous years.

## Tools Used

- Tableau Public Desktop

- Python for Cleaning

- GIS Geocoding (Tableau built-in)
