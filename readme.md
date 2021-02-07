# U.S. Weather History

## Data

Column | Description
---|---------
`date` | The date of the weather record, formatted YYYY-M-D
`actual_mean_temp` | The measured average temperature for that day
`actual_min_temp` | The measured minimum temperature for that day
`actual_max_temp` | The measured maximum temperature for that day
`average_min_temp` | The average minimum temperature on that day since 1880
`average_max_temp` | The average maximum temperature on that day since 1880
`record_min_temp` | The lowest ever temperature on that day since 1880
`record_max_temp` | The highest ever temperature on that day since 1880
`record_min_temp_year` | The year that the lowest ever temperature occurred
`record_max_temp_year` | The year that the highest ever temperature occurred
`actual_precipitation` | The measured amount of rain or snow for that day
`average_precipitation` | The average amount of rain or snow on that day since 1880
`record_precipitation` | The highest amount of rain or snow on that day since 1880

Source: [Weather Underground](http://wunderground.com)

We are given 12 Months Of Record-Setting Temperatures Across The U.S. In the code, we perform statistical data analysis and create some visualizations to understand our data well. 

* We'll start by looking at a single city first, in this case, Charlotte. On first glance, it does not look like there are any missing values in the dataset.
* We proceed with converting the fields into proper datatypes.
* Since the data started from 1880, we found there are three instances of 1879, but we choose to keep them since it doesn't make a significance difference. 
* After cleaning out data, we begin visualizing the trend between actual mininum, average minimum, and record minimum temperature as well as for maximum temperatures. 
* Now that we've looked at data from Charlotte, we merge all of the files to compare data from different cities. 
* We then work on data preparation for creating Tableau Dashboard. For that purpose, we create a month column in order to look at aggregate statistics. 
* Let's see how much the data from 2014-2015 varies from the mean historic data from 1880 onwards.

![Graph1](https://user-images.githubusercontent.com/70650689/107132405-c133e780-68ac-11eb-95d8-e7d63dab525a.png)

![graph2](https://user-images.githubusercontent.com/70650689/107132415-e9bbe180-68ac-11eb-95f4-0200a864901c.png)

![graph3](https://user-images.githubusercontent.com/70650689/107132422-01936580-68ad-11eb-9742-44a19245df9f.png)

![graph4](https://user-images.githubusercontent.com/70650689/107132426-0ce69100-68ad-11eb-824c-5583c40a8d9a.png)


Below are the links to the Tableau dashboards, to see how temperature and precipitation changes over the years for different cities across the US.

![Tableau Temperature Distribution](https://public.tableau.com/profile/saumya4852#!/vizhome/AveragetemperatureDistribution/Sheet1)


![Tableau Temperature Map](https://public.tableau.com/profile/saumya4852#!/vizhome/Temperaturemap_16126530357340/Sheet1)


![Tableau Precipitation Map](https://public.tableau.com/profile/saumya4852#!/vizhome/Precipitationmap/Sheet1?publish=yes])
