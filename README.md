# Current weather conditions

Search for a US city and see the current weather conditions. As you type a city name, it suggests US cities to you, based on [Mapzen search API](https://mapzen.com/documentation/search/search/). You can still enter an international city and hit Enter to see its weather.

Demo here: https://ampetr89.github.io/dojo-wf-weather

**Note** You will have to accept the warning message to "Load unsafe scripts." This is because the OpenWeatherMap API transfers data over non-secure HTTP.

![Warning message](doc/warning.png?raw=true)

## Functionality

As you start typing to search for a city, it will provide suggestions based on the letters you've typed so far.

![Dropdown menu](doc/options.png?raw=true)

By clicking on a city, you will see the weather in that city, as provided by the OpenWeatherMap API. The background of the page will change to reflect if the current conditions are sunny, cloudy, etc., as well as if it is day or night in the location. Note, if OpenWeatherMap cannot find the city you've entered, it will display an error message. 

### Background Styles
#### Clear background

![Clear](doc/clear.png?raw=true)

#### Cloudy
Day
![Cloudy](doc/cloudy.png?raw=true)


#### Thunderstorm
Day
![Thunder](doc/thunder.png?raw=true)


## Future functionality

* Let users toggle between Celcius and Fahrenheit
* Add forecase using the 5-day / hourly forecast api
* Show a map with an icon so you have the right location (Portland Oregon vs Maine)

