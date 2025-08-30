# 🎵 Spotify Clone with Flutter

A Spotify-like music streaming app built with **Flutter**, following **Clean Architecture**, using **BLoC** for state management, and powered by **Firebase** for backend services.  
This project is designed for learning scalable Flutter development practices and building real-world apps.

---

## 🚀 Features

- 🎶 Browse and play music tracks  
- 🔐 Firebase Authentication (Email/Google)  
- 📂 Firestore database integration  
- 📡 Real-time sync with Firebase  
- 📱 Responsive & clean UI with Flutter  
- ⚡ State management with BLoC  
- 🏗️ Scalable **Clean Architecture**  

---

## 🛠️ Tech Stack

- **Frontend:** Flutter (Dart)  
- **State Management:** BLoC  
- **Architecture:** Clean Architecture  
- **Backend:** Firebase Authentication, Cloud Firestore  
- **Tools:** Android Studio / VS Code  

---

## 📂 Project Structure

lib/
├── core/ # App-wide utilities & constants
├── features/ # Feature modules
│ ├── auth/ # Authentication
│ ├── player/ # Music player
│ └── home/ # Home screen & browsing
├── common/ # Shared widgets
└── main.dart # App entry point

yaml
Copy code

---

## ⚙️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/ARK1998/Spotify-Clone-With-Flutter.git
   cd Spotify-Clone-With-Flutter
Install dependencies

bash
Copy code
flutter pub get
Setup Firebase

Create a Firebase project at Firebase Console

Enable Authentication & Firestore

Download google-services.json (Android) and place it in android/app/

Download GoogleService-Info.plist (iOS) and place it in ios/Runner/

Run the app

bash
Copy code
flutter run
📸 Screenshots
Login Screen	Home Screen	Player Screen

(Replace with your actual screenshots)

🤝 Contributing
Contributions are welcome!

Fork the repo

Create a new branch (feature/new-feature)

Commit changes

Submit a PR 🚀

📜 License
This project is licensed under the MIT License.
See the LICENSE file for details.

🌟 Support
If you like this project, don’t forget to star ⭐ the repo!

