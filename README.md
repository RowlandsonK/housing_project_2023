# Housing Project 2023

## Overview
The main focus of this project is a person who wants to buy a house in King County, Washington. The plan is to live in the house for a few years and then sell it for a profit. The buyer has a modest income, plans to buy a home for less than $1 million, and has set aside money for any fixes that might be needed. For the project, data will be analyzed and models will be made based on house sales in the area. This will help us figure out how different factors affect each other. Linear regression is used to predict house prices and figure out how different things affect them.

## Business Problem
- What are the effects of living in different parts of King County?
- Where should one allocate funds for repairs?
- How does the size of a house's living space correlate with its purchase price?

## Data
- The data for this project is sourced from the kc_house_data.csv file on Kaggle.com.
- It comprises 21,597 records of homes sold in King County, Washington, between 2014 and 2015.
- Key features include living space in square feet, the number of bedrooms, and a grade based on construction quality.
- The target variable is the "price" column.

## Methods
- Data cleaning involved removing duplicates, handling extreme outliers, imputing missing values, and ensuring correct data types.
- Categorical variables were transformed into indicator columns.
- Some variables, such as months and bedrooms, were binned to reduce feature dimensionality.
- Various models were developed, with Model 4 meeting all four assumptions of linear regression.

## Results
- Model 4 provides valuable insights into factors affecting house prices.
- Improved construction quality is associated with higher prices, with Grade_High_Quality and Grade_Above_Average houses seeing price increases of $254K and $97K, respectively.
- Home condition positively influences price, with the best condition adding about $161K compared to the worst condition.
- The relationship between the number of bedrooms and price warrants further investigation.

## Conclusions
- Sections 1 and 2 have the most positive effect on price, likely indicating specific areas in King County.
- Investing in high-quality construction and building materials can boost property value.
- Further analysis and anomaly detection are necessary to understand the bedroom-price relationship.

## What's Next?
- Explore geographic libraries to create features based on location, such as proximity to schools or public places.
- Consider incorporating additional datasets with information about nearby jobs, public transportation, and other relevant factors.

