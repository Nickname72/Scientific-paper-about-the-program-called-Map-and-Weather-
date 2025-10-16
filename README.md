

**List of Libraries:**

  * `pyqt5`
  * `pyqtwebengine`
  * `geopy`
  * `folium`
  * `requests`
  * `serpapi`

-----

## 🚀 Setup and Launch Requirements

To ensure the program runs correctly and displays all features, **you must** take the following actions:

### 1. Obtain and Configure API Keys

You need to insert your personal keys directly into the relevant variables in the code:

* **OpenWeatherMap Key:** You must insert this into the `OPENWEATHERMAP_API_KEY` variable so the program can fetch weather data.
* **SerpAPI Key:** You must insert this into the `SERPAPI_KEY` variable so your AI Assistant can perform real-time Google searches.

*(**Important:** Without these keys, you won't see the current weather or be able to use the AI assistant features).*

### 2. Create the Backgrounds Folder

You need to create a folder named **`backgrounds`** in the same directory as your Python file and place images inside it for the dynamic background:

* `clear*.jpg` (for clear weather)
* `clouds*.jpg` (for cloudy weather)
* `rain*.jpg` (for rain)
* `storm*.jpg` (for storms)
* `snow*.jpg` (for snow)

*(This is necessary for the application to have a beautiful, dynamically changing background).*

### 3. Ensure Internet Connection

You must ensure that your computer has an active Internet connection, as the program constantly interacts with various external services (weather, geocoding, translation, and search APIs).
