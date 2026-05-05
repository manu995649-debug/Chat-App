Chat-App
A real-time chat application built with Kotlin, leveraging Firebase as the backend (BaaS) and Jetpack Compose for a modern, declarative UI. This project demonstrates how to integrate Firebase services with a Compose-based Android app to deliver seamless real-time messaging.

🚀 Features
Real-time Chat – Instant messaging powered by Firebase Realtime Database / Firestore.

Firebase Authentication – Secure login and signup with email/password or other providers.

Modern UI with Jetpack Compose – Declarative, responsive, and clean design.

Message Persistence – Chats stored and synced via Firebase.

Scalable Architecture – MVVM pattern for maintainability and testability.

🛠️ Tech Stack
Language: Kotlin

Frontend: Jetpack Compose

Backend (BaaS): Firebase (Authentication, Firestore/Realtime Database)

Architecture: MVVM + Repository pattern

Build Tool: Gradle

📂 Project Structure
Code
Chat-App/
│── app/
│   ├── ui/            # Jetpack Compose screens & components
│   ├── viewmodel/     # ViewModels for state management
│   ├── repository/    # Firebase data handling
│   ├── model/         # Data models (User, Message, etc.)
│   ├── utils/         # Helper classes and extensions
│   └── resources/     # Strings, themes, drawables
│── README.md
⚙️ Installation & Setup
Clone the repository

bash
git clone https://github.com/manu995649-debug/Chat-App.git
cd Chat-App
Open in Android Studio

Ensure you have the latest Android Studio (Arctic Fox or newer).

Open the project folder.

Configure Firebase

Create a Firebase project in the Firebase Console (console.firebase.google.com in Bing).

Add your Android app (package name).

Download the google-services.json file and place it in the app/ directory.

Enable Authentication and Firestore/Realtime Database in Firebase.

Build & Run

Sync Gradle.

Run the app on an emulator or physical device.

🤝 Contributing
Contributions are welcome!

Fork the repo

Create a new branch (feature-xyz)

Commit your changes

Open a Pull Request

📜 License
This project is licensed under the MIT License – feel free to use and modify it.
