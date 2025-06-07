# 📱 Android App Developer Interview Questions

This repository contains commonly asked Android development interview questions and answers to help you prepare for technical interviews as an Android developer. It covers core Android topics, architecture components, networking, and more.

---

## 📌 Topics Covered

- Android Fundamentals
- Lifecycle & Architecture
- Kotlin & Coroutines
- Jetpack Libraries
- UI & Layouts
- Networking (Retrofit, API)
- Room Database & LiveData
- Testing & Performance

---

## ✅ Interview Questions & Answers

### 1. **What is an Activity in Android?**
An Activity is a single screen with a user interface. It acts as the entry point for user interaction with the app.

---

### 2. **What is the Activity Lifecycle?**
Main lifecycle methods:
- `onCreate()`
- `onStart()`
- `onResume()`
- `onPause()`
- `onStop()`
- `onDestroy()`
- `onRestart()`

---

### 3. **What is the difference between Activity and Fragment?**
- **Activity**: Complete screen.
- **Fragment**: Reusable portion of UI in an activity.
- Fragments help with modular UI.

---

### 4. **What is ViewModel?**
`ViewModel` stores UI-related data and survives configuration changes like screen rotation. It separates UI logic from activity/fragment.

---

### 5. **What is an Intent?**
Intent is used to launch other activities or services.  
- **Explicit Intent**: Starts a specific component.  
- **Implicit Intent**: Requests an action (like opening a URL or camera).

---

### 6. **What is LiveData?**
`LiveData` is a lifecycle-aware observable data holder. It automatically updates the UI when data changes.

---

### 7. **What is Room Database?**
Room is a Jetpack component for using SQLite in Android with compile-time verification of SQL queries and data abstraction.

---

### 8. **What is Retrofit?**
Retrofit is a REST client for Android. It helps in making API calls and converting JSON to Java/Kotlin models.

---

### 9. **Coroutine vs Thread?**
- **Thread**: Heavyweight, managed by OS.  
- **Coroutine**: Lightweight, better for managing background tasks and concurrency in Kotlin.

---

### 10. **Explain MVVM Architecture.**
- **Model**: Data layer (API, DB)  
- **View**: UI components  
- **ViewModel**: Connects UI and data, handles business logic

---

### 11. **What is Data Binding?**
It allows binding UI components directly to data sources in XML, reducing boilerplate code.

---

### 12. **What is the difference between onSaveInstanceState() and ViewModel?**
- `onSaveInstanceState()`: Saves small data in Bundle.  
- `ViewModel`: Keeps data during configuration changes without rebinding UI manually.

---

### 13. **What is WorkManager?**
Used for deferrable background tasks that are guaranteed to execute even if the app closes or the device restarts.

---

### 14. **Common causes of memory leaks in Android?**
- Static references to Context  
- Not unregistering BroadcastReceivers or listeners  
- Long-running background tasks

---

## 🙌 Contribution

Feel free to contribute more questions, improve answers, or add advanced-level topics by submitting a pull request!

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

**Happy learning and good luck for your interviews! 💼**

