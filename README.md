# Solar_Power_Plant_Production_Prediction

The company provides electricity distribution and sales services to 10.1 million customers and more than 21 million users in 14 provinces. At the same time, we make significant contributions to sustainability thanks to our electricity distribution investments and operations focused on people, technology and solutions.

Operations also include hourly energy trading in electricity markets. Within the scope of this datathon, we estimate hourly production amounts of unlicensed solar power plants in our region. It is expected that the production totals of the unlicensed solar power plants located in the capital region between 01.12.2021 and 31.12.2021 are estimated on an hourly basis. The success metric is set as RMSE(Root Mean Square Error).

In the data set, the total hourly generation amounts of unlicensed solar power plants located in the Başkent region between 01.01.2019 and 30.11.2021 are given. Within this region, there are a total of 848 power plants located in the provinces of Ankara, Çankırı, Kırıkkale, Bartın, Karabük, Kastamonu and Zonguldak. In addition to the total production; Since the production weight is in Ankara, the temperature variables of Ankara province were shared between 01.01.2019 - 31.12.2021. The temperature variables include forecast data for the period 01.01.2019 to 30.11.2021, from 01.12.2021 to 31.12.2021.

The total number and installed power of these power plants on a provincial basis are as follows:

| City | Quantity  | #Total Power(kW)  |
| :---:   | :-: | :-: |
| Ankara | 664 | 382804.941 |
| Bartın | 2 | 520 |
| Karabük | 25 | 14561.2 |
| Kastamonu | 25 | 9616.6 |
| Kırıkkale | 61 | 55336 |
| Zonguldak | 5 | 2830 |
| Çankırı | 66 | 56336.16 |


In addition to shared data, data enrichment can be done using data from open source data sources.

The date range to be estimated has been determined as 01.12.2021 – 31.12.2021.

In the generation table:

* DateTime: specifies the time range in which the production was made in date-time format.
* Generation: Specifies the total production in MWh in the relevant hour range.

In the temperature table:

* DateTime: Specifies the time interval in which temperature variables are observed.
* AirTemperature: Specifies the air temperature in the hour range in Celsius.
* ComfortTemperature: Indicates the sensed air temperature in the hour range in Celsius.
* RelativeHumidity: Specifies the humidity in the hour range.
* WindSpeed: Specifies the wind speed in the hour range in km/h.
* WindDirection: Specifies the wind direction in the hour range.
* WWCode: Specifies the weather code in the time range.
* EffectiveCloudCover: Specifies the amount of cloudiness in the hour range in octal units of measure.
