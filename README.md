# Measuring-Neighborhood-Availability-of-Alcohol
Measuring neighborhood alcohol availability in Fayette County using Python, Census API, geocoding, and data visualization.

📝 Project Overview
This project analyzes the availability of liquor licenses across neighborhoods in Fayette County, Kentucky, by combining data from the Kentucky Department of Alcoholic Beverage Control (ABC) and the U.S. Census Bureau’s American Community Survey (ACS).
The analysis involves:
Cleaning and standardizing raw license address data
Geocoding addresses to Census tracts using the U.S. Census Geocoder API
Merging with population data from the 2020 ACS
Calculating liquor license rates per 1,000 residents for each neighborhood
Identifying the top 20 tracts by rate and count, and visualizing patterns

🧰 Technologies & Tools Used
Python (pandas, matplotlib, re, requests)
U.S. Census API (ACS 2020)
Census Geocoder API
Google Colab for notebook development
Matplotlib for data visualization

📈 Key Visualizations
Top 20 Neighborhoods by Alcohol Availability Rate (per 1,000 residents)
Top 20 Neighborhoods by License Count
Scatter Plot: License Count vs. Rate across all tracts

💡 Key Insights
Neighborhoods with high license rates are not always those with the highest total number of licenses.
Comparing rate vs. count provides a two-dimensional view: population-adjusted intensity vs. absolute volume.
Geocoding plays a crucial role in mapping addresses to Census geography for meaningful population-based analysis.

