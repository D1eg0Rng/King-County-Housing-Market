# King County Housing Market Recommendations

## Members

**Project members:** 
Srinivasan Ramakrishnan & Diego Rangel

## Overview
Main topics of the project:

1. Business Problem
2. Data Understanding
3. First Model
4. Data Preparation
5. Final Model
6. Recommendations
7. Next Steps

## Business Problem

A Real Estate Agency is currently facing a business problem of losing potential clients due to overpriced properties.

They want to hire us to create a model that can predict house prices based on certain characteristics of the houses, so they can more accurately price properties and increase their chances of making a sale. Additionally, the agency can identify undervalued properties that they could purchase and resell for profit.

## Data

The initial data contained 30156 houses with the following information

**Column Names and descriptions for Kings County Data Set:**

- id - a unique identifier for each house.<br />
- date - the date the house was sold.<br />
- price - the price of the house.   **(TARGET)**<br />
- bedrooms - the number of bedrooms in the house.<br />
- bathrooms - the number of bathrooms in the house.<br />
- sqft_living - the total square footage of the living space in the house.<br />
- sqft_lot - the total square footage of the lot the house sits on.<br />
- floors - the number of floors in the house.<br />
- waterfront - a binary variable indicating whether the house has a waterfront view.<br />
- greenbelt - a binary variable indicating whether the house is located near a greenbelt.<br />
- nuisance - a binary variable indicating whether the house is located near a nuisance, such as a busy road or airport.<br />
- view - a rating of the view from the house, on a scale of 0 to 4.<br />
- condition - a rating of the overall condition of the house, on a scale of 1 to 5.<br />
- grade - a rating of the construction quality and design of the house, on a scale of 1 to 13.<br />
- heat_source - the primary source of heat for the house.<br />
- sewer_system - the type of sewer system used by the house.<br />
- sqft_above - the square footage of the living space above ground level.<br />
- sqft_basement - the square footage of the basement.<br />
- sqft_garage - the square footage of the garage.<br />
- sqft_patio - the square footage of the patio or deck.<br />
- yr_built - the year the house was built.<br />
- yr_renovated - the year the house was last renovated, or 0 if the house has never been renovated.<br />
- address - the street address of the house.<br />
- lat - the latitude of the house's location.<br />
- long - the longitude of the house's location.<br />


**Kings Country GIS Data** (https://gis-kingcounty.opendata.arcgis.com) **(3600 rows**

Contained Latitude and Longitude of:

- Airports
- Cemeteries
- Commercial Farms
- Places of Culture
- Places of Education
- Fire / Police Station
- Gated Residential Areas
- Public Gathering Spaces
- Utilities

**King County Open Data** (https://data.kingcounty.gov/)

The data contained 20450 crimes with the following information

- case_number - a unique identifier for each incident report.<br />
- incident_datetime - the date and time the incident occurred.<br />
- incident_type - the type of incident that occurred, such as theft, assault, or vandalism.<br />
- FCR - the final classification of the incident, determined after investigation and analysis.<br />
- address_1 - the street address of the incident location.<br />
- city - the city where the incident occurred.<br />
- state - the state where the incident occurred.<br />
- zip - the postal code of the incident location.<br />
- created_at - the date and time the incident report was created.<br />
- updated_at - the date and time the incident report was last updated.<br />
- hour_of_day - the hour of the day the incident occurred.<br />
- day_of_week - the day of the week the incident occurred.<br />
- Incident Block Location - the block location where the incident occurred, typically with the street number and block range of the address.<br />

## First Model

![image](https://user-images.githubusercontent.com/122308669/219785757-b9663707-4313-44b3-8ea0-25b3b74d35af.png)

- 40% of variability in price can be explained by the model’s variables.
- Model prediction off by $698,310.

**First model cleaning:**
- Dropping null values.
- Deleting duplicates.

## Data/Model Preparation


![image](https://user-images.githubusercontent.com/122308669/219785158-59fb7799-126b-44c7-9c3b-c2ebd9fd0200.png)


![image](https://user-images.githubusercontent.com/122308669/219785497-ca6b3025-3498-4469-8871-b3adeb6345ec.png)


## Final Model

![image](https://user-images.githubusercontent.com/122308669/219785691-80dfa21b-a347-41fe-9c62-68c0ac50466c.png)

- 70% of variability in price can be explained by the model’s variables.
- Model prediction off by $222,155.

**Coefficients:**
- Sqft_living = 88.71
- Grade = 83,944.19
- Min Dist to Gated Building = 2,187,461
- Total_sqft = 43.91
- Sqft_lot = -43.64
- Sqft_basement = -40.49




## Recommendations and Next Steps


![image](https://user-images.githubusercontent.com/122308669/219786329-8d1f94b0-e785-4c23-a589-169591a5d657.png)


![image](https://user-images.githubusercontent.com/122308669/219786456-074cb17e-3260-4125-80fc-e733248333c7.png)


## Linkedin:

	Srinivasan: https://www.linkedin.com/in/srinivasanr1/

	Diego: https://www.linkedin.com/in/diego-rangel-35953a22b














