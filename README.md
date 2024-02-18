# NYC Airbnb Data Analysis

## Overview
This project analyzes Airbnb data for listings in New York City (NYC). The goal is to gain insights into the NYC Airbnb market, including average prices, room types, borough-wise price comparisons, and more.

## Datasets
The project uses three datasets:
- `airbnb_price.csv`: Contains information about listing prices, including listing ID, price, and neighborhood.
- `airbnb_room_type.xlsx`: Contains information about room types for listings, including listing ID, description, and room type.
- `airbnb_last_review.tsv`: Contains information about the last review for each listing, including listing ID, host name, and last review date.

## Analysis Steps
1. **Cleaning the Price Column**: Convert the price column to a numeric datatype and remove any non-numeric characters.
2. **Calculating Average Price**: Calculate the average price per night for an Airbnb listing in NYC.
3. **Comparing Costs to the Private Rental Market**: Convert per-night prices to monthly costs and compare them to the average cost of renting a 1-bedroom apartment in NYC.
4. **Cleaning the Room Type Column**: Convert room types to lowercase and update the column to the category data type.
5. **Analyzing Listing Prices by NYC Borough**: Extract borough information from the neighborhood column and calculate summary statistics for listing prices by borough.
6. **Price Range by Borough**: Categorize listings based on price ranges and analyze the frequency of listings in each price range by borough.

## Visualization
The project includes visualizations such as bar charts to illustrate the distribution of listings by price range and borough-wise comparison of listing prices.

## Conclusion
The analysis provides valuable insights into the NYC Airbnb market, including pricing trends, room types, and borough-wise differences. These insights can be useful for both hosts and guests in making informed decisions regarding Airbnb listings in NYC.

## Requirements
- Python 3
- pandas
- numpy
- matplotlib

## Author
John Doe

