## Team MEAT

Sources:

- renewable-water-resources-per-capita.csv & municipal-water-as-a-share-of-total-water-withdrawals.csv & industrial-water-as-a-share-of-total-water-withdrawals.csv & agricultural-water-as-a-share-of-total-water-withdrawals.csv, from https://ourworldindata.org/water-use-stress, collected on Thursday, March 14, 2024.

- state-capacity-index.csv, from https://ourworldindata.org/state-capacity?insight=many-states-have-increased-their-capacities-in-recent-decades#key-insights, collected on Thursday, March 14, 2024.

- share-of-population-urban.csv, from https://ourworldindata.org/urbanization, collected on Thursday, March 14, 2024.

- FAOSTAT_meat_production_by_country_by_year.csv, from https://www.fao.org/faostat/en/#data/QCL, collected on Thursday, March 14, 2024.


Variable Definitions:

`country` = most well known name of the country

`code` = country code

`year` = recorded year of data

`stress` = "defined in its simplest terms as occurring when total freshwater withdrawal substantiates a large share of available renewable freshwater resources.

UN-Water defines water stress categories based on this percentage (% of withdrawals to renewable resources) as follows:

<25% = no stress
25-50% = low stress
50-75% = medium stress
75-100% = high stress
>100% = critical stress"  -Our World in Data (source)

`% agriculture water` = "Annual quantity of self-supplied water withdrawn for irrigation, livestock and aquaculture purposes. It can include water from primary renewable and secondary freshwater resources, as well as water from over-abstraction of renewable groundwater or withdrawal from fossil groundwater, direct use of agricultural drainage water, direct use of (treated) wastewater, and desalinated water. Water for the dairy and meat industries and industrial processing of harvested agricultural products is included under industrial water withdrawal." [represented as a percentage of total freshwater withdrawals]  -UN Food and Agricultural Organization (FAO) AQUASTAT Database

`% industry water` = "Annual quantity of self-supplied water withdrawn for industrial uses. It can include water from primary renewable and secondary freshwater resources, as well as water from over-abstraction of renewable groundwater or withdrawal from fossil groundwater, direct use of agricultural drainage water, direct use of (treated) wastewater, and desalinated water. This sector refers to self-supplied industries not connected to the public distribution network. The ratio between net consumption and withdrawal is estimated at less than 5%. It includes water for the cooling of thermoelectric and nuclear power plants, but it does not include hydropower. Water withdrawn by industries that are connected to the public supply network is generally included in municipal water withdrawal." [represented as a percentage of total freshwater withdrawals]  -UN Food and Agricultural Organization (FAO) AQUASTAT Database

`% domestic water` = "Annual quantity of water withdrawn primarily for the direct use by the population. It can include water from primary renewable and secondary freshwater resources, as well as water from over-abstraction of renewable groundwater or withdrawal from fossil groundwater, direct use of agricultural drainage water, direct use of (treated) wastewater, and desalinated water. It is usually computed as the total water withdrawn by the public distribution network. It can include part of the industries and urban agriculture, which is connected to the municipal network. The ratio between the net consumption and the water withdrawn can vary from 5 to 15% in urban areas and 10 to 50% in rural areas." [represented as a percentage of total freshwater withdrawals]  -UN Food and Agricultural Organization (FAO) AQUASTAT Database

`water per capita` = amount of internal freshwater resources in cubic meters per capita.

`% urban population` = "Share of population living in urban areas."  -Our World in Data (source)

`state capacity` = "The index aggregates 21 indicators, such as how much countries can control their territory, raise sustainable resources, and hire skilled and impartial security forces and public servants...The index captures the extent to which the state controls its territory, sustainably raises sufficient resources, and has
skilled and impartial security forces and public servants. Higher scores mean more capacity."  -Our World in Data (source)

`cattle` = total cow production in number of cows.

`Annual freshwater withdrawals, total (billion cubic meters)` = Annual freshwater withdrawals refer to total water withdrawals, not counting evaporation losses from storage basins. Withdrawals also include water from desalination plants in countries where they are a significant source. Withdrawals can exceed 100 percent of total renewable resources where extraction from nonrenewable aquifers or desalination plants is considerable or where there is significant water reuse. Withdrawals for agriculture and industry are total withdrawals for irrigation and livestock production and for direct industrial use (including withdrawals for cooling thermoelectric plants). Withdrawals for domestic uses include drinking water, municipal use or supply, and use for public services, commercial establishments, and homes. Data are for the most recent year available for 1987-2002.

`Cereal yield (kg per hectare)` = Cereal yield, measured as kilograms per hectare of harvested land, includes wheat, rice, maize, barley, oats, rye, millet, sorghum, buckwheat, and mixed grains. Production data on cereals relate to crops harvested for dry grain only. Cereal crops harvested for hay or harvested green for food, feed, or silage and those used for grazing are excluded.

`Control of Corruption: Estimate` = Control of Corruption captures perceptions of the extent to which public power is exercised for private gain, including both petty and grand forms of corruption, as well as "capture" of the state by elites and private interests. Estimate gives the country's score on the aggregate indicator, in units of a standard normal distribution, i.e. ranging from approximately -2.5 to 2.5.

`Electricity production from hydroelectric sources (% of total)` = Sources of electricity refer to the inputs used to generate electricity. Hydropower refers to electricity produced by hydroelectric power plants.

`Permanent cropland (% of land area)` = Permanent cropland is land cultivated with crops that occupy the land for long periods and need not be replanted after each harvest, such as cocoa, coffee, and rubber. This category includes land under flowering shrubs, fruit trees, nut trees, and vines, but excludes land under trees grown for wood or timber.

`Population density (people per sq. km of land area)` = Population density is midyear population divided by land area in square kilometers. Population is based on the de facto definition of population, which counts all residents regardless of legal status or citizenship--except for refugees not permanently settled in the country of asylum, who are generally considered part of the population of their country of origin. Land area is a country's total area, excluding area under inland water bodies, national claims to continental shelf, and exclusive economic zones. In most cases the definition of inland water bodies includes major rivers and lakes.
