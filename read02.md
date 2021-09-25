Investigate appropriate APIs for the City Explorer System, you need to explain the following for each API that will be used:
-	API Description
-	API Usage
-	API Endpoints/Request URLs
-	Authentication Key
<br> <br><br><br>
- Weatherbit: An API I used to get the forecast for three days for the searched city
<br><br>
https://api.weatherbit.io/v2.0/forecast/daily?key=2c3ff4a8cc814c5aa50e972ba2c42b0f&city=Amman&days=3 
<br><br>
Key: 2c3ff4a8cc814c5aa50e972ba2c42b0f

<br><br><br>
- The Movie DB :  An API  I used to get movies contain the same city name used to get the forecast
<br><br>
Key: dfdc5d9540ccc1c9a0a76eab961871c2
<br><br>
https://api.themoviedb.org/3/search/movie?api_key=dfdc5d9540ccc1c9a0a76eab961871c2&query=Amman&language=de-DE&region=DE 

<br><br><br>
- Mapquest Dveloper: An API  I used to get longitude , latitude and a map of the searched city
<br><br>
Key: wFRJKy8kRM2sXSlA6aOmtN8RAG2tqAaJ
<br><br>
https://www.mapquestapi.com/geocoding/v1/address?key=wFRJKy8kRM2sXSlA6aOmtN8RAG2tqAaJ%20&location=Amman 

## Live URL for the system the includes all these API
https://bashar-city-explorer.netlify.app/ 