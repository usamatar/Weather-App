# Weather App

A responsive and interactive weather application built using HTML, CSS, and JavaScript. Get real-time weather information for any location around the world!

## Features

- **Real-Time Weather:** Displays the current weather conditions, temperature, humidity, and wind speed.
- **Search Functionality:** Look up weather data for any city or location.
- **Geolocation Support:** Automatically fetch weather data based on your current location.
- **Dynamic Backgrounds:** Visualize weather conditions with dynamic background changes.
- **Responsive Design:** Optimized for both desktop and mobile devices.

## How to Use

1. Clone this repository:

   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd <repository-name>
   ```

3. Open the `index.html` file in your browser.

4. Enter the name of a city in the search bar or allow location permissions to get weather data for your current location.

## Code Overview

The app is implemented in `script.js` with the following key components:

- **Weather API Integration:** Utilizes a weather API (e.g., OpenWeatherMap) to fetch real-time data.
- **Search and Geolocation:** Handles user input for city searches and retrieves geolocation data.
- **Dynamic Updates:** Updates the UI with weather details, including temperature, conditions, and icons.
- **Error Handling:** Displays user-friendly messages for invalid locations or API errors.

### Key Functions

- **fetchWeather(city):** Fetches weather data for the specified city.
- **fetchWeatherByLocation(lat, lon):** Retrieves weather data using latitude and longitude.
- **updateUI(data):** Dynamically updates the user interface with weather information.
- **handleError():** Displays error messages for invalid API responses or user inputs.

## Setup

1. Obtain an API key from [OpenWeatherMap](https://openweathermap.org/api).
2. Replace the placeholder API key in `script.js` with your actual API key:
   ```javascript
   const apiKey = 'your-api-key-here';
   ```
3. Save your changes and reload the application.

## Contributing

Contributions are welcome! Feel free to fork the repository, make changes, and submit a pull request. Suggestions for new features or improvements are greatly appreciated.

##

