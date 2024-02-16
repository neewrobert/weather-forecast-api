# Java Weather Forecast Application Challenge

## Overview
This challenge is designed to help beginners learn about interacting with APIs in Java by building a simple weather forecast application. You will use the WeatherAPI to fetch weather data for a specified city. This project will introduce you to making HTTP requests, parsing JSON responses, and integrating this data into a Java application.

## Objectives
Your application should be able to:
1. **Request User Input**: Create an GET endpoint for the users to get a forecast for a city
2. **Send API Request**: Make an HTTP GET request to the WeatherAPI with the city name as a parameter.
3. **Parse API Response**: Parse the JSON response from the API.
4. **Display Weather Information**: Extract and display data such as temperature, weather conditions, and humidity.
5. **Error Handling**: Implement error handling for invalid inputs or API errors.
6. **(Optional) Enhancements**: Allow specifying units (metric/imperial) for temperature, implement caching.


## Getting Started

### Step 1: Sign Up for WeatherAPI
1. Visit [WeatherAPI](https://www.weatherapi.com/) and create an account.
2. Obtain your API key after registration. (it's free)

### Step 2: Setup Your Java Project
1. Create a new Java project in your preferred IDE.
2. Use Spring boot

### Step 3: Implement the Application
1. A get endpoint for the user/front-end select a city
2. Make GET request to WeatherAPI with the user's city.
3. Parse the JSON response using a suitable JSON library.
4. Extract the necessary weather information and display it to the user.
5. Add error handling for various edge cases (e.g., invalid city, API limits).

## Tips for Success
- Review the WeatherAPI documentation to understand the API request and response formats.
- Start with basic functionality and gradually add more features, such as error handling and unit selection.
- Test your application with different cities to ensure it handles various scenarios gracefully.
- Implement unit test
- Implement integration tests

Good luck with your Java Weather Forecast Application Challenge!
