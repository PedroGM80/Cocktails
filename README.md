# 🍸 Cocktails - Cocktail Companion App

A modern Android application designed to help cocktail enthusiasts discover, explore, and save their favorite drink recipes. Built with Kotlin and leveraging the latest Android development technologies and architecture patterns.

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpack-compose&logoColor=white)

---

## 📱 Features

- **Browse Cocktail Database** - Explore a comprehensive collection of cocktail recipes
- **Search & Filter** - Find cocktails by name, ingredients, or preparation method
- **Save Favorites** - Create and manage your personal collection of favorite drinks
- **Detailed Recipes** - View complete ingredients lists, measurements, and preparation instructions
- **Modern UI** - Beautiful, responsive interface built with Jetpack Compose
- **Smooth Navigation** - Intuitive navigation structure for seamless user experience
- **Persistent Storage** - Your favorite cocktails are saved locally on your device

---

## 🛠️ Tech Stack

### Architecture
- **MVVM** (Model-View-ViewModel) pattern for clean separation of concerns
- **Repository Pattern** for data access abstraction
- **Dependency Injection** for better code organization and testability

### Technologies & Libraries
- **Kotlin** - Modern, concise, and safe programming language
- **Jetpack Compose** - Modern declarative UI toolkit
- **Room Database** - Local persistence for favorite cocktails
- **Retrofit** - HTTP client for API communication
- **Coroutines** - Asynchronous programming with lightweight threads
- **LiveData** - Observable data holders for reactive UI updates
- **Hilt** - Dependency injection framework
- **Navigation Component** - Type-safe navigation between fragments

---

## 🚀 Getting Started

### Prerequisites
- Android Studio (latest version)
- JDK 11 or higher
- Android SDK 24 or higher
- Gradle 7.0+

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/PedroGM80/Cocktails.git
cd Cocktails
```

2. **Open in Android Studio** - Launch Android Studio, select "Open an Existing Project", navigate to the cloned directory

3. **Build the project**
```bash
./gradlew build
```

4. **Run on Emulator or Device** - Click Run in Android Studio, select your target device

---

## 📁 Project Structure

```
Cocktails/
├── app/
│   ├── src/
│   │   ├── main/java/dev/pgm/cocktails/
│   │   │   ├── ui/theme/       # Theme and styling
│   │   │   └── MainActivity.kt # Main entry point
│   │   ├── res/               # Resources
│   │   └── AndroidManifest.xml
│   ├── build.gradle.kts
│   └── proguard-rules.pro
├── gradle/
├── build.gradle.kts
├── settings.gradle.kts
└── README.md
```

---

## 🤝 Contributing

1. **Fork** the repository
2. **Create a feature branch** (`git checkout -b feature/AmazingFeature`)
3. **Commit your changes** (`git commit -m 'Add some AmazingFeature'`)
4. **Push to the branch** (`git push origin feature/AmazingFeature`)
5. **Open a Pull Request**

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Pedro** - [@PedroGM80](https://github.com/PedroGM80)

📍 Cadiz, Spain | 🌐 [Portfolio](https://pedrogm80.github.io/PedroGM80/#top)

---

**Happy cocktail hunting! 🍹**
