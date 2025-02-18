
# Airbnb Data Analysis

This project focuses on analyzing an Airbnb dataset to uncover insights regarding pricing, discounts, stay duration, cities, and countries. The analysis is performed using Python, with visualizations to support key findings for deeper understanding.

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
- `RoomType`, `City` and `Location` (Country) of listing.
- `Price` and `Offer Price`
- `StartDate` and `EndDate` of stays
- `Number of Beds`
- `Review and Rating` information

## Data Preparation
Several steps were taken to clean and prepare the data for analysis:
- Extracted the room types, cities and countries from the `Title` column.
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

## Visualizations
Visualizations were used extensively to support the analysis, which include:
- Histograms and Boxplots for numeric columns.
- Bar chart showing room type distribution.
- Correlation heatmaps.
- Boxplot showing price variations across room types.
- Barplots showing average stay duration by month.
- Scatter plot of price distribution by location.
- Line plots for price trends over time.
  
![top_room_types](https://github.com/user-attachments/assets/bec4dc4d-3388-4a9a-9418-c5b88b53af09)
![price_distribution](https://github.com/user-attachments/assets/7f531417-abf8-4372-8a1b-118a1f93a12d)
![prices_across_room_types](https://github.com/user-attachments/assets/90eac0ae-148b-4f79-a41b-8ee53926fcc2)
![price_by_city](https://github.com/user-attachments/assets/a868b5d7-172d-40d4-8714-c734dd3bf89c)
![price_by_country](https://github.com/user-attachments/assets/87e0d62b-ffb8-45b6-be5d-f49fec9b6612)
![price_trend_over_time](https://github.com/user-attachments/assets/f698d403-1a5c-4db2-9305-e23de929688a)
![avg_price_per_month](https://github.com/user-attachments/assets/13631df4-8250-4005-aa10-94c42e3d8239)
![avg_stay_per_month](https://github.com/user-attachments/assets/0ac0e0ee-e0de-46ba-9915-896a5b00df88)
![cities_with_most_listings](https://github.com/user-attachments/assets/57bb45e7-ac4a-433d-9dc6-ac4d6364966c)
![countries_with_most_listings](https://github.com/user-attachments/assets/50d4a19f-3bf5-4246-abfe-167bc9777be3)

## Conclusion
The analysis provided valuable insights into Airbnb listings and highlighted trends in pricing and stay durations. Prices vary significantly based on location and room type. The regression models, while limited in predictive power, were useful for understanding variable relationships.

## How to Run the Code
1. Ensure you have Python 3.x installed.
2. Install the required packages:
   ```bash
   pip install pandas numpy matplotlib seaborn statsmodels plotly
   ```
3. Run the Python code provided in the Jupyter Notebook or script file.

**Author**: [Basit Adebayo Tiamiyu](https://github.com/lucid-bbayo/)
**Date**: February 2025
