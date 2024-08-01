Source: The dataset was originally collected using a free web-scraping tool called Apify from Zillow.com and stored on Kaggle in January 2021.
Format: CSV file
Description:
The dataset contains 15,171 records with 47 features (13 categorical and 34 numerical) describing housing listings in Austin, Texas. Key features include:

Price
Location (latitude, longitude, zipcode)
Property characteristics (number of bedrooms, bathrooms, square footage, etc.)
School information
Various amenities and features of the property

Preprocessing steps:

Removal of duplicates and null values
Outlier detection and removal using manual thresholds, z-scores, and IQR method
Conversion of Boolean features to binary (0/1) values
Feature engineering (e.g., distance from city center, zipcode classification)
Normalization of numerical features

Note: After preprocessing, the dataset was reduced to 8,569 records.
