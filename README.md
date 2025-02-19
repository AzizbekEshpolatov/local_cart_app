# LocalCart – Flutter CRUD Admin Panel with Provider & SQLite

## 📝 Project Description

LocalCart is a Flutter-based admin panel application that allows users (admin) to manage products
locally using SQLite for data storage. The app is built with the Provider state management solution,
ensuring smooth and reactive UI updates. Additionally, it integrates local notifications to inform
the admin when a product is added successfully.

## ✨ Key Features

- 🛒 **Product CRUD Operations:**
    - Create, Read, Update, Delete products.
- 💾 **Local Storage:**
    - SQLite for offline data persistence.
- 🔄 **State Management:**
    - Provider package for reactive state updates.
- 🔔 **Local Notifications:**
    - Notifications when a product is added successfully.
- 🖥️ **User-Friendly UI:**
    - Simple and efficient admin panel design.

## 🧑‍💻 Tech Stack

- **Flutter** – Frontend development
- **Provider** – State management
- **SQLite (sqflite package)** – Local database
- **Flutter Local Notifications** – Notification integration

## 📦 Required Packages

Add these dependencies to your `pubspec.yaml`:

```yaml
dependencies:
  flutter:
    sdk: flutter
  provider: ^6.0.5
  sqflite: ^2.3.0
  path: ^1.8.3
  flutter_local_notifications: ^15.1.0+1
```

## 📂 Folder Structure

```
lib/
│
├── data/
│   └── db/                # SQLite database helper
│
├── models/
│   └── product_model.dart
│
├── providers/
│   └── product_provider.dart
│
├── services/
│   └── notification_service.dart
│
├── ui/
│   ├── product_list_screen.dart
│   └── product_form_screen.dart
│
└── main.dart
```

## ⚙️ Setup & Installation

1. Clone the repository:
   ```bash
   git https://github.com/AzizbekEshpolatov/local_cart_app
   ```
2. Navigate to the project folder:
   ```bash
   cd local_cart_app
   ```
3. Install dependencies:
   ```bash
   flutter pub get
   ```
4. Run the app:
   ```bash
   flutter run
   ```

## 🛠️ How It Works

- **Product CRUD:**
    - Admin can add a product (Name, Price, Description, etc.).
    - Admin can view all products.
    - Admin can edit product details.
    - Admin can delete a product.
- **Notification:**
    - When a product is added successfully, a local notification is shown.
- **Provider:**
    - State is managed reactively using the Provider package.
- **SQLite:**
    - Product data is saved locally and persists across app restarts.

## 🚀 Future Enhancements

- Add product images.
- Implement product categories.
- Add search and filtering options.
