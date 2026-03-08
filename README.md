# ds4eeb_Final_Project

This is the repo for the ds4eeb project. Members include Gabriel, Leah, and Sora.

## Questions and Context

-   Kelp forests host a ton of biological diversity along the coasts of California, but they have been in the decline over the past few years. These kelp forests help sequester atmospheric carbon, helping to reduce the impact of climate change on the planet, but they themselves are also vulnerable. Because of the dynamic change in kelp forest biomass, it is important to understand how different variables could correlate to a more stable population of *Macrocystis Pyrifera*, commonly known as Giant Kelp.

-   As plants, Giant Kelp growth is limited by light and nutrient availability, as well as physical degradation caused by wave action. The study we took the data set from estimated the kelp biomass from satellite imagery, while Nitrate concentration derived from empirical relationships with measured sea surface temperature, and wave data was estimated from a swell propagation model.

Our motivating question:

-   How does nitrate concentration and wave height in the water affects kelp biomass off the central coast of California from 1987 to 2019?

-   Which one is the most important predictor of Giant Kelp biomass?

Target audience:

-   Our target audience are policy makers to see how nitrate concentrations correlate with the growth of giant kelp biomass.

## DAG (Visualized in slides)

Our DAG assumes these relationships:

-   Kelp biomass is the overall variable we want to observe.

-   NPGO (North Pacific Gyre Oscillation) affects the temperature fluctuations of the surface waters and nitrate concentration in the water through the oscillation of the North Pacific Gyre.

-   MEI (Multivariate El Nino Index) affects the temperature fluctuations of the surface waters, nitrate concentration in the water, and wave height through the El Nino and La Nina event cycles.

-   PDO (Pacific Decadal Oscillation) affects the surface temperature of the water and nitrate availability through the decadal patterns in warmer and cooler surface water temperature.

-   Wave height affects nitrate availability through the mixing of water and the physical stress that the kelp goes under. They are more likely to be ripped out with higher waves, thus contributing to less biomass.

-   Temperature affects the nitrate availability through increase in temperature making nitrogen fixing organisms more active, and kelp growth rate.

-   Nitrate affects the productivity of kelp, which contributes to its biomass.

-   There are also at least two unobserved variables:

    -   Grazing affects the kelp biomass through the physical removal of organic material from the plant by herbivores

    -   Eutrophication affects nutrient or pollutant availability in the water, which could inhibit kelp growth
