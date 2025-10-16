Site - https://map-and-weather-webs-jj4u.bolt.host

LIBRARIES:

1. pyqt5
2. pyqtwebengine
3. geopy
4. folium
5. requests
6. serpapi

1. Obtain and Set Up API Keys:
  ‣ I need my personal OpenWeatherMap API key. I must insert this into the OPENWEATHERMAP_API_KEY variable in the code so the application can fetch weather data.
  ‣ I need my SerpAPI key. I must insert this into the SERPAPI_KEY variable so that my AI Assistant can perform real-time searches on Google.
  (Without these keys, I will not see the current weather or be able to use the AI assistant features).

2. Create the Backgrounds Folder:
  ‣ I need to create a folder named backgrounds in the same directory as my Python file.
  ‣ I must place at least one image in this folder for each weather type, using the corresponding names to start the filename:
    • clear*.jpg (for clear weather)
    • clouds*.jpg (for cloudy weather)
    • rain*.jpg (for rain)
    • storm*.jpg (for storms)
    • snow*.jpg (for snow)
(This is necessary for the application to have a beautiful, dynamically changing background).

3. Ensure Internet Connection:
  • I must make sure my computer has an active Internet connection,
  as the program constantly interacts with various external services 
  (weather, geocoding, translation, and search APIs).
