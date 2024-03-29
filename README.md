# Interactive Housing Sales Analytics Dashboard

## Screenshot of Dashboard

<img width="1470" alt="image" src="https://github.com/gaurichaudhari9/house-sales-viz/assets/25304556/9018cd57-af9d-4db9-9220-e883b5abac97">

## Overview

This dashboard visualizes and analyzes housing sales data for King County, Washington. The dashboard features a calendar widget, line chart, map, histograms, and a heatmap, providing a user-friendly interface to explore the dataset. The purpose is to understand trends in housing prices and identify relationships between price and other attributes like number of bedrooms/bathrooms, square footage, view, condition, etc. 

The dashboard allows users to filter the data by month and day to see how prices change over time. Additional filters for year built, square feet living area, and square feet lot area allow further slicing of the data.

## Data

The data comes from a dataset of house sales transactions in King County between May 2014 - May 2015. It contains the following attributes:

- ID - Unique ID for each transaction 
- Date - Date of the transaction
- Price - Price of the sold property 
- Bedrooms - Number of bedrooms 
- Bathrooms - Number of bathrooms
- Sq ft living - Size of living area in square feet
- Sq ft lot - Lot size in square feet 
- Floors - Number of floors
- Waterfront - Whether the property is waterfront or not
- View - Category for view from property (no view to excellent view) 
- Condition - Category for condition of the property (worn out to very good)
- Grade - Grade of the property (higher is better)
- Year built - Year the property was built
- ZIP code
- Latitude 
- Longitude

The data was loaded into Tableau and the following transformations applied:

- Changed date format from text to date
- Changed the number format of square feet living and square ft lot to not have decimals and to include the thousands marker.

## Filters - To the left of the dashboard

- **Calendar Widget:** This main filter allows users to select a specific month or day, influencing the visuals on the right.
- **Additional Filters:** Three sliders filter data based on the year built, square foot living, and square foot lot.

## Analysis

The dashboard consists of the following visualizations:

- Line chart showing average price over time
- Map showing average price by ZIP code, colored by price  
- Histogram showing distribution of house prices
- Histograms for distribution of number of bedrooms and bathrooms
- Heatmap showing average price by view and condition

The visualizations allow us to identify trends like:

- Prices increasing over time
- Areas with higher concentrations of expensive houses
- Most houses having 2-4 bedrooms and 1-3 bathrooms 
- Higher prices for better views and conditions

## Instructions 

The dashboard can be filtered in the following ways:

- Select month and day from calendar to filter all visualizations to that time period
- Use sliders for year built, square feet living area, and square feet lot area to filter the bottom 4 visualizations
- Hover over marks in the visualizations to see more details

The dashboard is interactive and allows slicing data in different ways to uncover insights. 

## Dashboard

The dashboard can be viewed here: https://public.tableau.com/app/profile/gauri.chaudhari/viz/KingCountyHouseSales_17041554469630/KingCountyHouseSales
