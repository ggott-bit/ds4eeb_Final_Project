# newdf README

This is the folder where we put the combined dataframes. These dataframes were created in Final_Presentation_Gabriel.qmd, and there are little blurbs explainin what they are.

combined_sitespecific_climind_temp.csv is SBH_temperature_20241231.csv and climind_quarterly.csv merged together.

combines_kelp_climind_data.csv is climind_quarterly.csv and kelp_no3_waves_quarterly_long.csv merged together.

## Metadata

Combined data with temperature

| Column Name (combined_sitespecific_climind_temp.csv) | Unit | Type | Description |
|----|----|----|----|
| site_id | Arbitrary numbering | numeric | An id which designates a 500m long stretch of the Californian coast. |
| year | Year | numeric | Year of measurement. |
| quarter | Quarter | numeric | Quarter of measurement. |
| kelp | Kilograms | numeric | Kelp biomass estimated from remotely sensed data and empirical relationships. |
| no3 | Concentration in micro-moles per liter | numeric | Seawater nitrate concentration estimated from empirical relationships with remotely sensed sea surface temperature. |
| waves | Average wave height in meters | numeric | Wave height estimated from swell propagation model. |
| NPGO | Standard deviations | numeric | See NPGO in explaining terms. |
| MEI | MEI.v2 | numeric | See MEI in explaining terms. |
| PDO | Degree offset | numeric | See PDO in explaining terms. |
| mean_surf_temp | Temperature (Celsius) | numeric | The mean sea surface temperature. |

Combined data without temperature

| Column Name (combined_kelp_climind_data.csv) | Unit | Type | Description |
|----|----|----|----|
| site_id | Arbitrary numbering | numeric | An id which designates a 500m long stretch of the Californian coast. |
| year | Year | numeric | Year of measurement. |
| quarter | Quarter | numeric | Quarter of measurement. |
| kelp | Kilograms | numeric | Kelp biomass estimated from remotely sensed data and empirical relationships. |
| no3 | Concentration in micro-moles per liter | numeric | Seawater nitrate concentration estimated from empirical relationships with remotely sensed sea surface temperature. |
| waves | Average wave height in meters | numeric | Wave height estimated from swell propagation model. |
| NPGO | Standard deviations | numeric | See NPGO in explaining terms. |
| MEI | MEI.v2 | numeric | See MEI in explaining terms. |
| PDO | Degree offset | numeric | See PDO in explaining terms. |

### Explaining Terms

Some terms that may not have been obvious as to what they are, were the NPGO, MEI, and PDO that were measured in climind_annual.csv, and climind_quarterly.csv. Here is an explanation as to what they are.

**Multivariate El Nino Southern Oscillation Index (MEI):**

An index used to characterize the intensity of an El Nino event, with high positive values indicating a warming event, and high negative values indicating a cooling event. 

**Pacific Decadal Oscillation (PDO):**

A recurring pattern of water surface temperatures in the Pacific ocean north of 20°N changing between warmer and cooler temperatures every few decades. With positive values indicating a warming event, and negative values indicating a cooling event.\
\
**North Pacific Gyre Oscillation (NPGO):**\
A recurring phase of upwelling, in the form of counter rotating gyres, along 40°N in the Pacific. When the NPGO is positive, upwelling-favorable conditions are seen in the California Current and Alaskan Gyre, while downwelling-favorable conditions are seen in the Subtropical Gyre and the Alaskan Coastal Current.
