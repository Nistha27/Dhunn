# 🎵 Dhunn – A Spotify-Inspired Music Streaming App

[![Flutter](https://img.shields.io/badge/Built%20with-Flutter-blue.svg)](https://flutter.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

**Dhunn** is a feature-rich, cross-platform music streaming app inspired by Spotify, built using **Flutter**, **BLoC (Cubit)** state management, and **Firebase** backend services. The project follows **Clean Architecture principles**, promoting modularity, testability, and scalability.

---

## 📌 Features

- 🎧 **Music Playback** – Play/pause, seek, skip functionality
- 🎵 **Track Listings** – Browse songs and albums
- 🧠 **BLoC State Management (Cubit)** – Efficient and reactive UI updates
- 🔥 **Firebase Integration**:
  - Authentication (Email/Password, Google Sign-In)
  - Realtime Database / Firestore for storing metadata
- 🧼 **Clean Architecture** – Well-structured domain, data, and presentation layers
- 📱 **Responsive UI** – Works across Android, iOS, and Web
- 💚 **Local Music Caching (Planned)** – For offline listening

---

## 📂 Folder Structure

```plaintext
Dhunn/
│
├── android/              # Android-specific code
├── assets/               # App assets (images, icons, fonts, etc.)
│   └── icons/
│   └── images/
│   └── songs/
│
├── ios/                  # iOS-specific code
├── lib/
│   ├── core/             # Constants, utilities, themes
│   ├── data/             # Repositories, datasources, Firebase integration
│   ├── domain/           # Entities, use cases, repositories (abstract)
│   ├── presentation/
│   │   ├── blocs/        # BLoC (Cubit) classes for state management
│   │   ├── pages/        # Screens: Home, Login, Player, etc.
│   │   ├── widgets/      # Reusable UI components
│   └── main.dart         # Entry point
│
├── pubspec.yaml          # Dependencies and assets
├── test/                 # Unit and widget tests
└── README.md             # You're reading it!
