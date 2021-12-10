# Analysis and operation suggestions for HealthyRide
## Group member: Elaine Zhang, Xintong Zheng, Xi Yan
This project is about analysis and operation suggestions for HealthyRide. In this project, we split into 3 questions to better analyze HealthyRide.
1. How long do users usually ride based on other features?
2. How can we determine usertypes based on other features?
3. What is the influence of weather on trip duration? Weather is examined by average wind speed, precipitation, maximum temperature, minimum temperature, and average temperature.

For the first two questions, we perform classifications, and for the third question, we used clustering to try to answer these questions.
To begin with the project, we first do data processing to import and merge datasets.

To answer these 3 questions, **we need to use 13 csv to answer all 3 of the questions**. 

**The first csv file** is a weather data, which is retrieved from [National Centers for Environmental Information](https://www.ncdc.noaa.gov/cdo-web/search), ranged from Jan.1 2017 to Dec.31 2019, of a weather station located at Pittsburgh, PA, USA.

**The second to thirdteemth csv files** are ride rental data is retrieved from [Western Pennsylvania Regional Data Center](https://data.wprdc.org/dataset/healthyride-trip-data). Each csv contains a quarter of the data of the healthy ride share, and since we are using 2017-2019 data, there will be 4 * 3 = 12 csv files. We have to combine 12 .csv data first in order to finish the cleaning.

More instructions are included in the jupyter notebook.

**Due to that we have a very large dataset (200,000+ rows), please allow some time (15 minutes) to run the model fitting.**
