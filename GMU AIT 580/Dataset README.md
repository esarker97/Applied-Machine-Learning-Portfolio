Source: The dataset was originally collected using a free web-scraping tool called Apify from Zillow.com and was stored on Kaggle in January 2021.

Format: CSV file

Description: The dataset contains 15,171 records with 47 features, including 13 categorical and 34 numerical attributes, that describe housing listings in Austin, Texas. Key features include price, location (latitude, longitude, zipcode), property characteristics (such as the number of bedrooms, bathrooms, and square footage), school information, and various amenities and features of the property.

Preprocessing Steps: The preprocessing involved the removal of duplicates and null values, outlier detection and removal using manual thresholds, z-scores, and the IQR method, conversion of Boolean features to binary (0/1) values, feature engineering (e.g., calculating distance from the city center and classifying zipcodes), and normalization of numerical features.

Note: After preprocessing, the dataset was reduced to 8,569 records.
