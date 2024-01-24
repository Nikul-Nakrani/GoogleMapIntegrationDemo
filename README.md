# Google Map Integration Demo for Android

This Android application demonstrates the integration of Google Maps with various map types (Hybrid, Satellite, Terrain, and Normal) and the use of markers. The app also features live location updates on the map with the necessary location permissions.

## Features

- Google Maps integration with different map types: Hybrid, Satellite, Terrain, and Normal.
- Marker functionality to mark specific locations on the map.
- Live location updates to display the user's current location on the map.

## Prerequisites

Before running the app, make sure you have:

- Android Studio installed on your development machine.
- A valid Google Maps API key. You can obtain one from the [Google Cloud Console](https://console.cloud.google.com/).

## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/Nikul-Nakrani/GoogleMapIntegrationDemo.git
    ```

2. Open the project in Android Studio.

3. Add your Google Maps API key in the `google_maps_api.xml` file. Replace `"YOUR_API_KEY"` with your actual API key.

    ```xml
    <!-- app/src/debug/res/values/google_maps_api.xml -->
    <string name="google_maps_key" templateMergeStrategy="preserve" translatable="false">YOUR_API_KEY</string>
    ```

4. Build and run the app on an Android device or emulator.

## Usage

- Choose the desired map type from the options provided.
- Use the marker functionality to mark specific locations on the map.
- Grant location permissions to enable live location updates.

## Contributing

Feel free to contribute to the project by opening issues or creating pull requests.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- The project is inspired by the Google Maps API documentation.
- Special thanks to contributors.

**Happy Coding!!!**
