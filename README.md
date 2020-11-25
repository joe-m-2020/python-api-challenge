# python-api-challenge
Week 6 Homework
WeatherPy
Using openweathermap.org an analysis was run of random cities in the world to gather the city name, latitude, longitude, max temp, humidity, cloudiness, wind speed, country and date of analysis.

Observable trends:
A variety of comparisons were shown to characherize the data.  One thing that was interesting was contrary to initial assumptions, the humidity of the random cities chosen did not get more humid as they became closer to the equator.  This might there is a good chance that the points chosen at random were not surrounded by water since there are several deserts located near the equator.  The cities in these areas would likely also not be any more humid than some northern cities that were chosen.

figures were saved in the Figure sub-folder with data showing the following:
* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude


Observable trends:
1) Humidities in the Southern Hemisphere got higher as the cities were closer to the equator but in the northern hemisphere there was a slight trend to the opposite effect.  This is likely due to the variation in topography of each of the random cities selected by the algorithm.  According to Geography.com (https://geography.name/how-does-specific-humidity-vary-globally-and-seasonally/#:~:text=The%20main%20pattern%20that%20emerges,south%20(toward%20the%20poles) (11/25/2020)). While typically, "The main pattern that emerges from inspection of these globes is that specific humidity varies primarily as a function of latitude — areas near the equator have much higher specific humidity than areas farther north and south (toward the poles)," however, "Patterns of specific humidity are more complicated on land, mostly reflecting the influence of topography, especially large mountain belts that interfere with prevailing winds, such as the Andes of South America."  

2) Cloudiness increases from the lowest latitudes to the highest latitudes in the Northern Hemisphere. According to B. Geerts and E. Linacre at http://www-das.uwyo.edu/~geerts/cwx/notes/chap08/cloud_lat.html.com (11/25/2020), "At this longitude, cloudiness is suppressed at the equator (due to equatorial ocean upwelling, hence lower SSTs, hence atmospheric subsidence). The ITCZ can be seen between 5-10 degreesN (year-round), and the SPCZ is weaker and mostly a summer phenomenon, around 15 degrees S. The main belts of high cloudiness are associated with midlatitude cyclones (30-60 degrees). The baroclinic storm track is found at a higher latitude and is stronger in summer, mainly in the northern hemisphere."  Since the random plots chosen by the algorithm in this exercise included a great deal of land in the southern hemisphere that is closer to the equator, cloudiness is more prevalant in the Northern Hemisphere in this data, increasing as you travel North.

3)Wind has greater speed as you get closer to both of the North and South Poles.  According to National Geographic (https://www.nationalgeographic.org/encyclopedia/wind/ © 2015-2020 National Geographic Partners, LLC. All rights reserved, (11/25/2020) ),  "Winds occur where high-pressure air masses seek low-pressure areas. Prevailing winds are largely predictable and named for broad areas of the Earth over which they form."  The pressure in colder areas such as the North and South Poles creates wind trying to seek the low pressure areas towards the equator.

VacationPy
In this exercise the cities that were randomly chosen were displayed in a heatmap to show the humidity in each location

These locations were then filtered by favorable vacation conditions including humidity, cloudiness and max temperature. This resulted in 20 cities with that met the criterea specified.

A google maps search was performed to find hotels in these areas

These hotels found nearby the city latitudes and longitudes were displayed in a map displaying the hotel name, city and country.