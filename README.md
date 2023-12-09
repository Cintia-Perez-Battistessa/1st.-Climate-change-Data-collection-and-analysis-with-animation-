# Climate Change in the Capital Cities of Spain

![](https://github.com/Cintia-Perez-Battistessa/Climate-change-Data-collection-and-analysis/blob/main/maps_Mean%20Temperature%20anomaly.gif)

_Animation  1: Annual mean temperature change from 1963-2022 in Spanish capital cities. Marker color and size indicate if this year's temperature is close to a record for a Capital City. Blue and small makers represent the coldest temperatures, while red and big makers represent the highest temperatures._


<a name="top"></a>
# Table of Contents
* [1. Introduction to Climate Change](#item1)
* [2. Project objectives](#item2)
* [3. About this project](#item3)
* [4. Conclusion](#item4)
* [5. License](#item5)
* [6. Technical Review](#item6)
* [7. Give a Star](#item7)


<a name="item1"></a>
# 1. Introduction to Climate Change
According to NASA, climate change refers to alterations in the typical weather patterns observed in a particular location. Climate change has a global impact, affecting all regions of the world. Some of its effects include loss of sea ice, accelerated sea level rise, and temperature increase, leading to more frequent heat waves.

The main objective of this study was to analyze the climate of Spanish capital cities between 1963 to 2022, including temperature, precipitation, and wind speed. In addition, the data from these cities were grouped together to estimate the impact of climate change on the autonomous communities and the country (Spain).

To analyze climatic variables over time, the annual and monthly anomalies of each one were calculated. These anomalies help identify trends. The anomaly for a specific variable and time period is obtained by calculating the difference between the average value for that period and the average value of the variable for the chosen reference period (1963 to 2022).

The results have shown a significant trend of rising temperatures, commonly known as global warming.

<a name="item2"></a>
# 2. Project objectives 
This project had three primary goals:

1. Collect climate data from the capital cities of Spain between 1963 and 2022.
2. Determine annual and monthly climate anomalies.
3. Identify changes in weather patterns that could indicate climate change.

<a name="item3"></a>
# 3. Data collection 
It was necessary to collect data on the capital cities, their autonomous communities, latitude, and longitude, as well as weather data from 1963 to 2022. Data was fetched from public, free, and official sources 

**Data on capital.** The data were obtained from *Opendatasoft*, a company offering data sharing software. 

**Climatic data.**  The data were obtained from *Open-Meteo* which is an open-source weather API. The information obtained for each capital was Temperature, Total Precipitation, and Maximum wind speed. The following table outlines the different units and defines the climatic variables.

|Variable|Variable name in API|Unit|Description|
|---------------|----------------------|-----|--------------------------------------|
|Mean Temperature|temperature_2m_mean|°C|Mean daily air temperature at 2 meters above ground|
|Maximum Temperature|temperature_2m_max|°C|Maximum daily air temperature at 2 meters above ground|
|Minimum Temperature|temperature_2m_min|°C|Minimum daily air temperature at 2 meters above ground|
|Total Precipitation|precipitation_sum|mm|Sum of daily precipitation (including rain, showers, and snowfall)|
|Maximum Wind Speed|wind_speed_10m_max|km/h|Maximum wind speed on a day|

_Table 1. Climate variables collected from the Open-Meteo API._

<a name="item4"></a>
# 4. Data analysis

<a name="item4.1"></a>
## 4.1. Annual climate anomaly

To calculate the annual climate anomaly in a specific year, it's required to determine the difference between the average annual climate variable for that year (known as the average *annual climate variable*) and the average climate variable value for the period between 1963 and 2022 (known as the *historical average climate variable*).

**Temperature data.**

![Spain_Mean Temperature anomaly](https://github.com/Cintia-Perez-Battistessa/Climate-change-Data-collection-and-analysis/assets/129741210/19765ac6-288a-4cae-8693-0cd3965dcda3)

_Figure 1. The trend in mean temperature between 1963 and 2022._

|Level|Capital City|Year|Mean Temperature anomaly [°C]|
|---|------------------|--------|----------------------|
|1|Granada|2022|2,6|
|2|Burgos|2022|2,48|
|3|Soria|2022|2,47|
|4|Huesca|2022|2,46|
|5|Ciudad Real|2022|2,42|
|6|Cuenca|2022|2,4|
|7|La Rioja|2022|2,36|
|8|Segovia|2022|2,35|
|9|Lleida|2022|2,35|
|10|Badajoz|2022|2,29|

_Table 2. Top 10 in capital cities with the highest annual mean temperature anomaly._


**Precipitation data.**

![Spain_Total Precipitation anomaly](https://github.com/Cintia-Perez-Battistessa/Climate-change-Data-collection-and-analysis/assets/129741210/17c9f77d-84d9-476b-a388-b0868506137f)

_Figure 2. The trend in total precipitation between 1963 and 2022._

|Level|Capital City|Year|Total Precipitation anomaly [mm/day]|
|---|------------------|--------|----------------------|
|1|Cádiz|1996|2,26|
|2|Ceuta|1996|2,11|
|3|Pontevedra|1966|2,06|
|4|Huesca|1971|1,92|
|5|Valencia|1972|1,85|
|6|Castellón|1972|1,72|
|7|Lleida|1972|1,72|
|8|Barcelona|1972|1,69|
|9|Tarragona|1972|1,68|
|10|Gerona|1972|1,63|

_Table 3. It is in the top 10 in capital cities with the highest annual total precipitation anomaly._

**Wind speed data.**
![Spain_Maximum Wind Speed anomaly](https://github.com/Cintia-Perez-Battistessa/Climate-change-Data-collection-and-analysis/assets/129741210/da3fa652-53b4-414c-bc15-044d2ce72c11)

_Figure 3. The trend in maximum wind speed between 1963 and 2022._

|Level|Capital City|Year|Maximum Wind Speed anomaly [Km/h]|
|---|------------------|--------|----------------------|
|1|Valencia|2013|2,2|
|2|Tarragona|2013|2,13|
|3|Islas Baleares|2021|1,86|
|4|Castellón|2013|1,66|
|5|La Coruña|2013|1,63|
|6|Zaragoza|2013|1,63|
|7|Teruel|2013|1,62|
|8|Soria|2013|1,59|
|9|Lugo|2013|1,57|
|10|Albacete|2013|1,54|

_Table 5. It is in the top 10 in capital cities with the highest annual maximum wind speed anomaly._

<a name="item4.1"></a>
## 4.2. Monthly climate anomaly

To calculate the monthly climate anomaly in a particular month and year, it's required to determine the difference between the average climate variable for that specific month and year (known as the average *monthly climate variable*) and the average climate variable value for the period between 1963 and 2022 for that same month (known as the *historical monthly average climate variable*).

**Temperature data.**

![output_reduce](https://github.com/Cintia-Perez-Battistessa/Climate-change-Data-collection-and-analysis/assets/129741210/a5fd1ede-c86e-41c1-9797-b7e705f7a94f)

_Animation 2. The monthly mean temperature anomaly is represented on the polygon graph._

![Temperature](https://github.com/Cintia-Perez-Battistessa/Climate-change-Data-collection-and-analysis/assets/129741210/77c9c966-4295-4eb2-bf45-abac3479a450)

**Precipitation data.**

![output _reduce](https://github.com/Cintia-Perez-Battistessa/Climate-change-Data-collection-and-analysis/assets/129741210/73d0e934-3cfa-49bd-9b0b-0943e01c6450)

_Animation 3. The monthly total precipitation anomaly is represented on the polygon graph._

![total precipitation monthly](https://github.com/Cintia-Perez-Battistessa/Climate-change-Data-collection-and-analysis/assets/129741210/371fce4f-a983-492f-9d0f-2c9a5ddadcbc)

**Wind speed data.**

![output_reduce wind](https://github.com/Cintia-Perez-Battistessa/Climate-change-Data-collection-and-analysis/assets/129741210/b93792ce-e364-4b3d-8c07-729f3b45615c)

_Animation 4. The monthly maximum wind speed anomaly is represented on the polygon graph._

![WIND SPEED](https://github.com/Cintia-Perez-Battistessa/Climate-change-Data-collection-and-analysis/assets/129741210/66d5a4b8-ae39-48d2-ac38-f82bb7e5946a)


<a name="item4"></a>
# 4. Conclusions

Findings from this study can be replicated and extended to the rest of the capital cities of Spain.

According to the results of the study, vulnerable areas in nature management were identified in the context of an increase in air temperature and a decrease in precipitation.

<a name="item5"></a>
# 5. License 
This project is licensed under the Apache License. Please take a look at the LICENSE file for more information.

<a name="item6"></a>
# 6. Technical Review 
I conducted a technical review. Feel free to let me know if you need more information or have feedback.


<a name="item7"></a>
# 7. Give it a Star! ⭐ 
If you find this helpful, please star it. Thanks!


INFORMACIÓN A AGREGAR:

1. AGRUPAR POR COMUNIDAD, SUMAR LAS VARIABLES. DETERMINAR LOS VALORES MÁXIMOS Y MINIMOS. LAS COMUNIDADES QUE MÁS LLUEVE (Poner.. en el norte de españa llueve más).
2. VER COMO CALCULE el valor mensual y anual. Media aritmetica??
3. Hacer Anual de la temperatura, precipitación y viento medio y anomala.
4. Colocar top 10. modo cuadro (https://www.sciencedirect.com/science/article/pii/S2214629622001499)

The monthly data was processed and the arithmetic mean was calculated for each year, and subsequently for each of the studied periods.

The average annual precipitation from 1961 to 2018 varied in the range from 12 mm to 59 mm per year (Fig. 6A). 

The total amount of precipitation (Fig. 4B) for the period from 1950 to 2000 has a range from 88 mm to 321 mm per year. The indicators that have fallen in the north-west (weather stations Kuigan, Aul 4, Bakanas) of the studied area represent a decrease in the total amount of precipitation from 120 to 150 to 100 mm (desert zone). In the mountainous areas of Almaty region, including in the east (weather stations Lepsinsk, Sarkand, Tekeli) and in the south (weather stations Kugaly, Mynzhylki, Almaty (OGMS and Kam. plateau), Ecic) there is an increase in the total amount of precipitation from 250 to 300–320 mm per year (mountain desert-steppe, mountain forest, alpine zones). The central part (Kapshagai, Aksenger, Karashok weather stations) has indicators of reduction from 170 to 200 to 88–100 mm per year (steppe, foothill, mountain-desert-steppe zones).

The maximum temperature (Fig. 5A) measured in the specified period varies from +11 °C to +27 °C. In the northern (weather stations Usharal, Matai, Naimansuyek), north-western (weather stations Kuigan, Aul 4, Bakanas) parts of the Almaty region, there is an increase in the maximum temperature from +22 °C to +27 °C (desert, semi-desert zones). In other parts of the region, the indicators are stable.

The minimum temperature indicators (Fig. 5B) measured in the period from 1950 to 2000 will change in the range from −8°C to −16 °C. According to meteorological data, in Almaty region, except the northern part of the region (weather stations Usharal, Matai, Naimansuyek), there is an increase in the minimum temperature (desert, semi-desert zones).

https://www.sciencedirect.com/science/article/pii/S2405880723000857
doi.org/10.1016/j.cliser.2023.100423
