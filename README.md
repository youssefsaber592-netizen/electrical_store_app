# ⚡ Electronics Store App 📱

A modern, fast, and production-ready E-Commerce mobile application built using **Flutter** and **Dart**. The application features a clean user interface, responsive product cards, fluid navigation, and full local language switching. It is fully integrated with a cloud backend for seamless data management.

---

## ⚙️ Backend & Database Cloud Integration

The application is completely integrated with **Firebase** to provide a robust cloud backend infrastructure:
* **🔥 Cloud Firestore:** Utilizes a live NoSQL cloud database to manage, store, and sync user accounts and profile documents in real-time.
* **🔒 Authentication & Secure Storage:** Provides reliable data binding mapping individual authenticated user emails, registration timestamps, and addresses directly to cloud collections.

---

## ✨ Features

* **🔒 Authentication:** Clean Login & Registration flow tied directly to cloud database storage.
* **🌐 Localization:** Fully dynamic dual-language support (English / Arabic) toggled seamlessly in-app.
* **🛍️ Product Catalog:** Search and filter electronic items by categories (Audio, Cameras, VR, etc.).
* **⭐ Favorites System:** Easily add/remove items to your starred favorites list with real-time sync.
* **🛒 Shopping Cart:** Dynamic badge manager in AppBar, dynamic quantity update, and subtotal calculation.
* **📦 Interactive Details Page:** Clean detail preview where users can increase, decrease, or remove quantities directly.

---

## 📸 Screenshots Showcase

| 🎨 Splash & Authentication | 📱 Dynamic Home Screen (AR / EN) |
| :---: | :---: |
| <img src="description image/Screenshot 2026-07-15 235850.png" width="200"/> <img src="description image/Screenshot 2026-07-15 235912.png" width="200"/> <img src="description image/Screenshot 2026-07-15 235922.png" width="200"/> | <img src="description image/Screenshot 2026-07-16 000005.png" width="200"/> <img src="description image/Screenshot 2026-07-16 000103.png" width="200"/> |

| 📦 Details & Quantity Selector | ⭐ Favorites & 🛒 Cart Management |
| :---: | :---: |
| <img src="description image/Screenshot 2026-07-16 000144.png" width="200"/> | <img src="description image/Screenshot 2026-07-16 000111.png" width="200"/> <img src="description image/Screenshot 2026-07-16 000125.png" width="200"/> |

### 🔥 Firebase Cloud Firestore Console
<img src="description image/Screenshot 2026-07-16 002625.png" width="700"/>

---

## 🛠️ Project Structure

```text
lib/
│
├── models/
│   └── product.dart          # Data models
├── screens/
│   ├── home_screen.dart       # Main product feed
│   ├── login_screen.dart      # User Auth login
│   ├── favorites_screen.dart  # Favorite items manager
│   └── details_screen.dart    # Detailed screen with interactive counter
├── language_manager.dart      # Dynamic localization handler
├── constants.dart             # App themes, colors & padding constants
└── main.dart                  # App entrance & initialization
