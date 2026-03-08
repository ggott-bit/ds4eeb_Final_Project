---
title: "README"
format: html
---

# Raw Data

This is a folder where we keep all of our raw data sets before we have modified them.

Here are the sources for all of the data that we used:

### Source 1:

Santa Barbara Coastal LTER, Tom W Bell, Kyle C Cavanaugh, Daniel Reuman, Max C. N. Castorani, Lawrence Sheppard, & Jonathan Walter. (2021). *SBC LTER: REEF: Macrocystis pyrifera biomass and environmental drivers in southern and central California*. LTER Network Member Node. https://pasta.lternet.edu/package/metadata/eml/knb-lter-sbc/144/1.

### Source 2:

Washburn, L. 2025. SBC LTER: Reference: Sea-surface water temperature, Santa Barbara Harbor, Santa Barbara, CA, USA, 1955 to present, ongoing ver 17. Environmental Data Initiative. <https://doi.org/10.6073/pasta/8020223a1e2ed16411f0c18b61fbc3fb>.

### The files

climind_annual.csv was downloaded from Source 1, and goes over the NPGO, MEI, and PDO for each year from 1987 - 2019. Don't worry, I will explain what each of those things are.

climind_quarterly.csv is like climind_annual.csv but quarterly instead of annually, meaning that it has 4 times as many datapoints.

kelp_no3_waves_annual_long.csv was downloaded from Source 1, and goes over the annual kelp biomass in kilograms, seawater nitrate concentration in micro-moles per liter, and wave height in meters at each of 361 half kilometer long segments of beach.

kelp_no3_waves_quarterly_long.csv is like kelp_no3_waves_annual_long.csv but quarterly instead of annually, meaning that it has 4 times as many datapoints.

locations.csv was downloaded from Source 1, and just specifies the latitude and longitude of each of the 361 sites mentioned in the previous two files.

SBH_temperature_20241231.csv was downloaded from Source 2, and goes over the daily surface temperature in Celsius of the water in the Santa Barbara harbor between 1955 and 2024.

### Explaining Terms

Some terms that may not have been obvious as to what they are, were the NPGO, MEI, and PDO that were measured in climind_annual.csv, and climind_quarterly.csv. Here is an explanation as to what they are.

**Multivariate El Nino Southern Oscillation Index (MEI):**

An index used to characterize the intensity of an El Nino event, with high positive values indicating a warming event, and high negative values indicating a cooling event. 

**Pacific Decadal Oscillation (PDO):**

A recurring pattern of water surface temperatures in the Pacific ocean north of 20°N changing between warmer and cooler temperatures every few decades. With positive values indicating a warming event, and negative values indicating a cooling event.\
\
**North Pacific Gyre Oscillation (NPGO):**\
A recurring phase of upwelling, in the form of counter rotating gyres, along 40°N in the Pacific. When the NPGO is positive, upwelling-favorable conditions are seen in the California Current and Alaskan Gyre, while downwelling-favorable conditions are seen in the Subtropical Gyre and the Alaskan Coastal Current.
