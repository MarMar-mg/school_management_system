# 🏫 School Management System

A **School Management System** built with **Flutter** and a dedicated backend API.

The project provides a cross-platform application for managing school-related data and operations through a Flutter client connected to the `SchoolPortalAPI` backend.

---

## ✨ Features

* 📱 Cross-platform Flutter application
* 🌐 REST API integration
* 🔐 Authentication and API communication
* 🧩 State management with Provider
* 💉 Dependency injection with GetIt
* 💾 Local data storage
* 🖼️ Image and file handling
* 📶 Network connectivity handling
* 🌍 Localization support
* 🇮🇷 Persian/Shamsi date support
* 🎨 Modern UI with animations and loading states

---

## 🛠️ Tech Stack

### Frontend

* **Flutter**
* **Dart**
* **Provider**
* **GetIt**
* **Dio**
* **HTTP**
* **Shared Preferences**
* **GetStorage**

### UI & Utilities

* Lottie
* Shimmer
* Flutter SVG
* Image Picker
* File Picker
* Cached Network Image
* Permission Handler
* Connectivity Plus
* Intl
* Shamsi Date

### Backend

* `SchoolPortalAPI`
* REST API

---

## 🏗️ Architecture

The project follows a client-server architecture:

```text
┌─────────────────────────┐
│     Flutter Client      │
│                         │
│  UI → State → Services  │
└────────────┬────────────┘
             │
             │ REST API
             ▼
┌─────────────────────────┐
│     SchoolPortalAPI     │
│        Backend          │
└────────────┬────────────┘
             │
             ▼
┌─────────────────────────┐
│        Database         │
└─────────────────────────┘
```

The Flutter application communicates with the backend through HTTP APIs, while the backend handles server-side logic and data access.

---

## 📁 Project Structure

```text
school_management_system/
│
├── android/
├── ios/
├── linux/
├── macos/
├── web/
├── windows/
│
├── assets/
│   ├── animations/
│   └── images/
│
├── lib/
│   └── # Flutter application source
│
├── test/
│
├── SchoolPortalAPI/
│   └── # Backend API
│
├── pubspec.yaml
├── analysis_options.yaml
└── README.md
```

---

## 🚀 Getting Started

### Requirements

Make sure you have installed:

* Flutter SDK
* Dart SDK
* Git
* Android Studio / Android SDK for Android development
* Xcode for iOS development on macOS

The project currently uses:

```yaml
Dart SDK: ^3.9.2
```

### Clone the Repository

```bash
git clone https://github.com/MarMar-mg/school_management_system.git

cd school_management_system
```

### Install Dependencies

```bash
flutter pub get
```

### Check the Project

```bash
flutter analyze
```

### Run Tests

```bash
flutter test
```

### Run the Application

```bash
flutter run
```

---

## 🔌 Backend Configuration

The backend is located in:

```text
SchoolPortalAPI/
```

Before running the application, make sure the backend API is configured and running.

Configure the Flutter application with the appropriate API base URL for your environment.

For Android Emulator, a local API may be accessible through:

```text
http://10.0.2.2:<PORT>
```

For a physical device, use the local IP address of the development machine instead of `localhost`.

> Do not commit API keys, passwords, tokens, or other sensitive credentials to the repository.

---

## 🏭 Build

### Android APK

```bash
flutter build apk --release
```

### Android App Bundle

```bash
flutter build appbundle --release
```

### Web

```bash
flutter build web --release
```

---

## 📄 License

License information will be added to the project.

---

## 👨‍💻 Author

**MarMar-mg**

GitHub:
https://github.com/MarMar-mg

Repository:
https://github.com/MarMar-mg/school_management_system

---

<p align="center">
  Built with ❤️ using Flutter & Dart
</p>
