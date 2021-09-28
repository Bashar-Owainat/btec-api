Investigate appropriate APIs for the City Explorer System, you need to explain the following for each API that will be used:
-	API Description
-	API Usage
-	API Endpoints/Request URLs
-	Authentication Key
<br> <br><br><br>


- Weatherbit: An API I used to get the forecast for three days for the searched city.
<br>
With the Weather API, you may get real-time weather data from over 47,000 live weather stations, as well as historical weather data from over 120,000 stations, doppler radar, satellite, and atmospheric re-analysis products over the previous 10 years. Also, highly localized weather forecasts for any location on the planet, based on the world's most trusted weather models!
<br><br>
You may check up weather information using a variety of methods, including:

- Longitude and latitude

- The name of the city

- Identification of the city

- The location of the weather station

- The International Civil Aviation Organization (ICAO) code for the airport

- For any country in the globe, a postal (zip) code



<br><br>
https://api.weatherbit.io/v2.0/forecast/daily?key=2c3ff4a8cc814c5aa50e972ba2c42b0f&city=Amman&days=3 



<br><br>
Key: 2c3ff4a8cc814c5aa50e972ba2c42b0f

<br><br><br>
- The Movie DB :  An API  I used to get movies contain the same city name used to get the forecast.
<br>
The API service is for individuals who want to use photos and/or data from movies, TV series, or actors in their applications. This API is a system that allows you and your team to retrieve and use our data and/or photos programmatically.


<br><br>
Key: dfdc5d9540ccc1c9a0a76eab961871c2

<br><br>
https://api.themoviedb.org/3/search/movie?api_key=dfdc5d9540ccc1c9a0a76eab961871c2&query=Amman&language=de-DE&region=DE 

<br><br><br>
- Mapquest Dveloper: An API  I used to get longitude , latitude and a map of the searched city.
<br>
Thousands of organizations rely on MapQuest for Business for location-based geospatial solutions. These APIs and SDKs provide access to not only a wide range of maps, but also to key geospatial services like geocoding, routing, geographic search, type ahead, traffic, and more.
This powerful platform enables organizations of any size to improve productivity and optimize processes, engage with customers, and ultimately create an excellent user experience. And, as always, the MapQuest for Business experience is backed by our world-class customer care and technical support.


<br><br>
Key: wFRJKy8kRM2sXSlA6aOmtN8RAG2tqAaJ


<br><br>
https://www.mapquestapi.com/geocoding/v1/address?key=wFRJKy8kRM2sXSlA6aOmtN8RAG2tqAaJ%20&location=Amman 

## Live URL for the system the includes all these API
https://bashar-city-explorer.netlify.app/ 

## other  links 
https://github.com/Bashar-Owainat/city-explorer-api
<br><br>
https://github.com/Bashar-Owainat/city-explorer