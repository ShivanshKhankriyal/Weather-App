# Weather App Readme


Preview! ![Weather app](https://github.com/ShivanshKhankriyal/Weather-App/assets/96327360/9822281e-1764-4ccb-8dc3-2158e806a953)


## Introduction
This GitHub repository contains a simple weather app that provides real-time weather information using the OpenWeatherMap API. The app is built using HTML, CSS, and JavaScript. In this project, we've organized the code into different files for HTML and CSS while including the JavaScript directly within the HTML file to keep things simple. Additionally, all images used in the project are stored in a separate "images" folder within the repository.

## Project Structure

### HTML
- **index.html**: The main HTML file that serves as the entry point for the weather app. It contains the structure of the app's user interface and includes the JavaScript code for functionality.

### CSS
- **styles.css**: The main CSS file responsible for styling the weather app. It defines the layout, colors, and other visual elements of the user interface.

### Images
- **/images**: This folder contains all the images used in the project, such as weather icons and background images.

## Usage

To use the weather app, follow these steps:

1. Clone or download this repository to your local machine.

   ```
   git clone https://github.com/yourusername/weather-app.git
   ```

2. Open the `index.html` file in your web browser.

3. Enter the name of the city or location you want to check the weather for in the input field and click the "Search" button.

4. The app will display the current weather conditions, including temperature, humidity, and a weather icon for the specified location.

## API Key

Please note that this weather app uses the OpenWeatherMap API to fetch weather data. To make API requests, you will need to obtain an API key from the [OpenWeatherMap website](https://openweathermap.org/api) and replace the placeholder API key in the JavaScript code (`index.html`) with your own API key.

```javascript
// Replace 'YOUR_API_KEY' with your actual OpenWeatherMap API key
const apiKey = 'YOUR_API_KEY';
```

## Contributors

- Shivansh Khankriyal ((https://github.com/ShivanshKhankriyal)) - Lead Developer

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- Special thanks to [OpenWeatherMap](https://openweathermap.org/) for providing the weather data API.

Feel free to contribute, report issues, or make suggestions to improve this weather app! We hope you find it useful.
