**WeatherApp**

WeatherAppTest is a simple Android application that provides the current weather, temperature, and humidity for a specified location. The app uses the OpenWeatherMap API to fetch weather data and displays the current time, location, address, and weather information. Users can search for a location using the search bar, and the app saves and loads the last searched city for a seamless user experience. It uses java language and Kotlin DSL.

**Note**

The app will not load your location until you search for a city.

**Features**

•	Display current weather, temperature, and humidity for the user's location.
•	Search for weather information by city name.
•	Save and load the last searched city on app restart.
•	Show current system time.
•	Display the address of the current location.
•	Use of FusedLocationProviderClient for location services.
•	Fetch weather data from the OpenWeatherMap API.
•	User-friendly UI with cards to display weather information.

**Setup Instructions**

**Prerequisites**

•	Android Studio
•	A device or emulator running Android API level 34 or higher
•	An active internet connection

**Project Structure**

•	MainActivity.java: The main activity that handles location updates and displays weather information.
•	activity_main.xml: The layout file for the main activity, including TextViews and CardViews for displaying weather data.
•	AndroidManifest.xml: The manifest file declaring necessary permissions and application components.
•	build.gradle: Gradle configuration files for project dependencies and settings.

**Dependencies**

•	com.google.android.gms:play-services-location: For accessing location services.
•	com.squareup.okhttp3:okhttp: For making HTTP requests.
•	com.google.code.gson:gson: For parsing JSON responses.
•	AndroidX libraries for UI components and compatibility.

**Permissions**
•	INTERNET: To fetch weather data from the OpenWeatherMap API.
•	ACCESS_FINE_LOCATION: To access precise location data.
•	ACCESS_COARSE_LOCATION: To access approximate location data.
These permissions are declared in the AndroidManifest.xml file.
