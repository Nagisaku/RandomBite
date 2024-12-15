
# RandomBite

**RandomBite** is a mobile application developed as a class project. The app helps users simplify their dining decisions by providing a single, personalized restaurant suggestion based on customizable filters. The project uses modern technologies such as React Native, Expo, and Firebase to deliver a smooth and user-friendly experience.

---

## Features

- **Operation Platforms**: Android, iOS
- **Restaurant Recommendation**: Generates a single restaurant suggestion based on user-defined criteria like distance, availability, cuisine, pricing, and ratings.
- **Favorites and Blacklist**: Allows users to favorite restaurants and blacklist options they want to avoid in future suggestions.
- **User Profiles**: Tracks dining history, preferences, and visit plans.
- **Geolocation**: Suggests nearby restaurants using Google Places API.
- **Cross-Platform Compatibility**: Works on Android, iOS, and Web platforms.

---

## Tech Stack

- **Language**: JavaScript
- **Frontend**: React Native with Expo
- **Backend**: Firebase (Authentication, Firestore)
- **APIs**: Google Maps API, Google Places API
- **Navigation**: React Navigation

---

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/Nagisaku/RandomBite.git
   cd RandomBite
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Start the app:
   ```
   npx expo start
   ```

## Android

1. Download Expo Go from the Google Play Store.

2. Use the Expo Go > Scan QR Code > Scan the QR code generated by the `npx expo start` command.

## iOS

1. Download Expo Go from the App Store.

2. Use the camera to scan the QR code generated by the `npx expo start` command.


---

## Usage

1. **Log In**: Sign in using your account or create a new one.
2. **Set Preferences**: Define filters like distance, cuisine, and price to customize recommendations.
3. **Get Suggestions**: RandomBite will provide a single restaurant suggestion tailored to your criteria.
4. **Track History**: Access your dining history, favorite restaurants, and blacklist unwanted options.

---

## Folder Structure

- `src/`
  - `screens/`: Contains all app screens (e.g., `HomeScreen.js`).
  - `navigation/`: Manages navigation logic (e.g., `AppNavigator.js`).
  - `context/`: Handles global state management (e.g., `AuthContext.js`).
- `assets/`: Static files such as images and icons.
- `App.js`: Entry point for the app.

---
