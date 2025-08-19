# 📍 Find My Location App

![Android](https://img.shields.io/badge/Platform-Android-green?logo=android)
![Java](https://img.shields.io/badge/Language-Java-blue?logo=java)
![Location](https://img.shields.io/badge/Feature-Location-lightgrey?logo=google-maps)
![License](https://img.shields.io/badge/License-MIT-brightgreen)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 📌 About

This is a **basic Android application** built using **Java** that demonstrates how to fetch the **current location** of the device using the **Fused Location Provider API**. The app requests runtime permissions for location access and displays the latitude and longitude in real-time.

---

## 🚀 Features

- 📍 Fetches real-time device location
- 🔑 Requests runtime permissions (`ACCESS_FINE_LOCATION` / `ACCESS_COARSE_LOCATION`)
- 🌐 Uses **Fused Location Provider Client** for accurate location
- 🖥️ Displays **latitude** and **longitude** on the screen
- 📡 Lightweight and easy-to-understand implementation

---

## 🧰 Tech Stack

- **Language:** Java
- **Platform:** Android
- **IDE:** Android Studio
- **API:** Fused Location Provider (Google Play Services)

---

## 📂 Project Structure

```
📦 com.example.findmylocation
┣ 📄 MainActivity.java
┣ 🗂️ res/layout/activity_main.xml
┗ 🗂️ AndroidManifest.xml
```

---

## 💻 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/harinandanmv/find-my-location.git
   ```

2. Open the project in **Android Studio**.

3. Add the required **Google Play Services Location dependency** in `build.gradle`:

   ```gradle
   implementation 'com.google.android.gms:play-services-location:21.0.1'
   ```

4. Connect your emulator or Android device.

5. Click **Run** ▶️ to build and launch the app.

---

## ⚠️ Important Notes

* Location permissions **must be granted** for the app to work.
* Works only on devices with **Google Play Services**.
* Ensure **GPS/Location** is enabled on the device.

---

## 📚 Useful Resources

* [Fused Location Provider API](https://developer.android.com/training/location)
* [Android Runtime Permissions](https://developer.android.com/training/permissions/requesting)
* [Android Developer Docs](https://developer.android.com/)

---

> ✨ Learn by building — this simple app is a great starting point for mastering location-based features in Android!
