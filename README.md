# interstate-migration-2005-2022
Clean and tidy Census Bureau data (from ACS) on interstate migration (including DC and Puerto Rico) from 2005-2022 (2020 missing due to COVID)
Source: https://www.census.gov/data/tables/time-series/demo/geographic-mobility/state-to-state-migration.html

Note that the margins of error are quite high relative to the flows, so I wouldn't use this data to look at individual state pairs over time unless the volume is consistently high

oneway.csv contains 2 observations for each state pair for each year

twoway.csv contains 1 net flow observation for each state pair for each year with the state_to and state_from arranged so that every flow is positive
