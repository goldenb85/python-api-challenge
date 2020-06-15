# python-api-challenge
## Summary ##
This project is designed to fetch data from [OpenWeatherMap API](https://openweathermap.org/api). Visualizations of the weather of 500+ cities across the world of varying distance from the equator will be created. A series of scatter plots will be built to showcase the following relationships:<br>
* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

Conclusion for trends:
1. It is obvious that temperature have a correlation with latitude. Temperature is higher around equator area compared to other area. The Southern Hemisphere is warmer than the Northern Hemisphere, because it is summer in the Southern Hemisphere now.
2. There is no very obvious association between latitude and humidity. However, there are many cities between Lat=40~80 with very high humidity above 60%.
3. There is no very obvious association between latitude and cloudiness. Many cities aggregate along the cloudiness 0, 20, 40, ~78, 100 to form a horizontal line.
4. There is no very obvious association between latitude and wind speed. With high latidude for both Northern and Southern Hemisphere, the wind speed of several cities is over 25 mph, while the wind speed of most of the cities that extracted is between 0 and 15 mph.
## Data Source ##
[OpenWeatherMap API](https://openweathermap.org/api)
## Tool ##
Python (Jupyter Notebook), API
## Visualization ##

* Lat vs Cloudiness<br>
<img src="Png/Lat vs Cloudiness.png"><br>
* Lat vs Humidity<br>
<img src="Png/Lat vs Humidity.png"><br>
* Lat vs Max Temp<br>
<img src="Png/Lat vs Max Temp.png"><br>
* Lat vs Wind Speed<br>
<img src="Png/Lat vs Wind Speed.png"><br>

## Extra
API key needs to be used to fetch data from data source. API key can be obtained by signing up an account on the [OpenWeatherMap API](https://openweathermap.org/api).

## Contact
Email: xinlianghuang85@gmail.com