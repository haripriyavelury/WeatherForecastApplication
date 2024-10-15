# WeatherForecastApplication

## Overview  
The Weather Forecast Application is a web-based application that allows users to search and view current weather 
data and a detailed 5-day forecast for any city around the world. The application uses the OpenWeatherMap API to fetch weather data.  

## Features  
- Search for current weather by city name or current location.  
- View a detailed 5-day weather forecast, including temperature, wind speed, humidity, and time for each forecast.  
- Input validation to handle empty inputs and invalid locations.  
- Responsive design for ipadmini, desktop and IphoneSE screens.  

## Technologies Used  
- HTML  
- Tailwind CSS  
- JavaScript  
- OpenWeatherMap API  

### Prerequisites  
- A web browser to run the application.  
- A text editor or IDE for modifying the code.  

### Installation  
1.  GIT HUB repository:  

    git link https://github.com/haripriyavelury/WeatherForecastApplication
      
2. Open `index.html` in your preferred web browser.  

3. Sign up for a free OpenWeatherMap API key at [OpenWeatherMap](https://openweathermap.org/appid).  

4. Replace the placeholder in the JavaScript code (`YOUR_API_KEY`) with your actual API key.  

### Usage  
1. Open the application in your web browser.  
2. Enter a city name in the input field and click on the search button.  
3. The application will display the current weather and a 5-day forecast for the requested city.  
4. In case of an invalid input (empty or incorrect city name), the application will provide user-friendly error messages.  

### Code Explanation  
- **HTML Structure**: Contains a simple form for user input and sections to display weather information.  
- **CSS Styling**: Basic styling for a clean user interface, ensuring responsiveness across devices.  
- **JavaScript Logic**:  
  - Handles user input and API requests to fetch weather data.  
  - Displays current weather and forecast in an organized manner.  
  - Implements input validation to ensure users enter valid city names.  
  
### Example  
When you search for a city like "Delhi", the result will show the current weather of the city and also a forecast for 5 days on 3 hour basis indicating temperature, wind speed, and humidity.

## Acknowledgements  
- [OpenWeatherMap API](https://openweathermap.org/api) for providing weather data while using API KEY.  
