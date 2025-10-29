# 🎸 ToneSeer Bass Practice App

Welcome to **ToneSeer**, the all-in-one bass practice companion designed to make learning and playing music more engaging, intuitive, and fun. Built as an **Android TV app**, ToneSeer integrates your **Spotify** library with **Songsterr tablature**, creating a seamless environment for practicing bass guitar.

---

## 🚀 Key Features

- **🎵 Spotify Integration**  
  Connect your Spotify account to access playlists, control playback, and manage your music directly within the app.

- **📜 Tablature Display**  
  View real-time bass tabs via Songsterr while listening to your favorite tracks.

- **⏯️ Playback Control**  
  Play, pause, skip, shuffle, and repeat songs—all synced with your Spotify session.

- **📁 Playlist Management**  
  Create, modify, and organize your Spotify playlists from within ToneSeer.

- **🎲 Song Suggestion**  
  Let ToneSeer pick a random song from a genre or playlist to keep your practice fresh and inspiring.

---

## 📋 System Requirements

### User Requirements

- **Device:** Android TV or emulator  
- **OS:** Android 11+  
- **Storage:** 200 MB free  
- **Internet:** Stable broadband or ethernet  
- **Spotify Account:** Free or Premium  
- **Input:** Android TV remote or compatible controller

### Technical Dependencies

- **Language:** Kotlin  
- **UI:** Jetpack Compose (Material3)  
- **Networking:** OkHTTP  
- **Web Integration:** Android WebView  
- **Min SDK:** 30  
- **Target SDK:** 34  
- **Build Tools:** Gradle

---

## 🛠️ Installation & Setup

### 1. Install Android Studio

Download and install Android Studio (Narwhal version) from:  
👉 https://developer.android.com/studio
Ensure you install the **Android Emulator** during setup.

### 2. Create a TV Emulator

Navigate to the Device Manager section in Android Studio and create a New Device.
If you are unsure, this tutorial will show you how to set up and Android device in the Emulator: https://medium.com/@queen_shecoder/getting-started-with-setting-up-an-emulator-in-android-studio-8b573dd2326f
Ensure you instal and **ANDROID TV emulator**. Set the API to **API 36.0 "Baklava";Android 16.0.**
The **Services** and **System Image** can be left **Default.**
Click **"Finish"** to create the emulator. 

### 3. Download and Unzip the APK file 

Visit the repo:  
👉 Download the APK file from https://github.com/arny-j/ToneSeer-APk.
I would suggest placing the APK file on your desktop, this will make it much easier to drag and drop it into the emulator when you go to run the app. 

### 4. Install the App
**!! IMPORTANT !!** Cold boot the TV emulator to sync the device time wiht your sysyem time. 
This can be done using the three dots on the device in the Device Manager. 
Once running, find the download location for the APK and drag-and-drop the APK file into the emulator. 
This should install the app on the device. 
