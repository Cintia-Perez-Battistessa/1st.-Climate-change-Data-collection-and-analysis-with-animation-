# Climate Change in the Capital Cities of Spain

![](https://github.com/Cintia-Perez-Battistessa/Climate-change-Data-collection-and-analysis/blob/main/maps_Mean%20Temperature%20anomaly.gif)

>_Animation  1: Annual mean temperature change from 1963-2022 in Spanish capital cities. Marker color and size indicate if this year's temperature is close to a record for a Capital City. Blue and small makers represent the coldest temperatures, while red and big makers represent the highest temperatures._



<a name="readme"></a>
# Table of Contents
* [1. Introduction to Climate Change](#1_r_1)
* [2. Project objectives](#2_r_1)
* [3. Data collection](#3_r_1)
  + [3.1 Data on capital](#3.1_r_1)
  + [3.2 Climatic data](#3.2_r_1)
* [4. Data analysis](#4_r_1)
  + [4.1 Annual climate anomaly](#4.1_r_1)
    * [4.1.1. Temperature data](#4.1.1_r_1)
    * [4.1.2. Precipitation data](#4.1.2_r_1)
    * [4.1.3. Wind speed data](#4.1.3_r_1)
  + [4.2 Monthly climate anomaly](#4.2_r_1)
    * [4.2.1. Temperature data](#4.2.1_r_1)
    * [4.2.2. Precipitation data](#4.2.2_r_1)
    * [4.2.3. Wind speed data](#4.2.3_r_1)
* [5. Conclusion](#5_r_1)
* [6. License](#6_r_1)
* [7. Technical Review](#7_r_1)
* [8. Give it a Star](#8_r_1)


<a name="1_r_1"></a>
# 1. Introduction to Climate Change
According to NASA, climate change refers to alterations in the typical weather patterns observed in a particular location. Climate change has a global impact, affecting all regions of the world. Some of its effects include loss of sea ice, accelerated sea level rise, and temperature increase, leading to more frequent heat waves.

The main objective of this study was to analyze the climate of Spanish capital cities between 1963 to 2022, including temperature, precipitation, and wind speed. In addition, the data from these cities were grouped together to estimate the impact of climate change on the autonomous communities and the country (Spain).

To analyze climatic variables over time, the annual and monthly anomalies of each one were calculated. These anomalies help identify trends. The anomaly for a specific variable and time period is obtained by calculating the difference between the average value for that period and the average value of the variable for the chosen reference period (1963 to 2022).

This report will explain the study using Spain's results to aid comprehension. But, the findings from this study can be replicated and extended to Spain's autonomous communities and capitals. Just remember the results for Spain and autonomous communities are an extrapolation of the results for the Spanish capitals.

<a name="2_r_1"></a>
# 2. Project objectives 
This project had three primary goals:

1. Collect climate data from the capital cities of Spain between 1963 and 2022.
2. Determine annual and monthly climate anomalies.
3. Identify changes in weather patterns that could indicate climate change.

<a name="3_r_1"></a>
# 3. Data collection 

It was necessary to collect data on the capital cities, their autonomous communities, latitude, and longitude, as well as weather data from 1963 to 2022. Data was fetched from public, free, and official sources 

<a name="3.1_r_1"></a>
### 3.1. Data on capital
The data were obtained from *Opendatasoft*, a company offering data sharing software. 

<a name="3.2_r_1"></a>
### 3.2. Climatic data 
The data were obtained from *Open-Meteo* which is an open-source weather API. The information obtained for each capital was Temperature, Total Precipitation, and Maximum wind speed. The following table outlines the different units and defines the climatic variables.

|Variable|Variable name in API|Unit|Description|
|----|----|:----:|----|
|Mean Temperature|temperature_2m_mean|°C|Mean daily air temperature at 2 meters above ground|
|Maximum Temperature|temperature_2m_max|°C|Maximum daily air temperature at 2 meters above ground|
|Minimum Temperature|temperature_2m_min|°C|Minimum daily air temperature at 2 meters above ground|
|Total Precipitation|precipitation_sum|mm|Sum of daily precipitation (including rain, showers, and snowfall)|
|Maximum Wind Speed|wind_speed_10m_max|km/h|Maximum wind speed on a day|

>_Table 1. Climate variables collected from the Open-Meteo API._

<a name="4_r_1"></a>
# 4. Data analysis

<a name="4.1_r_1"></a>
## 4.1. Annual climate anomaly

To calculate the annual climate anomaly in a specific year, it's required to determine the difference between the average annual climate variable for that year (known as the average *annual climate variable*) and the average climate variable value for the period between 1963 and 2022 (known as the *historical average climate variable*).

<a name="4.1.1_r_1"></a>
### 4.1.1. Temperature data

The trend in mean temperature over the years is represented in a bar graph (Figure 1). The color scale ranges from blue to red, with the blue representing values closer to record lows and the redder colors indicating values closer to record highs for that year's anomaly. The graph shows a noticeable temperature rise, which is a clear indication of global warming in Spain. 

In 2022, Spain had a record high mean daily Mean Temperature of 1.94 °C above the historical average between 1963-2022 (13.44 °C), and in 1972, a record low of -1.67 °C below the historical average.

![Spain_Mean Temperature anomaly](https://github.com/Cintia-Perez-Battistessa/Climate-change-Data-collection-and-analysis/assets/129741210/19765ac6-288a-4cae-8693-0cd3965dcda3)

>_Figure 1. The trend in mean temperature between 1963 and 2022._

The 10 capitals of Spain that presented the greatest mean temperature anomaly were analyzed (Table 2). The most significant anomalies occurred in 2022, with Granada having the highest value (2,6 °C).

|Level|Capital city|Year|Mean temperature anomaly [°C]|Historial average mean temperature [°C]|
|:----:|------------------|:----:|:----:|:----:|
|1|Granada|2022|2,6|13,63|
|2|Burgos|2022|2,48|10,04|
|3|Soria|2022|2,47|10,43|
|4|Huesca|2022|2,46|11,42|
|5|Ciudad Real|2022|2,42|14,8|
|6|Cuenca|2022|2,4|11,57|
|7|La Rioja|2022|2,36|8,98|
|8|Segovia|2022|2,35|11,18|
|9|Lleida|2022|2,35|10,04|
|10|Badajoz|2022|2,29|16,48|

>_Table 2. Top 10 of capital cities with the highest annual mean temperature anomaly._

<a name="4.1.2_r_1"></a>
### 4.1.2. Precipitation data

The trend in total precipitation over the years is represented in a bar graph (Figure 2). Unlike temperature, there is no clear trend in total precipitation over the years. However, data shows that the precipitation was higher in the earlier years, indicating a decrease in precipitation over time.

In 1972, Spain had a record high mean daily Total Precipitation of 48.5 mm/day above the historical average between 1963-2022 (92.47 mm/day), and in 2005, a record low of -27.18 mm/day below the historical average.

![Spain_Total Precipitation anomaly](https://github.com/Cintia-Perez-Battistessa/Climate-change-Data-collection-and-analysis/assets/129741210/17c9f77d-84d9-476b-a388-b0868506137f)

>_Figure 2. The trend in total precipitation between 1963 and 2022._

The 10 capitals of Spain that presented the greatest total precipitation anomaly were analyzed (Table 3). The analysis indicates that the majority of the highest precipitation records occurred within the initial years of the study period, as previously mentioned.

|Level|Capital city|Year|Total precipitation anomaly [mm/day]|Historical average total precipitation [mm/day]|
|:----:|------------------|:----:|:----:|:----:|
|1|Cádiz|1996|2,26|2,1|
|2|Ceuta|1996|2,11|2,0|
|3|Pontevedra|1966|2,06|3,84|
|4|Huesca|1971|1,92|2,78|
|5|Valencia|1972|1,85|1,52|
|6|Castellón|1972|1,72|1,47|
|7|Lleida|1972|1,72|2,3|
|8|Barcelona|1972|1,69|2,13|
|9|Tarragona|1972|1,68|1,57|
|10|Gerona|1972|1,63|2,73|

>_Table 3. Top 10 of capital cities with the highest annual total precipitation anomaly._

<a name="4.1.3_r_1"></a>
### 4.1.3. Wind speed data

The trend in maximum wind speed over the years is represented in a bar graph (Figure 2). A slight increase in maximum wind speeds is observed.

In 2013, Spain had a record high mean daily Maximum Wind Speed of 0.98 Km/h above the historical average between 1963-2022 (15.77 Km/h), and in 1983, a record low of -0.72 Km/h below the historical average.

![Spain_Maximum Wind Speed anomaly](https://github.com/Cintia-Perez-Battistessa/Climate-change-Data-collection-and-analysis/assets/129741210/da3fa652-53b4-414c-bc15-044d2ce72c11)

>_Figure 3. The trend in maximum wind speed between 1963 and 2022._

The 10 capitals of Spain that presented the greatest maximum wind speed anomaly were analyzed (Table 4). The analysis indicates that the majority of the highest precipitation records occurred in 2013, with Valencia having the highest value (2,2 °C).

|Level|Capital city|Year|Maximum wind speed anomaly [Km/h]|Historical average maximum wind speed [Km/h]|
|:----:|------------------|:----:|:----:|:----:|
|1|Valencia|2013|2,2|15,55|
|2|Tarragona|2013|2,13|16,69|
|3|Islas Baleares|2021|1,86|17,5|
|4|Castellón|2013|1,66|14,42|
|5|La Coruña|2013|1,63|19,11|
|6|Zaragoza|2013|1,63|22,24|
|7|Teruel|2013|1,62|16,35|
|8|Soria|2013|1,59|17,16|
|9|Lugo|2013|1,57|17,93|
|10|Albacete|2013|1,54|16,45|

>_Table 5. Top 10 of capital cities with the highest annual maximum wind speed anomaly._

<a name="4.1_r_1"></a>
## 4.2. Monthly climate anomaly

To calculate the monthly climate anomaly in a particular month and year, it's required to determine the difference between the average climate variable for that specific month and year (known as the average *monthly climate variable*) and the average climate variable value for the period between 1963 and 2022 for that same month (known as the *historical monthly average climate variable*).

<a name="4.2.1_r_1"></a>
### 4.2.1. Temperature data

The monthly temperature anomaly animation is presented between 1963 and 2022 (Animation 2), revealing an expanding polygon area over time. It represented a rise in temperatures. 

![output_reduce](https://github.com/Cintia-Perez-Battistessa/Climate-change-Data-collection-and-analysis/assets/129741210/a5fd1ede-c86e-41c1-9797-b7e705f7a94f)

>_Animation 2. The monthly mean temperature anomaly is represented on the polygon graph between 1963 and 2022._

Below is the trend mean temperature for each month between 1963 and 2022 (Figure 4). Most months showed a rising temperature trend over the years. 

![Temperature](https://github.com/Cintia-Perez-Battistessa/Climate-change-Data-collection-and-analysis/assets/129741210/77c9c966-4295-4eb2-bf45-abac3479a450)

>_Figure 4. The trend mean temperature during a specific month between 1963 and 2022: (a)January, (b)February, (c)March, (d)April, (e)May, (f)June, (g)July, (h)August, (i)September, (j)October, (k)November, (l)December._

The largest anomaly for each month is listed below (Table 6). The highest was in June with 3,47 °C above the historical average between 1963-2022 (18,91 °C).

|Month|Year|Monthly mean temperature anomaly [°C]|Historical monthly mean temperature [°C]|
|--------|:------:|:------:|:------:|
|January|2016|2,36|6,0|
|February|2020|3,25|6,93|
|March|1997|3,0|9,08|
|April|2011|2,96|11,17|
|May|2022|3,19|14,79|
|June|2017|3,47|18,91|
|July|2022|3,16|22,08|
|August|2003|2,49|22,02|
|September|1987|2,47|18,86|
|October|2022|3,23|14,54|
|November|2022|2,25|9,62|
|December|2022|2,9|6,81|

>_Table 6. The highest recorded monthly mean temperature anomalies in Spain for each month._

<a name="4.2.2_r_1"></a>
### 4.2.2. Precipitation data

The monthly total precipitation anomaly animation is presented between 1963 and 2022 (Animation 3). In this, it isn't easy to find a trend in precipitation from the animation.  

![output _reduce](https://github.com/Cintia-Perez-Battistessa/Climate-change-Data-collection-and-analysis/assets/129741210/73d0e934-3cfa-49bd-9b0b-0943e01c6450)

>_Animation 3. The monthly total precipitation anomaly is represented on the polygon graph between 1963 and 2022._

The graphs below present the monthly total precipitation between 1963 and 2022 (Figure 5). Over the years, a trend cannot be observed in the precipitation of most months, except for a slight trend to decrease during some months, like June, July, and August.

![total precipitation monthly](https://github.com/Cintia-Perez-Battistessa/Climate-change-Data-collection-and-analysis/assets/129741210/371fce4f-a983-492f-9d0f-2c9a5ddadcbc)

>_Figure 5. The trend total precipitation during a specific month between 1963 and 2022: (a)January, (b)February, (c)March, (d)April, (e)May, (f)June, (g)July, (h)August, (i)September, (j)October, (k)November, (l)December._

The largest anomaly for each month is listed below (Table 7). The highest was in January with 171,72 mm/day above the historical average between 1963-2022 (102,72 mm/day).

|Month|Year|Monthly total precipitation anomaly [mm/day]|Historical monthly total precipitation [mm/day]|
|--------|:------:|:------:|:------:|
|January|1970|171,72|102,72|
|February|1966|119,29|103,79|
|March|2018|136,8|97,64|
|April|1971|103,63|117,54|
|May|1971|153,65|101,43|
|June|1988|103,02|72,29|
|July|1971|73,81|40,81|
|August|1983|73,2|49,49|
|September|1972|111,96|78,99|
|October|2003|109,5|112,73|
|November|1984|121,64|123,24|
|December|1996|154,7|110,66|

>_Table 7. The highest recorded monthly total precipitation anomalies in Spain for each month._

<a name="4.2.3_r_1"></a>
### 4.2.3. Wind speed data

The monthly maximum wind speed  anomaly animation is presented between 1963 and 2022 (Animation 3). In this, it isn't easy to find a trend in maximum wind speed from the animation. 

![output_reduce wind](https://github.com/Cintia-Perez-Battistessa/Climate-change-Data-collection-and-analysis/assets/129741210/b93792ce-e364-4b3d-8c07-729f3b45615c)

>_Animation 4. The monthly maximum wind speed anomaly is represented on the polygon graph between 1963 and 2022._

The graphs below present the monthly maximum wind speed between 1963 and 2022 (Figure 6). Like precipitation, the trend over time of maximum wind is not very marked. However, an increase in maximum wind speed can be observed in some months, such as June, July, and August.

![WIND SPEED](https://github.com/Cintia-Perez-Battistessa/Climate-change-Data-collection-and-analysis/assets/129741210/66d5a4b8-ae39-48d2-ac38-f82bb7e5946a)

>_Figure 6. The trend maximum wind speed during a specific month between 1963 and 2022: (a)January, (b)February, (c)March, (d)April, (e)May, (f)June, (g)July, (h)August, (i)September, (j)October, (k)November, (l)December._

The largest anomaly for each month is listed below (Table 7). The highest was in December with 6,01 km/h above the historical average between 1963-2022 (15,57 km/h).

|Month|Year|Monthly maximum wind speed anomaly [km/h]|Historical monthly maximum wind speed [km/h]|
|--------|:------:|:------:|:------:|
|January|2001|3,75|15,79|
|February|2014|4,79|16,8|
|March|2018|5,71|17,12|
|April|1998|3,97|17,0|
|May|1981|1,59|16,05|
|June|2012|1,53|15,42|
|July|2009|1,34|15,54|
|August|2007|1,65|15,17|
|September|1998|2,31|14,47|
|October|1993|3,53|14,91|
|November|2019|5,17|15,52|
|December|1981|6,01|15,57|

>_Table 8. The highest recorded monthly maximum wind speed anomalies in Spain for each month._

<a name="5_r_1"></a>
# 5. Conclusions

First of all, I would like to emphasize that there are few free sources available for extracting historical climate data. After searching, I discovered the Open-Meteo API, which allowed me to achieve my first objective.

Secondly, both the values of the anomalies of the climatic variables and their diverse graphic representations and animation helped analyze changes in patterns and possible trends in them.

Finally, after finishing my studies in Spain, I found a strong trend of increasing air temperature, also known as global warming, and a slight trend of decreasing precipitation and increasing maximum wind speed.

<a name="6_r_1"></a>
# 6. License 
This project is licensed under the Apache License. Please take a look at the LICENSE file for more information.

<a name="7_r_1"></a>
# 7. Technical Review 
I conducted a technical review. Feel free to let me know if you need more information or have feedback.


<a name="8_r_1"></a>
# 8. Give it a Star! ⭐ 
If you find this helpful, please star it. Thanks!

