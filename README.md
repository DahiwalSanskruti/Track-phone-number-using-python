**Phone Number Geolocation**

This project allows you to geolocate a phone number by retrieving its approximate location and service provider information. The location is then displayed on an interactive map.

**Features**

-Parse and validate phone numbers with country codes.
-Retrieve and display the geographical location of the phone number.
-Identify the service provider of the phone number.
-Generate an interactive map with the location marked.

**Dependencies**

-phonenumbers: Library for parsing, formatting, and validating phone numbers.
-folium: Python wrapper for Leaflet.js to create interactive maps.
-opencage: Python client for the OpenCage Geocoding API.

**Required Python packages:**

-pip install phonenumbers folium opencage[for windows]

**Usage**

1. Replace the key variable with your OpenCage Geocode API key.
2. Run the script: "filename".py
3. Enter the phone number with the preceding country code when prompted.
4. The script will output the location and service provider of the phone number.
5. An interactive map will be saved as mylocation.html with the phone number's location marked.

**Example**

Enter the phone number with preceding country code please: +14155552671
California
AT&T Mobility
37.7749 -122.4194

The resulting map (mylocation.html) will display a marker at the coordinates of the location.
