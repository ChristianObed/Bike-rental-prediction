# Bike-rental-prediction

this Repository contains some project i have done on IBM Data Analytics with Excel and R Professional Certificate
 https://www.coursera.org/professional-certificates/ibm-data-analyst-r-excel

Rental bikes are available in many cities around the globe. It is important for each of these cities to provide a reliable supply of rental bikes to optimize availablity and accessibility to the public at all times. Also important is minimizing the cost of these programs, in part by minimizing the number of bikes supplied in order to meet the demand. Thus, to help optimize the supply it would be helpful to be able to predict the number of bikes required each hour of the day, based on currrent conditions such as the weather.

The Seoul Bike Sharing Demand Data Set([seoul_bike_sharing.csv](seoul_bike_sharing.csv)) was designed for this purpose. It contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), and the number of bikes rented per hour and date.

### Dataset Sample
| Date     | RENTED_BIKE_COUNT | Hour | TEMPERATURE | HUMIDITY | WIND_SPEED | VISIBILITY | DEW_POINT_TEMPERATURE | SOLAR_RADIATION | RAINFALL | SNOWFALL | SEASONS | HOLIDAY   | FUNCTIONING_DAY |
| ---------|-------------------| -----|-------------|----------|------------|------------|-----------------------|----------------------------|----------|----------|---------|-----------|-----------------|
|01/12/2017|	254               |   0  | -5.2        |     37   |     2.2    |    2000    |           -17.6	      |      0         |   0       |     0    |    0     | WINTER  | NO HOLIDAY|         YES     |
|01/12/12017| 204              |   1  |     -5.5    |     38   |     0.8    |    2000    |           -17.6	      |      0         |   0       |     0    |    0     | WINTER  | NO HOLIDAY|         YES     |
|01/12/12017| 173              |   2  |     -6.0    |     39   |     1.0    |    2000    |           -17.7	      |      0         |   0       |     0    |    0     | WINTER  | NO HOLIDAY|         YES     |
|01/12/12017| 107              |   3  |     -6.2    |     40   |     0.9    |    2000    |           -17.6       |      0         |   0       |     0    |    0     | WINTER  | NO HOLIDAY|         YES     |
