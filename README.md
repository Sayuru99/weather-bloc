# Weather Bloc Flutter Project

This Flutter project is designed to demonstrate the implementation of the Bloc (Business Logic Component) architecture for managing state in a weather application.

## Overview

The project utilizes Bloc architecture to separate business logic from UI components, making the codebase easier to understand, test, and maintain. Bloc architecture consists of three main components:

1. **Events**: Represent user actions or interactions that trigger state changes. In this project, events such as fetching weather data based on the user's location are defined.

2. **States**: Represent the different states of the application. These states are emitted by the Bloc in response to events. Examples of states include loading, success, and failure states when fetching weather data.

3. **Bloc**: Acts as a mediator between the UI and the data layer. It processes events, updates states, and provides streams of states to the UI. The Bloc in this project handles fetching weather data and manages the state of the weather information.

## Key Features

- **Weather Data**: Utilizes the Geolocator and Weather packages to fetch real-time weather data based on the device's location.
- **UI Rendering**: Renders weather information on the HomeScreen widget based on the state emitted by the WeatherBloc.
- **Dynamic Greeting**: Displays a dynamic greeting message based on the current time of day.
- **Weather Icons**: Shows weather icons corresponding to the current weather condition.
- **Sunrise and Sunset**: Displays the sunrise and sunset times based on the retrieved weather data.

## Getting Started

To run the project locally, follow these steps:

1. Ensure you have Flutter SDK installed on your machine. If not, follow the [Flutter installation guide](https://flutter.dev/docs/get-started/install).

2. Clone this repository to your local machine:

   ```
   git clone https://github.com/your-username/weather_bloc_flutter.git```
3. Install dependeciesy:

```flutter pub get```  

4. Run the app  
```flutter run```
