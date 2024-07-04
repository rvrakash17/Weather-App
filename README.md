# Weather App

## Short Description
An application for viewing the weather.

## Description
This application allows you to view the weather in your city. The following options are provided:

- **View Current Weather:** See the current weather conditions.
- **View Weather by Hour:** Check the weather forecast for each hour.
- **View Weather for the Week:** Get a weekly weather forecast.
- **View Detailed Weather Data:** Access comprehensive weather information.
- **Localization:** Available in multiple languages including Russian, English, Italian, German, French, Turkish, Portuguese, Spanish, Slovak, Dutch, Hindi, Romanian, Chinese, and Polish.
- **Data Caching:** Efficiently manage weather data for offline access.
- **Choose Your City:** Select and view weather data for any city.
- **Add Cards for Other Cities:** Add weather cards for multiple cities.
- **Metric/Imperial Units:** Switch between metric and imperial systems.
- **Temperature Units:** Choose between Celsius and Fahrenheit.
- **Time Formats:** Select between 12-hour and 24-hour time formats.
- **Notifications:** Receive weather notifications.
- **Design:** Aimed at providing a convenient and visually appealing user experience.

## Services Used
- **Weather Data:** The app receives weather data from [Open-Meteo](https://open-meteo.com).
- **City Search:** Cities are searched using Open-Meteo's service.

## Getting Started

### Prerequisites
- Flutter SDK installed

### Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/weather_app.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd weather_app
   ```
3. **Install dependencies:**
   ```bash
   flutter pub get
   ```

### Running the App
1. **Run the application:**
   ```bash
   flutter run
   ```

## Configuration
The project is configured to use several dependencies and services, including:
- **Dio** for network requests
- **Get** for state management
- **Isar** for local storage
- **Flutter Local Notifications** for notifications
- **Connectivity Plus** for network connectivity
- **Google Fonts** for custom fonts
- **Dynamic Color** for theme support
- **Path Provider** for file storage
- **Flutter Timezone** for time zone handling

## Localization
The app supports multiple languages. You can switch languages via the settings in the app.

## Author
- Akash R
