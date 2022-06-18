# 06 Server-Side APIs: Weather Dashboard

The Weather APP Server Side API is a very useful tool for the users. Developers are using data from other APIs in many applications.  This weather APP Server Side API is one of them. User is making requests with the specific parameters to the open weather API URL. This weather dashboard runs in the browser and features dynamically updated HTML and CSS.

User is sending requests to the [OpenWeather One Call API](https://openweathermap.org/api/one-call-api) to retrieve weather data for cities. Also, user uses `localStorage` to store some data.

[OpenWeather One Call API] (https://api.openweathermap.org/)
When user connecting to the API Open Weather Map is validated with the unique identifier API KEY which is issued to individual account user name.
Open weather map.org offers free service with the creation of the account with the user name and password.  Every user is assigned a unique 
API_key = ('87a484b7a1b830...................')

## User Story

The Weather APP Server Side API is a very usefull tool for the people that love to travel.</br>
They can access the weather outlook for the multiple cities and can plan their trip accordingly to the weather report.


## Application Functionality

```

```
![Uploading weather-app-api-img-1.png…]()
The following image demonstrates the application functionality:

<img width="1070" alt="weather-app-api-img-1" src="https://user-images.githubusercontent.com/98120553/174402143-641c4032-f305-44dc-9e64-7ba40e8d7875.png" width="450" height="">


## Endpoint:
- User have to use the endpoint api.openweathermap.org for the API calls</br>
- Example of API call:</br>
(https://api.openweathermap.org/data/2.5/weather?q=${inputVal}&appid=${apiKey}&units=imperial`;)
## API key:</br>
- Your API key is 87a484b7a1b83.............</br>
## Included Technologies:

HTML</br>
CSS</br>
JS</br>
   script.js</br>
   index.html</br>
   styles.css</br>



            
## API Call:           
https://api.openweathermap.org/data/3.0/onecall?lat={lat}&lon={lon}&exclude={part}&appid={API key}     

## Parameters          
Geographical coordinates (latitude, longitude) `lat``lon``appid``exclude``units``lang`</br>
By using these parameters user can exclude some parts of the weather data from the API response.



## Source
Google Search</br>
https://openweathermap.org/</br>
The One Call API provides the following weather data for any geographical coordinates:</br>
Current weather</br>
Minute forecast for 1 hour</br>
Hourly forecast for 48 hours</br>
Daily forecast for 8 days</br>
National weather alerts</br>

