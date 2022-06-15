# 06 Server-Side APIs: Weather Dashboard

Developers are often tasked with retrieving data from another application's API and using it in the context of their own. Third-party APIs allow developers to access their data and functionality by making requests with specific parameters to a URL. Your challenge is to build a weather dashboard that will run in the browser and feature dynamically updated HTML and CSS.

Use the [OpenWeather One Call API](https://openweathermap.org/api/one-call-api) to retrieve weather data for cities. Read through the documentation for setup and usage instructions. You will use `localStorage` to store any persistent data.

[OpenWeather One Call API] (https://api.openweathermap.org/)
Connection to the API Open Weather Map is validated with the unique identifyer API KEY which is issued to individual accound user name.

API_key = ('87a484b7a1b830...................')

## User Story

AS A traveler
I WANT to see the weather outlook for multiple cities
SO THAT I can plan a trip accordingly


## Acceptance Criteria

```
GIVEN a weather dashboard with form inputs
WHEN I search for a city
THEN I am presented with current and future conditions for that city and that city is added to the search history
WHEN I view current weather conditions for that city
THEN I am presented with the city name, the date, an icon representation of weather conditions, the temperature, the humidity, the wind speed, and the UV index
WHEN I view the UV index
THEN I am presented with a color that indicates whether the conditions are favorable, moderate, or severe
WHEN I view future weather conditions for that city
THEN I am presented with a 5-day forecast that displays the date, an icon representation of weather conditions, the temperature, the wind speed, and the humidity
WHEN I click on a city in the search history
THEN I am again presented with current and future conditions for that city
```

The following image demonstrates the application functionality:

![weather dashboard demo](./Assets/06-server-side-apis-homework-demo.png)


## Endpoint:
- Please, use the endpoint api.openweathermap.org for your API calls
- Example of API call:
api.openweathermap.org/data/2.5/weather?q=London,uk&APPID=87a484b7a1b8306b493ddb555bad1acd
## API key:
- Your API key is 87a...............

## Included Technologies:

HTML
CSS
JS
    CurrentLocation.js
    dataFuinction.js
    domFunction.js
Also, folder structure was subdivided into:
SCSS
COMPONENTS
    buttons.scss
    a11y.sccs (to display elements offscreen)
LAYOUT
    buttons.scss
    currenForecast.scss
    dailyForecast.scss
    navButtons.scss
    searchBar.scss
THEMES
    backgrounds

Geo Location for the correct idrntifyer of the weather location.
Location Parameters include:
            name: currentLoc.getName(),
            lat: currentLoc.getLatitude(),
            lon: currentLon.getLongitude(),
            unit: currentUnit.getUnit(),


getWeatherFromCoords = Get Weather from the Coordinates is a request URL from the OpenWeather One Call API.



![Weather-Image-1](./Images/weather-img-1.png | width=200px)


## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository. Give the repository a unique name and include a high-quality README describing the project.

- - -
© 2022 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
