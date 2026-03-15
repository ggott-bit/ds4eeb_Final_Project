# Raw Data

This is a folder where we keep all of our raw data sets before we have modified them.

Here are the sources for all of the data that we used:

### Source 1:

Santa Barbara Coastal LTER, Tom W Bell, Kyle C Cavanaugh, Daniel Reuman, Max C. N. Castorani, Lawrence Sheppard, & Jonathan Walter. (2021). *SBC LTER: REEF: Macrocystis pyrifera biomass and environmental drivers in southern and central California*. LTER Network Member Node. <https://pasta.lternet.edu/package/metadata/eml/knb-lter-sbc/144/1>.

### Source 2:

Washburn, L. 2025. SBC LTER: Reference: Sea-surface water temperature, Santa Barbara Harbor, Santa Barbara, CA, USA, 1955 to present, ongoing ver 17. Environmental Data Initiative. <https://doi.org/10.6073/pasta/8020223a1e2ed16411f0c18b61fbc3fb>.

### The Files

climind_annual.csv was downloaded from Source 1, and conains the NPGO, MEI, and PDO values for each year from 1987 - 2019.

climind_quarterly.csv is a quarterly data set that measures the same variables as climind_annual.csv, meaning that it has 4 times as many data points as the annual data set.

kelp_no3_waves_annual_long.csv was downloaded from Source 1, and contains measurements for the annual kelp biomass in kilograms, seawater nitrate concentration in micro-moles per liter, and wave height in meters at each of 361 half kilometer long segments of beach measured.

kelp_no3_waves_quarterly_long.csv is a quarterly data set that measures the same variables as kelp_no3_waves_annual_long.csv, meaning that it has 4 times as many data points as the annual data set.

locations.csv was downloaded from Source 1, and specifies the latitude and longitude of each of the 361 measurement sites.

SBH_temperature_20241231.csv was downloaded from Source 2, and contains measurements for the daily surface temperature in degrees Celsius of the water in the Santa Barbara harbor between 1955 and 2024.

## Metadata

Annual climate

| Column Name (climind_annual.csv) | Unit | Type | Description |
|----|----|----|----|
| year | Year | numeric | Year of measurement. |
| NPGO | NPGO Index | numeric | See NPGO in explaining terms. |
| MEI | MEI.v2 Index | numeric | See MEI in explaining terms. |
| PDO | PDO Index | numeric | See PDO in explaining terms. |

Quarterly climate

| Column Name (climind_quarterly.csv) | Unit | Type | Description |
|----|----|----|----|
| year | Year | numeric | Year of measurement. |
| quarter | Quarter | numeric | Quarter of measurement. (Q1 = Jan – Mar, Q2 = Apr – Jun, Q3 = Jul – Sep, Q4 = Oct – Dec) |
| NPGO | NPGO Index | numeric | See NPGO in explaining terms. |
| MEI | MEI.v2 Index | numeric | See MEI in explaining terms. |
| PDO | PDO Index | numeric | See PDO in explaining terms. |

Kelp, NO3, Waves long form annual

| Column Name (kelp_no3_waves_annual_long.csv) | Unit | Type | Description |
|------------------|------------------|------------------|------------------|
| site_id | Arbitrary numbering | numeric | An id which designates a 500m long stretch of the Californian coast. |
| year | Year | numeric | Year of measurement. |
| kelp | Kilograms | numeric | Kelp biomass estimated from remotely sensed data and empirical relationships. |
| no3 | Concentration in micro-moles per liter | numeric | Seawater nitrate concentration estimated from empirical relationships with remotely sensed sea surface temperature. |
| waves | Average wave height in meters | numeric | Wave height estimated from swell propagation model. |

Kelp, NO3, Waves long form quarterly

| Column Name (kelp_no3_waves_quarterly_long.csv) | Unit | Type | Description |
|------------------|------------------|------------------|------------------|
| site_id | Arbitrary numbering | numeric | An id which designates a 500m long stretch of the Californian coast. |
| year | Year | numeric | Year of measurement. |
| quarter | Quarter | numeric | Quarter of measurement. (Q1 = Jan – Mar, Q2 = Apr – Jun, Q3 = Jul – Sep, Q4 = Oct – Dec) |
| kelp | Kilograms | numeric | Kelp biomass estimated from remotely sensed data and empirical relationships. |
| no3 | Concentration in micro-moles per liter | numeric | Seawater nitrate concentration estimated from empirical relationships with remotely sensed sea surface temperature. |
| waves | Average wave height in meters | numeric | Wave height estimated from swell propagation model. |

Locations

| Column Name (locations.csv) | Unit | Type | Description |
|------------------|------------------|------------------|------------------|
| site_id | Arbitrary numbering | numeric | An id which designates a 500m long stretch of the Californian coast. |
| lat | Latitude | numeric | Latitude. |
| lon | Longitude | numeric | Longitude. |

Temperature

| Column Name (SBH_temperature_20241231) | Unit | Type | Description |
|------------------|------------------|------------------|------------------|
| YEAR | Year | numeric | The calendar year. |
| MONTH | Month | numeric | the calendar month. |
| DAY | Day | numeric | the calendar day. |
| TIME_PST | Time (hour and minute not separated by a colon) | numeric | the time of day. |
| TIME_FLAG | Time flag | numeric | Data quality indicator. |
| SURF_TEMP_C | Temperature (Celsius) | numeric | Temperature in degrees Celsius. |
| SURF_FLAG | Temperature flag | numeric | Data quality indicator. |

### Explaining Terms

Some terms that may not have been obvious as to what they are, were the NPGO, MEI, and PDO that were measured in climind_annual.csv, and climind_quarterly.csv. Here is an explanation as to what they are.

**Multivariate El Nino Southern Oscillation Index (MEI):**

An index used to characterize the intensity of an El Nino event, with high positive values indicating a warming event, and high negative values indicating a cooling event. 

**Pacific Decadal Oscillation (PDO):**

A recurring pattern of water surface temperatures in the Pacific ocean north of 20°N changing between warmer and cooler temperatures every few decades. With positive values indicating a warming event, and negative values indicating a cooling event.\
\
**North Pacific Gyre Oscillation (NPGO):**\
A recurring phase of upwelling, in the form of counter rotating gyres, along 40°N in the Pacific. When the NPGO is positive, upwelling-favorable conditions are seen in the California Current and Alaskan Gyre, while downwelling-favorable conditions are seen in the Subtropical Gyre and the Alaskan Coastal Current.
