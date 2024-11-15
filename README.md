# Weather-App

## Overview

The **Weather App** is a web application that provides real-time weather updates and forecasts based on user location or specified cities. It utilizes the openWeatherAPI for weather data, OpenStreetMap for geolocation mapping, and the News API to display the latest news articles relevant to the weather conditions. The app features a clean, responsive design that enhances the user experience.

### Features

- Current weather conditions based on geolocation or user input.
- Interactive map displaying the user's location.
- News section displaying trending articles related to weather.
- Local time display and date management for forecasts.

## Technologies Used

- HTML5
- CSS (with Bootstrap for styling)
- JavaScript (jQuery)
- APIs:
  - WeatherAPI
  - OpenStreetMap
  - NewsAPI

## Installation

### Prerequisites

- Ensure you have a modern web browser (Chrome, Firefox, etc.) installed.
- Basic understanding of HTML, CSS, and JavaScript.

### Steps to Run the Application

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/edogola4/weather-app.git
   cd weather-app
   ```

2. **Open the HTML File:**
   Open `index.html` in your preferred web browser. You can simply double-click the file or open it via the browser's file menu.

3. **API Keys:**
   - Sign up for [WeatherAPI](https://weatherapi.com/) and [NewsAPI](https://newsapi.org/) to obtain your API keys.
   - Replace the `apiKey` variable in the JavaScript file with your actual API keys.

4. **Live Server (Optional):**
   If you have a local server setup (like using VS Code Live Server extension), you can run the app on a local server for better performance.

## Usage

- **Get Current Weather:**
  - Upon loading, the app will fetch the user's location and display the current weather conditions automatically.
  - Users can also enter a specific city in the input field and click the search button to get weather data for that location.

- **View Local Time:**
  - The app displays the current local time, which updates every second.

- **Weather Forecast:**
  - You can select a date range to view historical weather data.

- **News Section:**
  - Displays the latest articles related to the weather. Users can click on any article to read more.

## Code Explanation

### HTML Structure

The main HTML structure consists of the following sections:

- **Header Section:** Contains the title and navigation elements.
- **Weather Display Section:** Displays current weather conditions, including temperature, location, and weather icon.
- **Map Section:** Interactive map using Leaflet.js to show the user's location.
- **News Section:** Displays trending news articles with images, titles, and descriptions.

### JavaScript Functionality

The JavaScript file handles the following tasks:

- **Geolocation:** Retrieves the user's location using the Geolocation API.
- **Weather Data Fetching:** Makes API calls to the WeatherAPI to fetch current weather conditions and forecasts based on the user's input or location.
- **Map Initialization:** Uses Leaflet.js to display a map and place a marker at the user's location.
- **News Fetching:** Retrieves trending news articles related to weather from the NewsAPI and populates them into the news section.

## Contributing

Contributions to the project are highly encouraged. If you have suggestions for enhancements or wish to report issues, please submit a pull request or open an issue on the repository. If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (e.g., `feature-branch`).
3. Make your changes and commit them.
4. Push your changes to your forked repository.
5. Create a pull request.


## License

This project does not currently have a specified license. Users are free to utilize and modify the application as needed.

## Acknowledgments

I extend my gratitude myself as a contributor and users for their valuable feedback and support.

- [WeatherAPI](https://weatherapi.com/)
- [NewsAPI](https://newsapi.org/)
- [OpenStreetMap](https://www.openstreetmap.org/)
- [Leaflet.js](https://leafletjs.com/)

