# Masjid Kita

A Flutter mobile application for browsing and exploring mosques in your area.

## Description

Masjid Kita is a Flutter-based mobile app that helps users discover mosques in the Pakisaji area of Malang, East Java. The app provides detailed information about each mosque including location, capacity, land area, building area, land status, and year established. Users can view mosques on an interactive map, browse through image carousels, and get directions via Google Maps.

### Key Features

- **Splash Screen** — Branded app launch experience
- **Mosque List** — Browse all mosques with search and distance-based sorting
- **Mosque Detail** — View comprehensive information about each mosque including images, address, capacity, and more
- **Interactive Map** — View mosque locations on a map using flutter_map
- **Distance Calculation** — Shows real-time distance from your current location to each mosque
- **Google Maps Integration** — Get directions to any mosque directly from the app
- **Image Carousel** — Swipe through mosque photos

## How to Install and Run the Project

### Prerequisites

- Flutter SDK (>= 3.7.2)
- Dart SDK
- Android Studio / VS Code
- A physical device or emulator with GPS capabilities

### Installation

```bash
# Clone the repository
git clone https://github.com/novalmaulana7/masjid-kita.git
cd masjid-kita

# Install dependencies
flutter pub get

# Run the app
flutter run
```

## How to Use the Project

1. **Launch the App** — Open the app to see the splash screen, which will automatically navigate to the mosque list.
2. **Browse Mosques** — Scroll through the list of mosques. Each card shows the mosque name, address, and distance from your location.
3. **Search & Sort** — Use the search bar to find a specific mosque by name. Mosques are sorted by distance from your current location.
4. **View Details** — Tap on any mosque card to view detailed information including capacity, land area, building area, land status, and year established.
5. **View on Map** — In the detail screen, tap the map section to view the mosque's exact location on an interactive map.
6. **Get Directions** — Tap the directions button to open Google Maps and get navigation to the mosque.

## Credits

- **novalmaulana** — Project owner and lead developer
- [Flutter](https://flutter.dev) — UI framework
- [flutter_map](https://github.com/fleaflet/flutter_map) — Map rendering
- [latlong2](https://pub.dev/packages/latlong2) — Coordinate handling
- [geolocator](https://pub.dev/packages/geolocator) — GPS location services
- [carousel_slider](https://pub.dev/packages/carousel_slider) — Image carousel widget
- [url_launcher](https://pub.dev/packages/url_launcher) — Opening URLs (Google Maps)
- [SIMAS Kemenag](https://simas.kemenag.go.id) — Mosque data source

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
