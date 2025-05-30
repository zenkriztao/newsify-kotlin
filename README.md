# NewsifyKotlin 📰📱

NewsifyKotlin is a modern **news aggregation app** built using **Kotlin** and **Jetpack Compose** for Android. The application fetches real-time news from an API, providing users with a seamless and responsive interface to stay updated on global news.

This project leverages Android’s most recent technologies, including **Jetpack Compose** for UI components, **Kotlin** for concise and efficient code, and **Retrofit** for networking.

## 🚀 Features

- 🌍 **Real-time News**: Fetches news from multiple categories (e.g., Technology, Sports, Business) via an API.
- 📱 **Jetpack Compose**: Utilizes the power of Jetpack Compose for building a clean, modern, and intuitive UI.
- 🔄 **Dynamic Content**: Displays a list of news articles, each with an image, title, description, and a link to read more.
- ⚡ **Lightweight**: Optimized for performance with smooth scrolling and minimal latency in fetching news.
- 🌙 **Dark Mode Support**: Seamless switch between light and dark themes based on user preferences.

## ⚙️ Technologies Used

- **Kotlin** 🦸‍♂️: The primary programming language for building the app.
- **Jetpack Compose** 📲: The modern UI toolkit for building Android UIs declaratively.
- **Retrofit** 🔌: Used for making API requests to fetch news data.
- **Glide/Coil** 🖼️: For efficient image loading and caching.
- **Room Database** 💾: For local caching of news articles, allowing offline reading.

## 📖 How It Works

### API Integration

The app fetches news data from a third-party API that provides up-to-date articles based on selected categories. The news data includes essential details like:

- Title of the news article
- Description of the article
- Image URL (for displaying news images)
- Article URL (for redirecting users to the original news source)

The app uses **Retrofit** for API calls and **Gson** for parsing JSON data.

### UI/UX

The app’s interface is built using **Jetpack Compose**, ensuring a modern and highly responsive UI. The list of articles is displayed in a **LazyColumn**, and each item has an image, title, and description.

## 🛠 Setup

### Prerequisites

Before running the app, ensure that you have the following installed:

- Android Studio (latest stable version)
- JDK 8 or higher
- Kotlin 1.5 or higher

# Newsify - Kotlin News App

A Kotlin-based Android app that fetches real-time news articles using the News API.

## Installation Steps

### 1. Clone the Repository

Clone the repository to your local machine using the following command:

```bash
git clone https://github.com/zenkriztao/newsify-kotlin.git
```

### 2. Open the Project in Android Studio

1. Open **Android Studio**.
2. Choose **Open an existing project**.
3. Select the folder where you cloned the repository.

### 3. Sync Gradle Files

After opening the project, sync the Gradle files and let Android Studio build the project.

### 4. Run the Project

You can now run the project on either an Android Emulator or a physical device.

### 5. Set Up Your Own API Key (Optional)

To use your own API key for fetching news data:

1. Visit [News API](https://newsapi.org/) and sign up to get a free API key.
2. Add your API key to the `strings.xml` file:

   ```xml
   <string name="api_key">YOUR_API_KEY_HERE</string>
   ```

---

## Gradle Dependencies

Ensure the following dependencies are included in your `build.gradle`:

```gradle
dependencies {
    implementation "androidx.compose.ui:ui:1.0.0"
    implementation "androidx.compose.material:material:1.0.0"
    implementation "androidx.compose.ui:ui-tooling:1.0.0"
    implementation "com.squareup.retrofit2:retrofit:2.9.0"
    implementation "com.squareup.retrofit2:converter-gson:2.9.0"
    implementation "io.coil-kt:coil-compose:1.3.2"  // For image loading
    implementation "androidx.room:room-runtime:2.3.0"
    kapt "androidx.room:room-compiler:2.3.0"
}
```

---

## API Key Configuration

1. Go to [News API](https://newsapi.org/) and sign up for an API key.
2. Add your API key in the `strings.xml` file:

   ```xml
   <string name="api_key">YOUR_API_KEY_HERE</string>
   ```

---

## 🧑‍💻 Contributing

We welcome contributions to the project! To contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature/your-feature`).
3. Make your changes and commit them (`git commit -am 'Add your feature'`).
4. Push the changes to your fork (`git push origin feature/your-feature`).
5. Create a Pull Request for review.

Please ensure your code follows **Kotlin** and **Jetpack Compose** best practices for easy integration.

---

## 📝 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## 📑 Acknowledgements

* **News API**: Provides real-time news articles. [News API Documentation](https://newsapi.org/docs/endpoints/everything)
* **Jetpack Compose**: Android's toolkit for building modern UIs in a declarative style.
* **Kotlin**: The programming language used in this project for its concise and expressive syntax.

---

🧑‍💻 **Built by** [Zenkriztao](https://github.com/zenkriztao) - A Kotlin enthusiast passionate about creating fast, smooth, and intuitive mobile apps.
