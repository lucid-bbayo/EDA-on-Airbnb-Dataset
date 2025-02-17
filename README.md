
# Airbnb Data Analysis

This project focuses on analyzing an Airbnb dataset to uncover insights regarding pricing, discounts, stay duration, and customer reviews. The analysis is performed using Python, with visualizations to support key findings and multiple linear regression models for deeper understanding.

## Table of Contents
1. [Project Objective](#project-objective)
2. [Dataset](#dataset)
3. [Data Preparation](#data-preparation)
4. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
5. [Regression Analysis](#regression-analysis)
6. [Visualizations](#visualizations)
7. [Conclusion](#conclusion)
8. [How to Run the Code](#how-to-run-the-code)

## Project Objective
The main objective of this project is to clean, analyze, and visualize an Airbnb dataset to:
- Identify trends in pricing and stay durations across different months.
- Explore the relationship between discount, rating, and pricing.
- Build regression models to predict log-transformed prices.

## Dataset
The dataset contains information about Airbnb listings, including:
- **Price** and **Offer Price**
- **StartDate** and **EndDate** of stays
- **Number of Beds**
- **Review and Rating** information

## Data Preparation
Several steps were taken to clean and prepare the data for analysis:
- Filled missing offer prices with regular prices.
- Extracted and converted date information.
- Calculated stay durations and discounts.
- Removed duplicate rows and cleaned numeric columns.
- Converted relevant columns to appropriate data types.

## Exploratory Data Analysis (EDA)
Key findings from the data include:
- **Price Distribution**: Skewed distribution, log-transformed for better regression analysis.
- **Stay Duration Analysis**: Longer stays in October, with shorter stays from January to May.
- **Correlation Analysis**: Price shows a moderate correlation with discount and rating.

## Regression Analysis
Several regression models were built to explore the relationship between variables:
1. **LogPrice vs StayDuration** – R²: 0.022
2. **LogPrice vs Rating** – R²: 0.058
3. **Discount vs Rating** – R²: 0.004
4. **Multivariable Regression** – LogOfferPrice, Discount, and StayDuration were combined to predict LogPrice.

## Visualizations
Visualizations were used extensively to support the analysis:
- Histograms and Boxplots for numeric columns.
- Correlation heatmaps.
- Barplots showing average stay duration by month.
- Line plots for price trends over time.

## Conclusion
The analysis provided valuable insights into Airbnb listings and highlighted trends in pricing and stay durations. The regression models, while limited in predictive power, were useful for understanding variable relationships.

## How to Run the Code
1. Ensure you have Python 3.x installed.
2. Install the required packages:
   ```bash
   pip install pandas numpy matplotlib seaborn statsmodels plotly
   ```
3. Run the Python code provided in the Jupyter Notebook or script file.

---
**Author**: Basit Adebayo Tiamiyu  
**Date**: February 2025
