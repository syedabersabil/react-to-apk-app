# React to APK App

This is a basic React.js app set up for conversion to an Android APK using Capacitor.

## Setup Instructions

1. Clone this repository to your local machine and install dependencies:
   ```sh
   npm install
   ```
2. Build the React app:
   ```sh
   npm run build
   ```
3. Initialize Capacitor:
   ```sh
   npm run cap:init
   ```
   (Press Enter to accept default values if prompted)
4. Add Android support:
   ```sh
   npm run cap:add:android
   ```
5. Copy your build to the Android project:
   ```sh
   npm run cap:copy
   ```
6. Open in Android Studio:
   ```sh
   npm run cap:open:android
   ```
7. Build your APK from Android Studio (Build > Build APK(s)).

---

You now have a React.js app that can be built as an APK for Android devices!
