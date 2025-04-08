# Capital Insights: Unveiling Airbnb Dynamics in Ottawa

## Table of Contents
- [Project Overview](#project-overview)
- [Inspiration](#inspiration)
- [Dataset Description](#dataset-description)
- [Business Benefits](#business-benefits)
- [Key Findings](#key-findings)
- [Visualizations](#visualizations)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [Limitations](#limitations)
- [References](#references)

## Project Overview
This project provides an in-depth analysis of the Airbnb market in Ottawa, Ontario, utilizing Airbnb's publicly available dataset. The goal is to uncover trends, host activities, and pricing strategies within the local short-term rental market. Tableau was employed to create interactive visualizations that effectively communicate the insights derived.

## Inspiration
The analysis was driven by several key questions:
- What can we learn about different hosts and areas?
- What insights can predictions provide (e.g., locations, prices, reviews)?
- Which hosts are the busiest and why?
- Is there any noticeable difference in traffic among different areas, and what could be the reason?

## Dataset Description
The dataset comprises approximately 103,127 listings across 40 neighborhoods, with 41 columns representing a mix of categorical and numeric values. Key columns include:
- `listing_id`: Unique ID of the property
- `listing_name`: Name of the listed property
- `host_id`: ID of the property owner
- `host_name`: Name of the property owner
- `listing_neighbourhood`: Specific location of the property
- `neighbourhood`: General area where the property is located
- `latitude` & `longitude`: Geographical coordinates
- `room_type`: Type of room offered
- `price_per_night`: Listing price in dollars
- `number_of_reviews`: Total number of reviews
- `last_review`: Date of the last review
- `reviews_per_month`: Average number of reviews per month

The dataset used in this analysis was sourced from [Inside Airbnb](http://insideairbnb.com/get-the-data.html), specifically the data for Ottawa, Ontario, Canada.

## Business Benefits
The analysis provides valuable insights for customers planning their travels, such as:
- Estimating accommodation expenses
- Choosing the preferred room type in a specific area
- Identifying the most popular Airbnb properties based on reviews

This information can help increase tourism, enhance the company's reputation, and contribute to revenue growth.

## Key Findings
- **Maximum Listings**: The neighborhood with the most properties listed is Rideau-Vanier.
- **Top Host**: The host with the most listings is "Short And Suite" with 47 listings.
- **Busiest Host**: The busiest host, based on the number of properties and reviews, is "Sonder".
- **Preferred Room Type**: The most preferred room type across neighborhoods is "Entire home/Apartment".
- **Pricing Insights**: The average price for different properties and reasons for higher prices in certain areas are discussed.
- **Availability**: The total availability of properties with different room types is analyzed.

## Visualizations
The project includes a series of Tableau visualizations that address the following questions:
- In which neighborhood is there the maximum number of properties listed?
- Which host has the maximum number of properties listed?
- What is the average price in different properties listed?
- What is the most preferred room type in every neighborhood?
- Which property has the maximum number of reviews?

Access the interactive dashboard here: [Tableau Dashboard](https://public.tableau.com/app/profile/sarthak.oke/viz/AirBnBTableauDataAnalysisOttawa/Dashboard1)

## Conclusion
The analysis sheds light on the dynamics of the Airbnb market in Ottawa, providing a resource for potential customers and contributing to the broader understanding of the sharing economy in the region.

## Future Work
Potential areas for further analysis include:
- Examining seasonal trends in bookings and pricing
- Analyzing the impact of major events on Airbnb demand
- Exploring customer satisfaction through sentiment analysis of reviews

## Limitations
While the analysis provides valuable insights, certain limitations should be acknowledged:
- The dataset may not capture all Airbnb listings, leading to potential sampling bias.
- Data accuracy depends on hosts' self-reported information, which may not always be reliable.
- The analysis does not account for external factors such as local regulations or economic conditions that may influence the Airbnb market.

## References
- [Airbnb Open Data](http://insideairbnb.com/get-the-data.html)
- [Tableau Public](https://public.tableau.com/)
