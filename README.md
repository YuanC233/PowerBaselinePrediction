# PowerBaselinePrediction
## Pecan St. Power Data
This folder includes hourly power data for 13 units in Austin, TX. `AustinHourlyPowerDataSummary.txt` summarizes missing data points for each individual unit. Note that 3/11/2018 and 11/4/2018 are the beginning and end of daylight saving time respectively. Therefore, 3/11/2018 should have 23 hourly power readings and 11/4/2018 should have 25. In this dataset, however, only the beginning of the saving time is considered. As a result, 3/11/2018 has 23 points, whereas 11/4/2018 still has 24 hours.

## Darksky Weather Data
### Austin weather data
This file includes weather data for Austin, TX for the entire year of 2018. Daylight saving schedule is consistent, unlike that in Pecan St. Power Data. 3/11/2018 has 23 hours of recording and 11/4/2018 has 25.

**When using the power and weather datasets together, please fill in the missing power data first, and keep the timestamps aligned with each other.**
