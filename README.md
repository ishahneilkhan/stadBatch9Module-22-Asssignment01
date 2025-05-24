# OstadBatch9Module-22
# Google Maps with Geolocator - Flutter Project

A clean and simple Flutter application that demonstrates the integration of **Google Maps** with **Geolocator** for real-time location tracking, marker animation, and polyline path drawing.

## Getting Started

This project is a great starting point if you’re learning how to work with maps and location services in Flutter.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.



##  Useful Resources

*  [Write Your First Flutter App](https://docs.flutter.dev/get-started/codelab)
*  [Flutter Cookbook](https://docs.flutter.dev/cookbook) – Handy code examples
*  [Flutter Documentation](https://docs.flutter.dev) – Full API references and guides

---

##  Features

*  Automatically animate the map to the user's location
*  Update location in real-time (every 10 seconds)
*  Draw polylines between previous and current location
*  Tap marker to show location info with latitude & longitude




## Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/google_map_flutter.git
   cd google_map_flutter
   ```

2. **Install dependencies**

   ```bash
   flutter pub get
   ```

3. **Add your Google Maps API Key**
   Open `android/app/src/main/AndroidManifest.xml` and add:

   ```xml
   <meta-data android:name="com.google.android.geo.API_KEY"
              android:value="YOUR_GOOGLE_MAPS_API_KEY"/>
   ```

4. **Run the app**

   ```bash
   flutter run
   ```
