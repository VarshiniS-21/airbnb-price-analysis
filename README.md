# airbnb-price-analysis
Exploratory analysis of NYC Airbnb listings using Python and SQL
# NYC Airbnb Listings Analysis (Python & SQL)

## Project Overview
Airbnb, started in 2008, lets people rent out anything from a spare room to a full apartment, and lets travelers book stays almost anywhere in the world. Because it offers more variety and often better value than hotels, it has become one of the most widely used travel platforms.

This project studies Airbnb listings in New York City to understand how the market works: where listings are concentrated, what guests prefer, and what affects the price.

## Objective
The goal is to turn raw listing data into useful insights for:
- **Hosts**, who want to price and position their listings better
- **Travelers**, who want to find good-value areas and room types
- **Analysts and businesses**, who want to understand supply and demand in the market

## Dataset
The data is the public "NYC Airbnb Open Data (2019)" set from Kaggle, with 48,895 listings. It covers:
- **Location:** borough, neighbourhood, latitude, and longitude
- **Listing details:** room type, price, and minimum nights
- **Reviews:** total reviews, last review date, and reviews per month
- **Host details:** host ID and number of listings per host
- **Availability:** number of days available in a year

## Analyses Performed
1. **Average price by borough:** compared prices across Manhattan, Brooklyn, Queens, the Bronx, and Staten Island.
2. **Room type preference:** checked how listings split between entire homes, private rooms, and shared rooms.
3. **Popular neighbourhoods:** found the areas with the most listings and activity.
4. **Average price by month of last review:** looked at how prices vary across review months.
5. **Price variation by borough:** studied how widely prices spread within each borough.
6. **Price vs number of reviews:** tested whether cheaper or pricier listings get more reviews.
7. **Hosts by borough and room type:** compared how many hosts operate in each area and category.
8. **Correlation analysis:** checked how numeric features relate to each other.

## Visualizations Used
- Bar charts for comparing averages and counts
- Pie charts for room type share
- Line plot for the monthly price pattern
- Scatter plots for price vs reviews and availability
- Correlation heatmap for feature relationships

## Key Insights
- Manhattan and Brooklyn together hold about 85% of all listings.
- Manhattan is the most expensive borough (median $150 per night), well above Brooklyn ($90) and the Bronx ($65).
- Entire homes cost more than twice as much as private rooms (median $160 vs $70).
- Price shows almost no relationship with reviews or availability, so location and room type drive pricing far more than popularity.

## Practical Use
- **Hosts** can set prices by comparing with similar listings in the same area and room type.
- **Travelers** can find cheaper boroughs and room types without going far from the city center.
- **Businesses** can see where supply is concentrated and where the market is less crowded.

## Files
- `Air_Bnb_EDA.ipynb`: Python analysis and charts
- `Airbnb_Data_Exploration_Using_SQLite_&_Pandas_Dataframe.ipynb`: SQL queries with SQLite
- `AB_NYC_2019.csv`: dataset

## Summary
This project explores NYC Airbnb data using Python and SQL, combining summary statistics and visuals to show how location and room type shape prices and how the market is spread across the city.

*## Acknowledgements
Learned the workflow through a guided course; analysis and write-up done by me.*
