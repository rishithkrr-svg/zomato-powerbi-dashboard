# Zomato Delivery Performance Dashboard (Power BI)

## Objective
Analyse Zomato delivery performance and find which factors affect delivery time.

## Dataset
Zomato delivery time dataset from Kaggle (train file, 20 columns).

## Tools
Power BI, Power Query

## Data Cleaning (Power Query)
- Removed NaN and blank rows (Road_traffic_density, Festival, Ratings, Age)
- Trimmed text columns
- Removed text prefixes from Time_taken(min) and Weatherconditions
- Removed errors and duplicates

## Dashboard


![Dashboard](dashboard.png)



Includes:
- 4 KPI cards: Total Orders, Avg Delivery Time, Avg Rating, Avg Age
- Avg delivery time by traffic density, vehicle type and city
- Orders trend by date, orders by order type
- Slicers: City, Festival, Road traffic density

## Files
- dashboardpowerbi.pbix
