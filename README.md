# 📺 Quran TV

Quran TV is a modern, elegant, and spiritually-themed Flutter application for live Islamic TV streaming. The app features multiple high-quality Quran channels with smooth user experience, Islamic aesthetics, and performance-optimized architecture.

---

## 🚀 Features

* 🕋 Stream live Quran and Islamic TV channels (1080p / 720p)
* 🌙 Beautiful splash screen with Islamic design
* 📡 Smooth and responsive video player
* 📺 Channel list with thumbnails, names (Arabic & English), quality badges
* 🌐 Multi-language support (English, Arabic)
* 📱 Responsive UI for different screen sizes
* 💾 Caching and offline support (where applicable)
* 🔌 Modular and scalable architecture (Clean Architecture)

---

## 🧱 Project Structure

```
lib/
├─ core/                    # App-wide core functionality
│  ├─ base/                 # API config, service locator, observer
│  ├─ enviroment/          # Environment variables
│  ├─ error/               # Error handling system
│  ├─ flavors/             # Flavor-based environment config
│  ├─ l10n/                # Localization (AR/EN)
│  ├─ models/              # Shared enums & response models
│  ├─ services/            # Connectivity, HTTP, Security, etc.
│  ├─ utils/               # Extensions, validation, theming, routing
│  ├─ widgets/             # Reusable widgets (buttons, toasts, dropdowns)
│  └─ core_export.dart     # Central export file
├─ features/
│  ├─ quran_tv/            # Main feature: channel list + player
│  │  ├─ data/             # Model(s) for channel info
│  │  ├─ presentation/     # UI pages and cubits
│  ├─ splash/              # Splash screen feature
├─ main_common.dart        # Flavor entry point
├─ main.dart               # Main launcher
└─ my_app.dart             # App widget and setup
```

---

## 🌍 Supported Channels

* Al-Quran Al-Kareem TV
* Madinah Live - Sunnah TV
* Bahrain Quran TV
* Holy Quran Radio Nablus
* Iqraa Quran Channel
* Al-Majd Holy Quran
* Al-Quran TV Iraq
* Quran Radio (Saudi)
* Sharjah Radio Quran

---

## 🧪 Technologies Used

* Flutter 3.19+
* Dio (HTTP requests)
* BLoC (State management)
* Custom Service Locator
* Responsive Design
* Localization (arb, `AppLocalizations`)
* Clean Architecture + Modular Feature System

---

## 🖼 UI Highlights

* Splash screen with crescent and Islamic geometric patterns
* Fully RTL-compatible
* Modern card-based list with hover/tap feedback
* Smooth transitions between pages

---

## 📷 Screenshots

  Splash Page                 |   Home Page        |  Live Page
:-------------------------:|:-------------------------:|:-------------------------:
![446520585-164806f2-f569-4a51-9c6e-ae55d9ea0af6](https://github.com/user-attachments/assets/8f68a9ce-af86-4d06-9929-929d4c045dca)|![446520581-7c95cbba-9998-4871-bdeb-07b8c620b49f](https://github.com/user-attachments/assets/b1cca680-bd5c-4ed5-a8b4-3b1bfdc9051d)|![446520570-73216e6d-cb20-49f0-9e62-962605125b66](https://github.com/user-attachments/assets/10a0c36a-c026-4554-ad74-f78753cd3196)




---

## 👨‍💻 Author

Developed with ❤️ by [Mahmoud Alaa](https://www.linkedin.com/in/mahmoudalaa2210/) & [Waleed Ashraf](https://www.linkedin.com/in/waleed-ashrf/)

---

## 📜 License

This project is licensed under the MIT License.
