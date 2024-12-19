# Weather Forecast Application

This is a **Weather Forecast** application built using **Python** and the **Tkinter** library for creating the graphical user interface (GUI). The app uses the **OpenWeatherMap API** to fetch real-time weather data and display it for a user-specified city.

## Features
- Enter the name of a city to get the current weather details.
- Displays:
  - Temperature (in Kelvin)
  - Weather description (e.g., sunny, cloudy)
  - Humidity
  - Minimum and maximum temperatures
- Error handling for invalid city names or failed API requests.
- User-friendly interface built with **Tkinter**.

## Libraries Used
- **Tkinter**: For creating the GUI of the application.
- **Requests**: To make HTTP requests to the OpenWeatherMap API and fetch weather data.
- **OpenWeatherMap API**: Provides real-time weather data.

## How the Application Works

### 1. **User Input**
- The user enters the name of a city in the provided text entry field.

### 2. **Weather Data Fetching**
- Once the user clicks the **Submit** button, the `weather()` function is called.
- The city name entered by the user is used to make an API request to the OpenWeatherMap API.
- The API returns weather data, including:
  - Temperature
  - Weather description
  - Humidity
  - Minimum and maximum temperatures

### 3. **Displaying Data**
- If the API call is successful (status code 200), the data is displayed in the `Text` widget.
- If the city name is invalid or the API request fails, an error message is shown.

### 4. **Error Handling**
- The application checks if the user has entered a city name. If the input is empty, a warning message is displayed.
- If the API request fails, the application displays an error message asking the user to check the city name.

### 5. **Temperature Units**
- The temperature is displayed in **Kelvin**. You can modify the API call to display the temperature in **Celsius** or **Fahrenheit** as per your preference.
