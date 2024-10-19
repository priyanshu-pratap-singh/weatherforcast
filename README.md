
# Weather App

## Overview

This is a simple Weather Application built with HTML, CSS, and JavaScript. The app has two main features:

1. **Current Location Weather**: Fetches and displays the weather of the user's current location.
2. **Search Weather by Location**: Allows the user to search for weather details of any city, country, or place worldwide.

## Features

- **Real-time Weather Information**: The app fetches real-time weather data using the OpenWeatherMap API.
- **Current Location Weather**: Automatically detects the user’s location and shows the current weather details.
- **Search Functionality**: Users can search for the weather in any location by entering the city or country name.
- **Responsive Design**: The app is fully responsive and adapts to different screen sizes.
  
## Technologies Used

- **HTML**: For structuring the content of the app.
- **CSS**: For styling the application and making it visually appealing.
- **JavaScript**: For handling the logic, making API calls, and updating the user interface dynamically.
- **OpenWeatherMap API**: For fetching weather data.

## How It Works

1. **Current Location Weather**:  
   When the app loads, it asks for the user's permission to access their location. If granted, it fetches the weather details of the user's current location using the OpenWeatherMap API and displays it.
   
2. **Search Weather**:  
   Users can type the name of any city or country in the search box. Once they submit the search, the app fetches the weather information for that location and displays it.

## Setup Instructions

1. Clone or download this repository.
   ```bash
   git clone https://github.com/your-username/weather-app.git
   ```

2. Navigate to the project directory and open `index.html` in your web browser.
   ```bash
   cd weather-app
   open index.html
   ```

3. To fetch weather data, you will need to get an API key from [OpenWeatherMap](https://openweathermap.org/).
   - Sign up and get an API key.
   - Replace the placeholder `YOUR_API_KEY` in the JavaScript file with your actual API key.

## API Usage

This app uses the [OpenWeatherMap API](https://openweathermap.org/api). You need to get an API key and use it to make requests to get the weather data.

**API Key Setup**:
- Open the JavaScript file.
- Replace the placeholder `YOUR_API_KEY` with your actual API key from OpenWeatherMap.

```javascript
const apiKey = 'YOUR_API_KEY';
```

## Screenshots

![Weather App Screenshot](path-to-screenshot.png)

## License

This project is licensed under the MIT License - see the LICENSE file for details.
