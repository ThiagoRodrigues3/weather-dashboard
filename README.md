# Weather Dashboard


This is a weather dashboard with form inputs that will run in the browser and feature dynamically updated HTML and CSS. It allows the user to search to view weather outlook for multiple cities so travelers can plan a trip accordingly.

[OpenWeather API](https://openweathermap.org/api) is used to retrieve weather data for cities. And `localStorage` is used to store persistent data.

## Installation

1. Download or clone repository
2. Open the main page (index.html) on your browser to view
3. Use an IDE of your choosing to view all coding, Visual Studio Code is recommended.

## Functionality

* When searched for a city, the current and future conditions for that city will be presented and that city is added to the search history
  
* When viewing current weather conditions for the city, the following is shown:
  * City name
  * Date
  * An icon representation of weather conditions
  * Temperature
  * Humidity
  * Wind speed
  * UV index
  
* When viewing the UV index, it is presented with a color indicating severity
  * ![#299501](https://via.placeholder.com/15/3EA72D/000000?text=+) 0-2 Low
  * ![#cea009](https://via.placeholder.com/15/F18B00/000000?text=+) 3-7 Orange
  * ![#bd0713](https://via.placeholder.com/15/E53210/000000?text=+) 8+ Very High
  
  
* When viewing the future weather conditions for the city, a 5-day forecast will be presented with the following information:
  * Date
  * An icon representation of weather conditions
  * Temperature
  * Humidity
  
* When a city in the search history is clicked, the current and future conditions for that city is presented again
* When the weather dashboard is opened, the last searched city forecast is presented
  
## Features

* HTML
* CSS
* Bootstrap
* jQuery
* Moment.js
* Server-Side API - OpenWeather API

## Demo

![Weather Dashboard Demo](Assets/weather-dashboard-demo.gif)

## Websites

* [Github](https://github.com/ThiagoRodrigues3/weather-dashboard)
* [Deployed](https://thiagorodrigues3.github.io/weather-dashboard/)
