# Weather-App

The Weather App is a web application that provides real-time weather information for various locations. Users can search for a city and get details about the current weather conditions, including temperature, weather description, and more.

## Weather App Screenshot
<img width="960" alt="image" src="https://github.com/priyamsinghh/Weather-app/assets/83497025/27ff530d-e8ca-4bb6-843e-d0cf099cf037">


## Features

* Real-time Weather Data: The app fetches real-time weather data using the OpenWeatherMap API, providing users with up-to-date information.
* Location Search: Users can search for a city and get weather details for that specific location.
* Celsius Units: Weather information is displayed in Celsius units for temperature.
* Date and Time: The app displays the current date and time of the searched location.
* Weather Condition: Users can see the current weather condition, such as sunny, cloudy, rainy, etc.
* Min/Max Temperature: The app shows the minimum and maximum temperatures for the day.

## Technologies Used

 <div style="display: flex;">
   <a href="https://developer.mozilla.org/en-US/docs/Web/HTML">
     <img src="https://www.w3.org/html/logo/downloads/HTML5_Badge_512.png" alt="HTML_Logo" width="40"/>
   </a>
   <a href="https://developer.mozilla.org/en-US/docs/Web/CSS">
     <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/62/CSS3_logo.svg/800px-CSS3_logo.svg.png" alt="CSS_Logo" width="40"/>
   </a>
   <a href="https://www.javascript.com">
    <img src="http://code-institute-org.github.io/Full-Stack-Web-Developer-Stream-0/assets/javascript.png" alt="JS_Logo" width="75"/>
   </a>
 </div>


## How to Use
* Clone the repository to your local machine.
* Open the index.html file in your web browser.
* In the search box, enter the name of the city you want to get weather information for.
* Press the 'Enter' key or click the 'Search' button to view the weather details.

## API Key
* To use the Weather App, you need to obtain an API key from OpenWeatherMap.
* Visit OpenWeatherMap website and sign up for a free API key. * Replace the api.key value in the index.js file with your API key.

```javascript
const api = {
  key: "YOUR_API_KEY",
  base: "https://api.openweathermap.org/data/2.5/",
};
```
## Acknowledgments
The Weather App is inspired by a tutorial from Weather App Tutorial. Special thanks to [OpenWeatherMap](https://openweathermap.org/) for providing the weather data API.
