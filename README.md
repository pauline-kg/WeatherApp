# Weather App

A React Native mobile app that shows current weather conditions and a 5-day forecast for cities worldwide, using real-time data from the OpenWeatherMap API.

**Team:** Weather Peeps
**Course:** SODV2205-02 – Mobile Application Development with React Native I, Bow Valley College
**Instructor:** Mahbub Murshed

---

## Preliminary

### Project Overview

Provide users with current weather conditions and short-term forecasts for cities worldwide using real-time weather data from a third-party API.

### User Stories

- As a user, I want to search for a city so that I can view its current weather information.
- As a traveler, I want to view weather conditions for different cities so that I can plan my activities.
- As a user, I want to see a multi-day weather forecast so that I can prepare for upcoming weather changes.
- As a user, I want weather information displayed with icons and clear formatting so that it is easy to understand.

### Main Features

- Search for weather information by city name
- View current conditions: temperature, humidity, wind speed, and weather description
- View a 5-day weather forecast
- Weather icons and images based on current conditions
- Navigation between the Home, Current Weather, and Forecast screens
- Error messages when a city cannot be found or the API request fails

### API Used

**[OpenWeatherMap API](https://openweathermap.org/api)** – retrieves real-time weather information and forecasts.

| Purpose         | Endpoint                                           |
| --------------- | -------------------------------------------------- |
| Current weather | `https://api.openweathermap.org/data/2.5/weather`  |
| 5-day forecast  | `https://api.openweathermap.org/data/2.5/forecast` |

### Screens

| Screen          | Contents                                                      |
| --------------- | ------------------------------------------------------------- |
| Home / Search   | Search bar, popular cities, recent searches                   |
| Current Weather | Current conditions, weather icon, temperature, humidity, wind |
| Forecast        | 5-day forecast                                                |

### Technologies

| Technology              | How it is used                                                                     |
| ----------------------- | ---------------------------------------------------------------------------------- |
| **Axios**               | Sends requests to the API and retrieves the weather information                    |
| **useState**            | Stores the city name, weather data, and loading/error states                       |
| **useEffect**           | Runs API calls when a search is performed and updates the UI when new data arrives |
| **useReducer**          | Manages loading, success, and error states along with the weather data             |
| **React Navigation**    | Moves users between screens                                                        |
| **FlatList**            | Renders each forecast day as a list item                                           |
| **Reusable Components** | `Header`, `SearchBar`, `WeatherCard`, `LoadingIndicator`                           |
| **Flexbox**             | Responsive, organized screen layouts                                               |

### Wireframes

|                                   Home / Search                                    |                                          Current Weather                                          |                                      Forecast                                       |
| :--------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------: |
| <img width="461" height="710" alt="Screen1" src="https://github.com/user-attachments/assets/db1b453d-9a63-45e1-bd81-9bfc6a075461" />
| 
| <img width="461" height="717" alt="Screen3" src="https://github.com/user-attachments/assets/91cba374-168e-4d49-97d8-7c180f4dc047" />
 |<img width="470" height="722" alt="Screen2" src="https://github.com/user-attachments/assets/c2068d4c-33f0-4558-a28f-bc53af734b1f" />

---

## Contributions / Responsibilities

| Team Member   | Responsibilities                               |
| ------------- | ---------------------------------------------- |
| Pauline Guiao | \_TODO: screen1, Reusable Components, FlatList |
| Sweeny Tan    | _TODO: screens2-3, API integration_            |

---

## Development Timeline

| Phase                   | Date         | Milestone                                                       | Status |
| ----------------------- | ------------ | --------------------------------------------------------------- | ------ |
| Proposal                | Nov 18, 2026 | Phase 1 proposal submitted (features, screens, API, wireframes) | Done   |
| Setup                   | _TODO_       | Project created, dependencies installed, API key configured     |        |
| Core build              | _TODO_       | Search, API calls (Axios), and Current Weather screen           |        |
| Forecast and navigation | _TODO_       | 5-day forecast with FlatList, React Navigation between screens  |        |
| Polish and testing      | _TODO_       | Weather icons, error handling, layout cleanup                   |        |
| Final submission        | _TODO_       | Final code and README on GitHub                                 |        |
