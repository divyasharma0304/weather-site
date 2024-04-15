## Weather Website

**Project Overview**

This is a fully functional weather website built using HTML, CSS, and JavaScript. It allows users to retrieve weather details for a specific city or their current location.

**Features:**

* **Search by City Name:** Enter a city name in the provided field to get weather information.
* **Current Location Weather:** Click the "Get Device Location" button to display weather data based on your device's location (requires browser permission).
* **Error Handling:** An error message is displayed for invalid city names.
* **Weather Details:** Provides comprehensive weather information including:
    * Temperature (°C)
    * Weather Conditions (e.g., sunny, rainy, cloudy)
    * Location Name
    * Feels Like Temperature
    * Humidity
      
![image](https://github.com/divyasharma0304/weather-site/assets/108946390/2b4b9357-18f4-477e-90af-664d12382810)
![image](https://github.com/divyasharma0304/weather-site/assets/108946390/de80e7d4-c1f5-4728-9021-1ee09575d53a)
![image](https://github.com/divyasharma0304/weather-site/assets/108946390/837bd43d-6038-4346-9547-93152a8b7858)
![image](https://github.com/divyasharma0304/weather-site/assets/108946390/8d425357-a7f2-45c3-8dfa-9327bbdb8fc5)
![image](https://github.com/divyasharma0304/weather-site/assets/108946390/b98af22b-e232-4c3b-af73-7b96f32b82ad)
![image](https://github.com/divyasharma0304/weather-site/assets/108946390/a403e623-e96d-464d-af5c-303e61319460)

**Data Source:**

The project utilizes the OpenWeatherMap API to fetch weather data based on user input or device location.

**Project Structure:**

The website consists of three main files:

1. **index.html:** Defines the HTML layout of the webpage elements.
2. **style.css:** Contains CSS styles for visual design and formatting.
3. **script.js:** Implements JavaScript code for functionality:
    * Retrieves user-entered city name.
    * Sends a GET request to the OpenWeatherMap API with the city name.
    * Handles "Get Device Location" button click:
        * Checks for browser geolocation support.
        * If supported, retrieves user's device location (latitude & longitude).
        * Sends coordinates to the OpenWeatherMap API.
    * Processes response data from the API and populates relevant HTML elements.
    * Displays weather icons based on weather conditions using the API's provided ID.

**Getting Started (Optional)**

1. Clone this repository.
2. Install any required dependencies (if applicable).
3. Open `index.html` in your web browser to run the application.

**Note:**

This README provides a general overview. Additional details or instructions specific to running the project might be included depending on your setup.
