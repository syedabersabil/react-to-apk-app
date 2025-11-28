# React to APK App

This is a React.js app that automatically builds an Android APK using GitHub Actions.

## 🚀 Automatic APK Build

Every time you push code to the `main` branch, GitHub Actions will automatically:
1. Build your React app
2. Set up Capacitor with Android support
3. Build an APK file
4. Create a new release with the APK attached

### Download Your APK

- Go to the [Actions tab](https://github.com/syedabersabil/react-to-apk-app/actions) to see builds in progress
- Once complete, download the APK from the **Artifacts** section
- Or check the [Releases page](https://github.com/syedabersabil/react-to-apk-app/releases) for tagged releases with APK files

## 🛠️ Local Development Setup

1. Clone this repository:
   ```sh
   git clone https://github.com/syedabersabil/react-to-apk-app.git
   cd react-to-apk-app
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

3. Run the development server:
   ```sh
   npm start
   ```

4. Build for production:
   ```sh
   npm run build
   ```

## 📱 Manual APK Build (Optional)

If you want to build locally:

1. Build the React app:
   ```sh
   npm run build
   ```

2. Initialize Capacitor (if not done):
   ```sh
   npx cap init react-to-apk-app com.example.reacttoapkapp --web-dir=build
   ```

3. Add Android platform:
   ```sh
   npx cap add android
   ```

4. Copy web assets:
   ```sh
   npx cap copy android
   ```

5. Open in Android Studio:
   ```sh
   npx cap open android
   ```

6. Build APK from Android Studio: **Build > Build Bundle(s) / APK(s) > Build APK(s)**

## 🎯 Features

- ✅ Automatic APK builds via GitHub Actions
- ✅ React.js web app
- ✅ Capacitor for native Android integration
- ✅ Release management with version tagging

---

**Made with ❤️ using React + Capacitor + GitHub Actions**
