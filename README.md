# LW300-weather-grabber
A python project to grab weather information from Oregon Scientific LW300 Weather Stations

How it works

- LW300 does DNS request for gateway.weather.oregonscientific.com which you must "grab" and return your own IP address. 
- LW300 sends HTTP GET message to your IP address where python is listening and stores the weather data in db


To get started:
- Configure DNS so that requests from LW300 to OS Server goes to your own server
- Start WeatherGrabberToCassandraDB.py to store weather data in Cassandra OR
- Start SimpleServer.py to store weather data in SQLLite
- Start DataServer.py to access Web app to display weather graphs
- Start Wunderground.py to transfer data from your db to Weather Underground


# TODO  
 Clean up the code and upload here. If you're interested in this project send message and I'll hurry this up ;)
 
