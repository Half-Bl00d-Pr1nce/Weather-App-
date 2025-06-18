# Python Weather App

## Overview  
This desktop Weather App is built with Python and PyQt5, integrating the OpenWeatherMap API to provide real-time weather information for any city. The application features a user-friendly graphical interface, robust error handling, and clear weather data visualization.

---

## Features  

- **Real-Time Weather Data**: Instantly fetches and displays current weather conditions for user-specified cities.
- **PyQt5 GUI**: Responsive and intuitive desktop interface.
- **Custom UI Styling**: Designed for clarity and ease of use.
- **Comprehensive Error Handling**: User-friendly messages for invalid input or network/API issues.
- **Input Validation**: Prevents invalid city names and duplicate requests.

---

## Screenshots  
![Screenshot 2025-06-18 161142](https://github.com/user-attachments/assets/b35d5fc8-5377-4588-b9bc-6701fb30c749)

![Screenshot 2025-06-18 161123](https://github.com/user-attachments/assets/49ca43ea-984a-449a-98e9-4847426b3edf)





---

## Installation  

1. **Clone the repository** : git clone https://github.com/Half-Bl00d-Pr1nce/Weather-App-.git 
2. **Navigate to the project directory** : cd Weather-App-
3. **Install dependencies** : pip install -r requirements.txt


---

## Usage  

1. **Obtain an API Key**  
- Register at [OpenWeatherMap](https://openweathermap.org/api) to get a free API key.

2. **Configure the API Key**  
- Open `main.py` and insert your API key where indicated:
  ```
  API_KEY = "your_api_key_here"
  ```

3. **Run the application**  

4. **Using the App**  
- Enter a city name in the input field.
- Click the "Get Weather" button to view current weather details.
- Error messages will appear for invalid inputs or connectivity issues.

---

## Future Improvements  

- Add multi-day weather forecasts.
- Integrate location auto-detection.
- Enhance UI with theming and animations.
- Package as a standalone desktop executable.

---

## Acknowledgements  

- Weather data powered by [OpenWeatherMap](https://openweathermap.org/)
- GUI built with [PyQt5](https://riverbankcomputing.com/software/pyqt/)

---





