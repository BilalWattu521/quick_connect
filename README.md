# Quick Connect 📱

[![Flutter](https://img.shields.io/badge/Flutter-2.10-blue?logo=flutter)](https://flutter.dev/)
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black)](https://firebase.google.com/)

**Quick Connect** is a modern, sleek **social networking Android app** built with **Flutter** and **Firebase**. Connect with friends, share posts, follow users, and engage in real-time interactions. Designed for simplicity, speed, and an engaging experience.

---

## 🌟 Features

### 🔑 Authentication
- **Signup**: Register with **email & password** via Firebase Auth.
- **Login**: Authenticate securely and fetch username automatically.
- **Persistent Login**: Stay logged in using **SharedPreferences**.

### 👤 Profile Management
- **Profile Page**: View profile picture, username, email, and dynamic counts: posts, followers, following, likes.
- **Follow/Unfollow**: Follow friends and see updates in real time.
- **Profile Picture Update**: Upload or change profile pictures dynamically.

### 📝 Posts
- **Create Posts**: Share text posts with optional images.
- **Like Posts**: Toggle likes, tracked under both post and user.
- **Delete Posts**: Authors can delete their own posts instantly.

### 📲 Feeds
- **Home Feed**: Shows latest posts from all users.
- **Profile Feed**: Shows all posts by a specific user.
- **Add New Post**: Easily create new posts from the feed.

### Adaptive Theme
- **System Default**: Enjoy your system's default theme.
- **Dark Theme**: Enjoy Dark theme.
- **Light Theme**: Enjoy Light theme.

---

## 📸 Screenshots


![Login Screen](screenshots/login.jpg)
![Signup Screen](screenshots/signup.jpg)
![Password Reset](screenshots/forgot_password.jpg)
![Home Feed](screenshots/home.jpg)
![My Profile](screenshots/profile.jpg)
![Create Post](screenshots/new_post.jpg)
![Delete Post](screenshots/delete_post.jpg)
![Update Profile Pic](screenshots/update_profile_pic.jpg)
![Other User Profile](screenshots/other_user_profile.jpg)

---

## 🚀 How to Run

1. **Clone the Repository**

        git clone https://github.com/BilalWattu521/quick_connect.git

        cd quick_connect

3. **Install Dependencies**

        flutter pub get

3. **Configure Firebase**

      Create a Firebase project for Android.

      Add google-services.json to android/app/

      Enable Email/Password Authentication and Realtime Database.

4. **Run the App**

        flutter run
   
      Note: Android only for now.
---

### 🛠 Tech Stack
  - Flutter – Frontend

  - Firebase Authentication – Login & Signup

  - Firebase Realtime Database – Real-time storage

  - SharedPreferences – Local persistence

  - Provider – State management
---

# Author
- Muhammad Bilal Ahmed
