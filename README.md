# Measuring-Neighborhood-Availability-of-Alcohol
Measuring neighborhood alcohol availability in Fayette County using Python, Census API, geocoding, and data visualization.

📊 Project Overview
This project analyzes liquor license availability across neighborhoods in Fayette County, KY, by linking ABC liquor license data with U.S. Census tract population data. The goal is to identify patterns in alcohol availability relative to population size and highlight neighborhoods with the highest license concentration.

📂 Dataset
Liquor License Data: Kentucky Department of Alcoholic Beverage Control (ABC) — Fayette County Active Licenses.
Population Data: U.S. Census Bureau — 2020 American Community Survey (ACS 5-year) at Census Tract level.
Geocoding Data: U.S. Census Geocoder API for mapping addresses to tracts.

⚙️ Methodology
Data Import & Cleaning
Loaded raw CSV from ABC portal.
Standardized address fields (removed punctuation, whitespace, etc.).
Population Data Extraction
Pulled tract-level population data from Census API.
Geocoding
Mapped each business address to a Census tract using the U.S. Census Geocoder API.
Merging & Rate Calculation
Joined license and population data by tract.
Calculated licenses per 1,000 residents for each tract.
Analysis & Visualization
Identified Top 20 tracts by rate and Top 20 by count.
Visualized patterns using horizontal bar charts and scatter plots.

📈 Key Findings
Some tracts with high license rates are not the same as those with the highest total number of licenses, highlighting the importance of population adjustment.
A few neighborhoods have exceptionally high rates, suggesting dense clusters of licensed businesses relative to their population size.
Scatter plots show no strict linear relationship between total license count and per-capita rate, indicating diverse neighborhood patterns.

📝 Conclusions
Analyzing alcohol availability by both raw count and population-adjusted rate gives a more complete picture of neighborhood-level alcohol access. These insights could support local planning, health research, and policy decisions regarding alcohol licensing and zoning.

🚀 Future Work
Create interactive maps using GeoPandas or Folium to visualize spatial distribution.
Automate the geocoding pipeline for all addresses (beyond the sample subset).
Incorporate demographic and socioeconomic variables to explore deeper correlations.

📬 Contact
Madhav Dahal
📍 Lexington, KY
✉️ madhavdahal16@gmail.com
