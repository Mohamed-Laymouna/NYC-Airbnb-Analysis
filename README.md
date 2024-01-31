# Airbnb Market Analysis in New York City

This Jupyter Notebook contains an analysis of the Airbnb market in New York City. The notebook explores multiple datasets related to Airbnb listings, including pricing, room types, and reviews. The goal of this analysis is to uncover insights and trends in the Airbnb market in NYC.

## Getting Started

To run this notebook, you will need the following:

- Jupyter Notebook installed on your machine
- Python 3.x
- Required Python libraries: pandas, numpy, matplotlib, seaborn

## Dataset

The analysis is based on the following datasets:

1. "datasets/airbnb_price.csv": Contains information about the prices of Airbnb listings.
2. "datasets/airbnb_room_type.xlsx": Provides details about the room types available in Airbnb listings.
3. "datasets/airbnb_last_review.tsv": Contains information about the last reviews for Airbnb listings.

## Analysis Steps

The notebook follows the following steps:

1. Importing and preparing the datasets: The datasets are imported and combined into a single dataset using pandas merge function.
2. Data cleaning: The dataset is cleaned by converting data types, removing unnecessary columns, and handling missing values.
3. Data analysis: Various analyses are performed, including calculating average daily and monthly costs, exploring room types, and examining the distribution of last reviews.
4. Conclusion: The findings and insights from the analysis are summarized.

## Results

The analysis reveals several key findings:

- The average price per night for Airbnb in NYC is $169.44, while the average price per month is $4,072.67.
- Manhattan has the highest average price per month ($5,103.41), while the Bronx has the lowest ($2,481.34).
- The most common room type in NYC Airbnb listings is "Entire home/apt".
- The average daily price for "Entire home/apt" is $183, for "Private room" is $80, and for "Shared room" is $50.
- The most common month for Airbnb listings is June, with 12,378 listings.

## Conclusion

This analysis provides valuable insights into the Airbnb market in New York City. The findings can be used by stakeholders, such as hosts and travelers, to make informed decisions about pricing, room types, and booking trends in the NYC Airbnb market.

For more details, please refer to the Jupyter Notebook file in this repository.
