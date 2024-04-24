## Team MEAT

## Overview:

2.4 billion people live in countries with high levels of water stress. Inadequate access to clean water reduces levels of sanitation, exacerbating the spread of disease. Agriculture also becomes more difficult to maintain in water-stressed areas, causing malnutrition and hunger. People in water-stressed areas often have to travel far or wait long to acquire drinking water. This reduces the amount of time available to pursue higher goals like education, thereby stunting the community's development. 

## Goals: 

The goal of this analysis is to understand the factors that affect water stress in order to combat this growing issue.* 

## Variable Definitions:

`country` = Most well known name of the country.

`code` = Country code.

`year` = Recorded year of data.

`stress` = Freshwater use as a proportion of available internal freshwater resources (%).

`agriculture_water` = Percentage of freshwater withdrawals for agricultural purposes.

`industry_water` = Percentage of freshwater withdrawals for industrial purposes.

`domestic_water` = Percentage of freshwater withdrawals for municipal and domestic purposes.

`water_per_capita` = Amount of internal freshwater resources in cubic meters per capita.

`urban_population` = Share of population living in urban areas.

`state_capacity` = "The index aggregates 21 indicators, such as how much countries can control their territory, raise sustainable resources, and hire skilled and impartial security forces and public servants...The index captures the extent to which the state controls its territory, sustainably raises sufficient resources, and has
skilled and impartial security forces and public servants. Higher scores mean more capacity."  -Our World in Data (source)

`cattle` = Total cow production in number of cows.

`total_withdrawals` = Total freshwater withdrawals in cubic meters.

`cereal_yield` = Cereal yield, measured as kilograms per hectare of harvested land.

`control_of_corruption` = Level of corruption estimate.

`hydro_electricity` = Percent of total electricity production from hydroelectric sources.

`permanent_cropland` = Permanent cropland is land cultivated with crops that occupy the land for long periods and need not be replanted after each harvest.

`population_density` = Population density is midyear population divided by land area in square kilometers.

## Conclusions:

## Resources:

- renewable-water-resources-per-capita.csv & municipal-water-as-a-share-of-total-water-withdrawals.csv & industrial-water-as-a-share-of-total-water-withdrawals.csv & agricultural-water-as-a-share-of-total-water-withdrawals.csv, from https://ourworldindata.org/water-use-stress, collected on Thursday, March 14, 2024.

- state-capacity-index.csv, from https://ourworldindata.org/state-capacity?insight=many-states-have-increased-their-capacities-in-recent-decades#key-insights, collected on Thursday, March 14, 2024.

- share-of-population-urban.csv, from https://ourworldindata.org/urbanization, collected on Thursday, March 14, 2024.

- FAOSTAT_meat_production_by_country_by_year.csv, from https://www.fao.org/faostat/en/#data/QCL, collected on Thursday, March 14, 2024.
  
# *Packages used:*

- pandas
- numpy
- seaborn
- matplotlib
- math
- itertools
- scikit.learn
- statsmodels
