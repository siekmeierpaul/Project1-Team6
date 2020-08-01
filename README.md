# Crime in Silver Spring, MD and Temperature
## Authors: Dan Evans, Rose Inglis, Cynthia Kunakom, Paul Siekmeier

Our team explored if there is any correlation between the number of crime incidence and the weather temperature in Silver Spring, Maryland during 2017-2019. We believed that the number of crime incidence may be affected by the weather temperature.

### Data
We retrieved the raw data of crime statistic in Maryland from dataMontgomery (https://data.montgomerycountymd.gov/Public-Safety/Crime/icn6-v9z3), and transcribed the tempearture data from https://www.bestplaces.net/climate/city/maryland/silver_spring into a csv file.

### Scope of Analysis
The questions we tried to answer are the following:
- Is there a correlation between crime against property and the weather temeprature?
- Is there a correlation between crime against person and the weather temeprature?
- Is there a correlation between crime against society and the weather temeprature?

### Methodology
We performed linear regression to establish the correlation and hypothesis testing analysis to confirm whether the correlation between the number of crime incidence in each category and the weather temperature is statistically significant.

### Result & Conclusion
Our statisical analyses suggest that only crime against person category has a statistical significant difference between the average number of crime and the weather temperature (p-value <0.05). The correlation between the number of crime against property or crime agaianst sociaty and the weather temperature are not statistically significant. 

### Limitation
We were unable to get the temperature data for the day of the crime for each rows of our data as we did not set aside a budget to spend on the tempearture data. OpenWeatherApi only allows for 5 days of weather history. Anything beyond that would require a paid transaction. Therefore, we used climate data instead of weather data to get the average temperature for the month instead of the exact temperature on that day in history.

We understand that using climate data negates the validity of our statistically significant result as we did not have enough sample size. However, if we are to perform the same analyses using the real tempearture data, we would expect our statistically significant results to be more valid.
