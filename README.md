# LifeFlow: A Blood Donation App

LifeFlow is a cross-platform mobile application designed to simplify and improve the blood donation process in Pakistan. The app connects donors, recipients, and blood donation centers in real time, facilitating timely blood availability, especially during emergencies.

---

## 🚀 Features

### ✅ User-Focused Modules
- **Authentication:** Secure login/signup using Firebase Authentication (email/password).
- **Profile Management:** Create, update, and manage user profiles with blood type, contact info, and health details.
- **Donation System:** Donors can view and respond to blood requests.
- **Emergency Requests:** Users can submit urgent requests by specifying blood type and urgency (Urgent, Medium, Low).
- **Nearby Blood Banks:** Simulated blood bank data shown using Geolocator and Google Maps integration.
- **Donation History:** Track donation status and view historical data via Firebase Firestore.

---

## 🎓 Learning Outcomes

### 🛠 Technical Skills
- **Flutter & Dart:** Built a responsive cross-platform UI using Flutter.
- **Firebase Integration:** Auth, Firestore, Storage, and real-time updates with Firestore listeners.
- **Geolocation:** Location-based services with `geolocator` and `google_maps_flutter`.
- **Async Programming:** `FutureBuilder`, `StreamBuilder`, and async/await usage.
- **State Management:** Managed global state using Provider.

---

## ⚠️ Challenges & Resolutions

- **Firebase Setup Errors:** Resolved SHA mismatch by reconfiguring Firebase CLI and project settings.
- **UI Responsiveness:** Used `MediaQuery` and `LayoutBuilder` to adapt to various device sizes.
- **Real-Time Sync:** Enabled Firestore listeners to keep requests and user data in sync.
- **APK Build Issues:** Fixed Gradle and SDK-related problems by updating dependencies.

---

## 📲 Screenshots

> *Screenshots of the UI have been included in the report for visual reference.*

---

## 📦 Project Structure

```
/lifeflow/
├── android/
├── ios/
├── lib/
│   ├── screens/
│   ├── widgets/
│   ├── models/
│   ├── services/
│   └── main.dart
├── assets/
├── pubspec.yaml
└── README.md
```

---

## 🛠 How to Run This Project

### 📌 Prerequisites

- Flutter SDK installed: [Get Flutter](https://flutter.dev/docs/get-started/install)
- Android Studio / VS Code (with Flutter and Dart extensions)
- Firebase project set up (with proper configuration)

---

### 🧪 Steps to Run

1. **Clone the Repository**

```bash
git clone https://github.com/your-username/lifeflow.git
cd lifeflow
```

2. **Install Dependencies**

```bash
flutter pub get
```

3. **Configure Firebase**

- Replace `/android/app/google-services.json` and `/ios/Runner/GoogleService-Info.plist` with your own Firebase files.
- Enable Firebase Authentication, Firestore, and Storage from the Firebase Console.

4. **Run the App**

```bash
flutter run
```

> Make sure an emulator or physical device is connected.

---

## 📁 Project Code

The entire source code, assets, and configuration files are included in this GitHub repository.

---

## ✍️ Author

- **Project By:** Syed Muhammad Ali Raza Naqvi, Ramla Owais
- **Course:** Mobile Application Development (Semester 6)

---

## 📄 License

This project is for educational purposes and is not intended for production use without additional security, testing, and optimization.
