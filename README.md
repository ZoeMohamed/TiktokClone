# TikTok Clone with GetX and Firebase in Flutter

This repository contains a TikTok clone built using Flutter, with GetX for state management and Firebase for backend services. The app mimics the core functionalities of TikTok, providing a platform to upload and view short videos.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Project](#running-the-project)
- [Project Structure](#project-structure)
- [Firebase Setup](#firebase-setup)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

## Features

- User authentication (Firebase Auth)
- Video upload and storage (Firebase Storage)
- Real-time video feed (Firebase Firestore)
- Like, comment, and share functionality
- User profile management

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

- [Flutter 3.22.2](https://docs.flutter.dev/get-started/install) 
- [Dart 3.4.3](https://dart.dev/get-dart)
- An IDE such as [Android Studio](https://developer.android.com/studio) or [Visual Studio Code](https://code.visualstudio.com/)
- [Git](https://git-scm.com/)
- Firebase project setup (see [Firebase Setup](#firebase-setup))

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/ZoeMohamed/TiktokClone.git
    cd TiktokClone
    ```

2. Install dependencies:
    ```bash
    flutter pub get
    ```

### Running the Project

To run the project on your local machine, ensure you have an emulator or a physical device connected.

1. **Android Emulator**:
    - Start your emulator from Android Studio or through the command line:
      ```bash
      emulator -avd your_avd_name
      ```

2. **iOS Simulator**:
    - Open the iOS simulator from Xcode.

3. **Physical Device**:
    - Connect your device via USB and ensure it is recognized by running:
      ```bash
      flutter devices
      ```

To run the app, use the following command:
```bash
flutter run
