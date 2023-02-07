# predict-guests-on-mountain
Machine learning to predict number of people on the mountain acessed through the Flims/Laax/Falera resort. Includes data collection. 

In progress!

## Prediction
Using machine learning, actual model and process to be determined once sufficient data has been collected. Core data is collected through the Laax app. Minimal input: `day of year`, `year`, `time`. Output: predicted number of people on the mountain. More specifics on the input: 
Inputs (features): 
- Day of year, 0 to 365. 
- Year
- Minute of day to nearest 10, 0 to 1440.
- Total number people yesterday (planned)
- Is weekend? 
- Public holiday in CH? DE? AT? UK (planned)
- School holiday in CH? (planned) 
- Laax open event? (planned) 
- 1-day ticket price day before (planned) 
- Measured amount of snow (planned)
- Precipitation, temperature (planned)
- Which restaurants on the mountain open? (planned)
- Which lifts open? (planned) 
- Did bus arrive in previous 10-minute window? (planned)


## Data collection
Collect data every 10 minutes through the Laax app, which displays the number of people on the mountain, as well as which base station they came from (Flims, Laax, Falera, other). Other data is scraped the day before from various sources, or calculated. 
