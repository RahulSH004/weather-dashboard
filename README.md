# Weather Dashboard

![Weather Dashboard Screenshot](image/screenshot.png) <!-- Update the path based on where you place the screenshot -->

A visually appealing and responsive weather dashboard application that provides real-time weather information and dynamically updates background videos based on the current weather conditions and time of day. This project is built using HTML, CSS, and JavaScript, and utilizes various APIs for fetching weather data and background videos.

## **Table of Contents**

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [APIs Used](#apis-used)
- [Installation](#installation)
- [Usage](#usage)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## **Overview**

Check out the live website here: [My Website](https://weather-dashboard-lq35qkttb-rahul-singh-s-projects-3662b08b.vercel.app/)
The Weather Dashboard is a user-friendly web application that allows users to search for weather information in any city. It provides current weather details, including temperature, humidity, wind speed, air quality, and UV index. The application also dynamically updates background videos based on the weather conditions and whether it is daytime or nighttime in the searched city.

## **Features**

- **Real-Time Weather Data**: Fetches and displays the current weather conditions for any city worldwide.
- **Dynamic Background Videos**: Changes background videos based on the current weather conditions and time of day (nighttime feature).
- **Responsive Design**: Works seamlessly on various devices, including desktops, tablets, and smartphones.
- **User-Friendly Interface**: Simple and intuitive interface for easy navigation and user experience.
- **7-Day Forecast**: Displays a 7-day weather forecast for the searched city.
- **Additional Weather Details**: Provides information on humidity, wind speed, air quality index (AQI), UV index, and precipitation probability.

## **Technologies Used**

- **HTML5**: For the structure of the web application.
- **CSS3**: For styling and layout.
- **JavaScript**: For the application's logic, fetching data, and handling user interactions.
- **API Integration**: For fetching real-time weather data and background videos.
- **Vercel/Netlify**: (Optional) For deploying the web application.

## **APIs Used**

- **Weather API**: [WeatherAPI](https://www.weatherapi.com/)
  - Used to fetch current weather conditions, 7-day forecasts, and additional weather details (e.g., humidity, wind speed).
  - Provides local time for the searched city, which is used to determine day or night.
  
- **Astronomy API**: Part of WeatherAPI
  - Provides sunrise and sunset times to help determine the current time of day.
  
- **Pexels Video API**: [Pexels API](https://www.pexels.com/api/)
  - Used to fetch high-quality videos based on the current weather condition and time of day (e.g., night rain, sunny day).

## **Installation**

To run the Weather Dashboard locally, follow these steps:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/weather-dashboard.git
    cd weather-dashboard
    ```

2. **Obtain API Keys**:
   - Sign up for API keys from the following services:
     - [WeatherAPI](https://www.weatherapi.com/)
     - [Pexels API](https://www.pexels.com/api/)
   - Replace placeholders in the JavaScript files with your actual API keys.

3. **Open the Project**:
   - Open `index.html` in your web browser to see the application in action.

## **Usage**

- **Search for a City**: Use the search bar to enter the name of any city.
- **View Weather Information**: The dashboard will display current weather details, including temperature, weather conditions, humidity, wind speed, air quality index, and UV index.
- **Dynamic Background**: If it's nighttime in the searched city, the background video will change to reflect the weather conditions (e.g., rainy night, clear night).
- **7-Day Forecast**: Check the weekly forecast for the selected city.

## **Deployment**

The Weather Dashboard can be deployed using various platforms. Below are some options:

### Deploying with GitHub Pages

1. **Push your project to a GitHub repository**.
2. **Enable GitHub Pages** under the repository settings.
3. **Select the main branch** as the source.
4. Your site will be available at `https://yourusername.github.io/weather-dashboard`.


## **Contributing**

Contributions are welcome! If you would like to improve this project, please fork the repository and submit a pull request with your changes.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/NewFeature`)
3. Commit your Changes (`git commit -m 'Add new feature'`)
4. Push to the Branch (`git push origin feature/NewFeature`)
5. Open a Pull Request

## **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## **Acknowledgments**

- **WeatherAPI**: For providing real-time weather data and forecasts.
- **Pexels**: For providing high-quality videos for dynamic backgrounds.
- **Vercel**: For providing an easy-to-use deployment platform.
- **Netlify**: For hosting static sites and serverless functions.
- **GitHub Pages**: For simple static site hosting.

## **Links**

- [WeatherAPI Documentation](https://www.weatherapi.com/docs/)
- [Pexels API Documentation](https://www.pexels.com/api/documentation/)
- [GitHub Pages](https://pages.github.com/)
- [Vercel](https://vercel.com/)
- [Netlify](https://www.netlify.com/)
