# SCREL's Flutter Machine Test


Design & build an app to provide users with real-time weather information based on their location. It fetches weather data from the OpenWeatherMap API and displays it in a user-friendly and visually appealing interface. The app also includes appropriate weather icons (images) to give users a clear understanding of the current weather conditions.

### Instructions

- Get the weather information based on the user's current location.
- Display current weather conditions, temperature, and more.
- Show an appropriate ```weather image and icon```.
- Utilize the ```Provider and Freezed``` packages for state management and data modeling.
- Implement a user-friendly and visually appealing ```UI/UX```.
- Provide a great ```app name and a beautiful logo```.

## Usage

- When you open the app, it will request permission to access your location. Grant the permission to get weather information based on your current location.
- The app will fetch weather data from the OpenWeatherMap API and display it on the main screen.
- The main screen displays the current temperature, weather conditions, and an appropriate weather image (Probably as full screen background)
- To refresh the weather data, simply pull down on the main screen.
- You can explore more weather details by tapping on the displayed weather information.

## API

We used the OpenWeatherMap API to retrieve weather data. The endpoint we utilized is as follows:

- API Endpoint: `https://api.openweathermap.org/data/2.5/weather?lat={latitude}&lon={longitude}&appid={api_key}&units=metric`
- KEY : ```15f958d72a82ae04f2b70568b2a8e082```
NOTE : If the provided key doesn't work, you can try creating an account at OpenWeatherMap and generate a new key. It's free.


## Design inspiration
https://dribbble.com/tags/weather%20app


# To begin, follow these steps:

1. Start by creating a Flutter project.
2. Once your task is finished, upload all your code to your GitHub account with appropriate commit messages.
3. Make sure your repository is public.
4. Share the project's GitHub link with us & Build APK and share with us



