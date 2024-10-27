# Pin-Drop-with-Remarks-Functionality

A user-friendly tool that allows users to drop pins on a map, enter remarks, and automatically fetch the address for the pin location using OpenStreetMap's Nominatim API. The saved pins are viewable in a list format and persist across sessions using local storage.

FEATURES
Interactive Map Interface: Built using Leaflet.js, the map allows for easy navigation and pin dropping.
Pin Drop Functionality: Users can click anywhere on the map to drop a pin, triggering a popup to add optional remarks.
Automatic Address Fetching: The tool retrieves the address based on pin latitude and longitude using Nominatim API (bonus feature).
Save and View Pins: Saved pins are displayed in a sidebar with remarks and addresses for easy access.
Pin Navigation: Clicking on a saved pin in the sidebar re-centers the map on that location and highlights the pin.
Local Storage Persistence: All pin data, including addresses and remarks, is stored in local storage, retaining data across sessions.

PROJECT STRUCTURE
HTML, CSS, and JavaScript: The core project is written in plain HTML, CSS, and JavaScript with no backend. The Leaflet.js library is used for map functionality.

SETUP AND USAGE
Prerequisites
Internet Connection: The project requires an internet connection to load the Leaflet library and OpenStreetMap tiles.
Web Browser: A modern web browser that supports local storage and JavaScript.
Installation
Clone the repository or download the HTML file.
Open the HTML file in your browser.

HOW TO USE
Map Interface: Navigate the map using zoom and pan controls.
Drop a Pin: Click on any location on the map. A popup will appear where you can:
View the automatically fetched address (if available).
Enter any remarks about the pin.
Save the Pin: Click the Save Pin button to save the pin, address, and remarks.
View Saved Pins: Saved pins are listed in the sidebar.
Navigate to a Pin: Click on any saved pin in the sidebar to re-center the map on that pin.
