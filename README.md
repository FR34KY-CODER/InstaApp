---

<h3 align="center">
  <img src="https://img.shields.io/badge/InstaApp%20-%20Social%20Media%20Application-282C34?logo=Instagram&logoColor=E4405F" alt="InstaApp Logo" height="38" />
</h3>

[![Uploading image.png…]()](https://github.com/FR34KY-CODER/InstaApp/blob/main/instaapp.png?raw=true)

<h4 align="center">🎉 A feature-rich social media app built with Kotlin in Android Studio</h4>

---

## 📱 Features

* 🔐 **Authentication**

  * Sign up with Firebase Authentication
  * Sign in with Firebase
  * Store and retrieve user data using Firebase Realtime Database

* 👤 **User Profiles**

  * Create and edit user profile
  * Account settings management
  * Search for users
  * Follow/Unfollow users
  * Navigate to searched user profiles

* 📸 **Posts & Media**

  * Upload images to Firebase Storage
  * Post images to timeline
  * Like posts and display total likes
  * Add and view comments
  * View post details from user profile
  * Display user's posts on profile
  * Save and view saved post collections

* 🔔 **Notifications**

  * Real-time notifications for likes, comments, and follows

* 📚 **Stories**

  * Upload and view stories
  * Story navigation: next, previous, seen status
  * Display story viewers

---

## 💠 Tech Stack

* **Language:** Kotlin
* **IDE:** Android Studio
* **Backend & Cloud:** Firebase

  * Realtime Database
  * Authentication
  * Storage

---

## 📦 Libraries Used

* [`android-image-cropper`](https://github.com/ArthurHub/Android-Image-Cropper) – Image cropping
* [`StoriesProgressView`](https://github.com/shts/StoriesProgressView) – Instagram-style story view
* [`Picasso`](https://square.github.io/picasso/) – Image loading
* [`CircleImageView`](https://github.com/hdodenhof/CircleImageView) – Circular profile images

---

## 🚀 Getting Started

### 1. 📥 Install Android Studio & Kotlin

👉 [Follow official setup guide](https://developer.android.com/studio/install)

### 2. 🧬 Clone the Repository

```bash
git clone https://github.com/your-username/InstaApp.git
```

> ⚠️ **Important**: Change the package name!
> [How to rename package in Android Studio](https://stackoverflow.com/questions/16804093/android-studio-rename-package)

### 3. 🔧 Firebase Setup

* Go to [Firebase Console](https://console.firebase.google.com)
* Create a new Firebase project
* Enable **Email & Password** authentication:

  * Authentication → Sign-in method → Enable Email/Password
* Add a new **Android App** to the Firebase project:

  * Use your app’s package name (e.g., `com.yourcompany.instaapp`)
* Download `google-services.json`
* Place it inside:

  ```bash
  /app/google-services.json
  ```

> 💡 *You can also use the existing Firebase config in the project temporarily, but it's **not maintained***.

---

## 📌 Notes

* All user-generated content and interactions are powered by Firebase in real time.
* This is a clone-like app intended for learning and demonstrating Firebase integration with modern Android development practices.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---
