\# Exploratory Data Analysis (EDA) Report: Airbnb Dataset

\#\# Introduction  
This report presents an in-depth exploratory data analysis (EDA) of an Airbnb dataset. The goal is to uncover trends, patterns, and insights that can help understand the Airbnb market better.

\#\# Dataset Overview  
\- \*\*Source:\*\* Airbnb open data (Kaggle)  
\- \*\*Number of rows:\*\* 953  
\- \*\*Number of columns:\*\* 7  
\- \*\*Key columns:\*\* Listing ID, Price, Room Type, Location, Availability, Reviews, etc.

\#\# Data Cleaning and Preprocessing  
\- \*\*Handled Missing Values:\*\*  
  \- Offer price: The (787) missing values were filled with their corresponding prices.  
  \- Other rows with missing values were dropped.  
\- \*\*Converted Data Types:\*\*  
  \- The room types, cities and countries were extracted from the \`Title\` column.  
  \- Price columns were converted to \`float\` data type.  
  \- Date columns were converted to \`datetime\` format.  
  \- \`Review and rating\` column was splitted into \`Review\` and \`Rating\` with their appropriate data types.  
  \- Categorical columns were optimized using the \`category\` data type.  
\- \*\*Duplicates:\*\*  
  The duplicated rows were handled, by deleting the duplicates and leaving the first entries.  
\- \*\*Outliers Treatment:\*\*  
  \- Extreme values in price and reviews were analyzed and treated accordingly.  
The dataframe ended up with 892 rows and 14 columns.

\#\# Univariate Analysis  
\#\#\# Distribution of Room Types  
\- \*\*Findings:\*\* Majority of listings are apartments and private rooms.  
\- \*\*Visualization:\*\* Bar chart showing room type distribution.

\#\#\# Price Distribution  
\- \*\*Findings:\*\* Prices are right-skewed, with a few high-priced outliers.  
\- \*\*Visualization:\*\* Histogram of price distribution.

\#\# Multivariate Analysis  
\#\#\# Price vs. Room Type  
\- \*\*Findings:\*\* Entire homes/apartments are significantly more expensive than shared rooms.  
\- \*\*Visualization:\*\* Boxplot showing price variations across room types.

\#\#\# Price vs. Location  
\- \*\*Findings:\*\* Certain neighborhoods have higher average prices.  
\- \*\*Visualization:\*\* Scatter plot of price distribution by location.

\#\# Key Insights  
\- The majority of Airbnb listings are concentrated in specific neighborhoods.  
\- Prices vary significantly based on location and room type.

\#\# Recommendations  
\- Users should target high-demand areas for better occupancy.  
\- Airbnb hosts could optimize pricing strategies based on seasonality and location trends.  
\- More detailed analysis could be done to predict price trends using machine learning.

\#\# Next Steps  
\- Consider feature engineering for predictive modeling.  
\- Compare Airbnb trends across different cities or time periods.

\*\*Author:\*\* \[Basit Adebayo Tiamiyu\](“https://github.com/lucid-bbayo”)    
\*\*Date:\*\* February 2025