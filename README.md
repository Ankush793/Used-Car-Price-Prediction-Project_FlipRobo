# Used Car Price Prediction Project

# Project Overview

Scraped 6224 used cars data from Carsdekho.com website using Python and Selenium.
Cleaned the data and built a model to help determine the price of cars on auction
Built a flask web app and deploy to cloud
# Packages/Tools Used
Python Version: 3.9
Selenium
Request
Numpy
Matplotlib
Seaborn
Scikit-Learn
# Data
The data was scraped from carsdekho.com site. The data was scraped from multiple pages from the site and was stored as a excel file. The scraped data contains:

Model
Price
Year
Mileage
Engine
Transmisson
Location
Driven Kilometers

# Data Cleaning
The features (columns) contained messy entries and were tidied using some custom functions. The following steps were taken.

- Removed the duplicate rows in the data because it will affect the analysis.
- Deleted thhe rows with missing values because they ae not up to 1% of the data.
- Extracted the manufaturer of each car from the Model column
- Corrected some of the values in the manufacturers column by merging similar value and correcting those wrongly extracted.
- Removed the pounds symbol and the comma in the values of the price column
- Removed the commas, space and miles input in all the values of the mileage columns.
- Corrected some of the values in the engine and transmission columns by merging similar value and correcting those wrongly extracted.
