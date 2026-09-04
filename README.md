# Automobile Recession Analysis & Dashboard

## Project Overview

This project analyzes how recession periods affect automobile sales using a synthetic automobile sales dataset.

The project is divided into two parts:

- **Part 1:** Exploratory analysis and static visualizations using Pandas, Matplotlib, and Seaborn
- **Part 2:** Interactive dashboard development using Plotly and Dash

The goal is to turn automobile sales and economic indicators into clear, business-oriented insights.

## Project Objectives

The analysis focuses on understanding how automobile sales are influenced by:

- Recession periods
- GDP
- Consumer confidence
- Unemployment rate
- Vehicle prices
- Advertising expenditure
- Vehicle type
- Seasonality

The dashboard allows users to switch between:

- **Yearly Statistics**
- **Recession Period Statistics**

and interactively review multiple automobile sales visualizations.

## Part 1 — Data Analysis & Visualization

| Task | Analysis | Visualization |
|---|---|---|
| **1.1** | Yearly automobile sales trends | Line Chart |
| **1.2** | Advertising expenditure vs. automobile sales | Line Chart |
| **1.3** | Vehicle sales during recession vs. non-recession periods | Grouped Bar Chart |
| **1.4** | GDP variation during recession and non-recession periods | Subplots / Line Charts |
| **1.5** | Impact of seasonality on automobile sales | Bubble Plot |
| **1.6** | Consumer confidence and vehicle price vs. sales | Scatter Plots |
| **1.7** | Advertising expenditure by economic period | Pie Chart |
| **1.8** | Advertising expenditure by vehicle type during recessions | Pie Chart |
| **1.9** | Unemployment rate, vehicle type, and automobile sales | Line Plot |

## Part 2 — Interactive Dashboard

The interactive Dash application includes two report types.

### Recession Period Statistics

- Average automobile sales during recession years
- Average automobile sales by vehicle type
- Advertising expenditure by vehicle type
- Effect of unemployment rate on automobile sales

### Yearly Statistics

- Yearly automobile sales for the full period
- Monthly automobile sales for a selected year
- Average vehicle sales by vehicle type for a selected year
- Advertising expenditure by vehicle type for a selected year

The dashboard also includes:

- Report-type dropdown
- Year-selection dropdown
- Dynamic callbacks
- Interactive Plotly charts

## Key Insights

- Automobile sales generally decline during recession periods.
- Higher unemployment rates are generally associated with lower automobile sales.
- Higher consumer confidence tends to correspond with stronger automobile sales.
- Consumers become more price-sensitive during recessions, which can reduce demand for higher-priced vehicles.
- Advertising expenditure is lower during recession periods compared with non-recession periods.
- Vehicle categories respond differently to recessions, with smaller and more affordable vehicles tending to maintain stronger demand.
- Monthly sales patterns show clear seasonal variation.

## Technologies Used

| Technology | Purpose |
|---|---|
| **Python** | Core analysis and application development |
| **Pandas** | Data cleaning, filtering, grouping, and aggregation |
| **Matplotlib** | Static visualizations |
| **Seaborn** | Statistical and grouped visualizations |
| **Plotly Express** | Interactive charts |
| **Dash** | Interactive dashboard application |
| **Jupyter Notebook** | Analysis and dashboard development environment |
| **Git / GitHub** | Version control and project hosting |

## Repository Structure

```text
automobile-recession-analysis/
│
├── DV0101EN-Final-Assign-Part1-v1.jupyterlite.ipynb
├── Part_2_Create_Dashboard.ipynb
├── Part_2_Create_Dashboard.py
├── automobile_sales.csv
└── README.md
