# Zillow Real Estate Investment Recommender

BY: TaeJoon Kim

PURPOSE: This notebook aims to suggest potential locations for investing in U.S. real estate, based on historical data on the average housing prices. 

BUSINESS PROBLEM: The clients utilizing this notebook are people who intend to buy houses purely for investment purposes and not for residence. For this reason, in-depth considerations for each region and neighborhood are not included - only monthly price movements will be considered. 

DATA: Data used in this notebook contains the average monthly house prices from April 1996 to April 2018 (22 year span), organized by zipcode.
The dataframe contains 14722 rows and 272 columns.
This data can be accessed on the Zillow website (https://www.zillow.com/research/data/).

DATA SELECTION: Selection of the top 5 zipcodes to invest was carried out by weighing four factors:
- Size Rank (20%)
- Price Range (20%)
- Coefficient of Variance (60%)
- Return on Investment

The top five zipcodes that were selected were: 11211,	11222,	11216,	07302, and	11215.
All five zipcodes were areas within the New York City Metropolitan Area.

Train RMSE: 0.00375
Test RMSE: 0.00573
