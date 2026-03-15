# newdf README

This is the folder where we put the combined dataframes. These dataframes were created in Final_Presentation_Gabriel.qmd, and there are little blurbs explainin what they are.

combined_sitespecific_climind_temp.csv is SBH_temperature_20241231.csv and climind_quarterly.csv merged together.

combines_kelp_climind_data.csv is climind_quarterly.csv and kelp_no3_waves_quarterly_long.csv merged together.

## Data

| Column Name (combined_sitespecific_climind_temp.csv) | Unit | Type | Description |
|------------------|------------------|------------------|------------------|
| site_id | Arbitrary Numbering | numeric | An id which designates a 500m long stretch of the Californian coast. |
| year | Year | numeric | Year of measurement. |
| quarter | Quarter | numeric | Quarter of measurement. |
| kelp | Kilograms | numeric | Kelp biomass estimated from remotely sensed data and empirical relationships. |
| no3 | Micromoles/Liter | numeric | Seawater nitrate concentration estimated from empirical relationships with remotely sensed sea surface temperature. |
| waves | Meters | numeric | Wave height estimated from swell propagation model. |
| NPGO | standard deviations | numeric | See NPGO in explaining terms. |
| MEI | MEI.v2 | numeric | See MEI in explaining terms. |
| PDO | Degree offset | numeric | See PDO in explaining terms. |
| mean_surf_temp | Degrees Celcius | numeric | The mean sea surface temperature. |

| Column Name (combined_kelp_climind_data.csv) | Unit | Type | Description |
|------------------|------------------|------------------|------------------|
| site_id | Arbitrary Numbering | numeric | An id which designates a 500m long stretch of the Californian coast. |
| year | Year | numeric | Year of measurement. |
| quarter | Quarter | numeric | Quarter of measurement. |
| kelp | Kilograms | numeric | Kelp biomass estimated from remotely sensed data and empirical relationships. |
| no3 | Micromoles/Liter | numeric | Seawater nitrate concentration estimated from empirical relationships with remotely sensed sea surface temperature. |
| waves | Meters | numeric | Wave height estimated from swell propagation model. |
| NPGO | standard deviations | numeric | See NPGO in explaining terms. |
| MEI | MEI.v2 | numeric | See MEI in explaining terms. |
| PDO | Degree offset | numeric | See PDO in explaining terms. |
