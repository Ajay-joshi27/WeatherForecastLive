
# Weather App

## Overview

This is a simple weather application that retrieves and displays the current weather data for a specified location using the OpenWeatherMap API. The app features an intuitive interface with real-time updates.

## Features

- Displays current weather conditions, including temperature and description.
- Shows an icon representing the current weather.
- Refresh button to reload the weather data.

## Technologies Used

- HTML
- CSS
- JavaScript
- jQuery
- OpenWeatherMap API

## Getting Started

To run this application locally, follow these steps:

### Prerequisites

- A web browser (Chrome, Firefox, etc.)
- Internet connection (to fetch weather data)

### Installation

1. Clone this repository to your local machine:
   ```bash
   git clone <repository-url>
   ```
2. Open the `index.html` file in your web browser.

### Usage

1. The app will automatically fetch and display the weather for Gulbarga.
2. Click the refresh button to reload the weather data.

## Customization

To display weather for a different location, modify the following line in the JavaScript code:

```javascript
link="https://api.openweathermap.org/data/2.5/weather?q=gulbarga&appid=YOUR_API_KEY";
```

Replace `gulbarga` with your desired city name and `YOUR_API_KEY` with your OpenWeatherMap API key.

## Contributing

If you wish to contribute to this project, feel free to fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

- [OpenWeatherMap](https://openweathermap.org) for providing the weather API.
- [Font Awesome](https://fontawesome.com) for the icons used in the app.

---

Feel free to modify any sections or add additional details!
