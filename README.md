# Zomato-Sql-Analysis
Exploring the Zomato dataset via SQL revealed India as the primary market with 90.67% of listings, followed by the USA at 4.45%. Insights showed limited online delivery options, with 28.01% of Indian and 46.67% of UAE restaurants offering this service. Connaught Place in New Delhi stood out with 122 restaurants .Connaught Place in New Delhi stood out with 122 restaurants, mostly featuring North Indian cuisine, underscoring regional dining preferences and operational nuances.

Data Preparation and Structure Review:

Meticulously reviewed Zomato dataset's table structure.
Verified data integrity, focusing on duplicates in the RestaurantId column.
Streamlined dataset by removing unnecessary columns.
Data Integration and Enrichment:

Utilized SQL capabilities to merge disparate tables.
Introduced a new dimension with Country_Name linked via primary key, CountryCode.
Regional Insights:

Discovered India dominates the dataset with 90.67% of restaurant listings, followed by the USA at 4.45%.
Highlighted disparities in online delivery availability: 28.01% in India and 46.67% in UAE offer this service.
Local Analysis - Connaught Place, New Delhi:

Identified Connaught Place as having the highest restaurant listings.
Noted North Indian cuisine's dominance in this area.
Facilities Impact on Ratings:

Analyzed the impact of table booking on restaurant ratings:
Restaurants with table booking averaged 3.9/5, while those without averaged 3.7/5.
Case Study - 'India Restaurant' in Kolkata:

Explored Kolkata for top moderately priced dining under ₹1000.
Highlighted 'India Restaurant' (RestaurantID - 20747) for its exceptional ratings (>4), significant votes, and comprehensive amenities (table booking, online delivery).
Operational Insights:

Uncovered nuanced customer preferences and operational dynamics influencing service offerings and regional dining trends within Zomato's business landscape.
