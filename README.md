# OstadBatch9Module-22
google_map
A new Flutter project.

Getting Started
This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

Lab: Write your first Flutter app
Cookbook: Useful Flutter samples
For help getting started with Flutter development, view the online documentation, which offers tutorials, samples, guidance on mobile development, and a full API reference.

This project demonstrates:

* 📍 **Automatic Map Animation** to the user's current location
* 🔄 **Real-Time Location Updates** every 10 seconds
* 📈 **Polyline Tracking** between previous and current locations
* ℹ️ **Marker Info Window** with location data

---

## 🛠 Features

### ✅ 1. Automatic Map Animation

* On app launch, the map animates and centers to the user's current position.

### ✅ 2. Real-Time Location Updates

* Location updates every 10 seconds.
* Marker position updates in real time.

### ✅ 3. Polyline Tracking

* A polyline connects the movement path between locations.
* Continuously updated as the user moves.

### ✅ 4. Marker Info Window

* Tapping the marker shows:

  * Title: `My current location`
  * Snippet: `Latitude` and `Longitude`

---

## 📦 Packages Used

| Package               | Description                              |
| --------------------- | ---------------------------------------- |
| `google_maps_flutter` | Embeds Google Maps in the Flutter app    |
| `geolocator`          | Provides real-time device location       |
| `permission_handler`  | Requests and manages runtime permissions |

---

## 🚀 Getting Started

### Prerequisites

* Flutter SDK installed
* Android/iOS emulator or real device
* A valid Google Maps API Key

### Installation

```bash
git clone https://github.com/your-username/google_maps_tracker.git
cd google_maps_tracker
flutter pub get
flutter run
```

### Add API Key

Update your `AndroidManifest.xml` with your Google Maps API key:

```xml
<meta-data android:name="com.google.android.geo.API_KEY"
           android:value="YOUR_API_KEY_HERE"/>
```

---

## 📸 Screenshots

(Add screenshots here if needed)

---

## 📝 License

This project is for educational purposes.
Feel free to customize and extend!

