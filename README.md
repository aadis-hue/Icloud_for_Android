# iCloud for Android (WebView)

A lightweight, feature-rich Android wrapper for the iCloud web interface. This app provides a seamless experience for accessing iCloud Photos, Mail, Drive, and Shared Albums directly on your Android device.

## 🚀 Features

- **Full iCloud Access:** Navigate all iCloud web apps (Photos, Notes, Mail, etc.).
- **Shared Albums Support:** Special configuration to ensure Shared Albums are visible and interactive.
- **Desktop Experience:** Uses a Mac Safari User-Agent to unlock features usually restricted on mobile browsers.
- **File Uploads & Downloads:** Fully supports uploading photos/files and downloading images directly to your device's Downloads folder.
- **Deep Linking:** Automatically opens `icloud.com` links within the app.
- **Integrated Navigation:** Handles popups and new windows within the same app instance.
- **Modern UI:** Features a native Splash Screen and follows Material Design guidelines.

## 🛠️ Technical Highlights

- **WebView Optimization:** Enabled DOM storage, Database API, and JavaScript window handling for maximum compatibility with Apple's complex web architecture.
- **User-Agent Spoofing:** Configured as `Macintosh; Intel Mac OS X 10_15_7` to bypass mobile-only limitations.
- **Permission Handling:** Dynamically requests media permissions for seamless file interactions on Android 13+.
- **Download Manager Integration:** Custom `DownloadListener` to handle authenticated file downloads from the iCloud CDN.

## 📦 Getting Started

### Prerequisites
- Android Studio Ladybug or newer.
- Android SDK 24 (Android 7.0) or higher.

### Installation
1. Clone the repository.
2. Open the project in Android Studio.
3. Build and Run on your device or emulator.

### OR
1.Click on the .apk file in this repo.
2.Download
3.Open the file


## 🛡️ Disclaimer
This project is an independent wrapper and is not affiliated with, sponsored by, or endorsed by Apple Inc. "iCloud" is a trademark of Apple Inc.

---
*Created for personal use to bridge the gap between Android hardware and the iCloud ecosystem.*
