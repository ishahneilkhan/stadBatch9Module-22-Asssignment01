# OstadBatch9Module-22
Google Maps and Geolocator
A Flutter application that integrates Google Maps and Geolocator to provide real-time tracking of the user's location with smooth animation, polyline tracking, and interactive markers.

🧪 Assignment Objective
This app demonstrates:

📍 Automatic map animation to the user's location

🔄 Real-time location updates every 10 seconds

📈 Polyline tracking of movement

ℹ️ Interactive marker info window showing location data

🛠 Features
✅ 1. Automatic Map Animation
On app launch, the map automatically animates and centers to the user's current location.

✅ 2. Real-Time Location Updates
Location is updated every 10 seconds.

The marker moves with each update to show real-time movement.

✅ 3. Polyline Tracking
As the user's location changes, a polyline is drawn between the previous and current points.

Continues to build a path as the user moves.

✅ 4. Marker Information Window
Tapping the marker shows an info window.

Title: My current location

Snippet: Current latitude and longitude

📦 Packages Used
Package	Description
google_maps_flutter	Embeds Google Maps in the Flutter app
geolocator	Gets real-time device location
permission_handler	Requests and handles runtime permissions
