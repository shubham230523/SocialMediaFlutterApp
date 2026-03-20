# 💬 Minimal Chat App

A sleek, minimal chat application built using **Flutter** and **Firebase**. This project implements real-time messaging, user authentication, and a dynamic theme-switching system (Light/Dark mode).

[![Repo Link](https://img.shields.io/badge/GitHub-SocialMediaFlutterApp-blue?style=flat-square&logo=github)](https://github.com/shubham230523/SocialMediaFlutterApp)

## 🚀 Features

- **Authentication**: Secure Login and Sign-up using Firebase Auth (Email/Password).
- **Real-time Chat**: Instant messaging powered by Cloud Firestore.
- **User Directory**: Automatically lists all registered users (excluding the current user) to start new conversations.
- **Theming**: Toggle between Light and Dark modes using the `Provider` package.
- **Smooth UI**: 
  - Custom components for text fields and buttons.
  - Auto-scroll to the latest message when sending/receiving or opening the keyboard.
  - Interactive navigation drawer and settings page.
- **Responsive Design**: Minimalist aesthetic with a focus on usability.

## 🛠️ Tech Stack

- **Framework**: [Flutter](https://flutter.dev/)
- **Backend**: [Firebase](https://firebase.google.com/)
  - Firebase Authentication
  - Cloud Firestore
- **State Management**: [Provider](https://pub.dev/packages/provider)
- **Icons**: Cupertino Icons & Material Icons

## 📦 Getting Started

### Prerequisites
1. Install [Flutter SDK](https://docs.flutter.dev/get-started/install).
2. Set up a [Firebase Project](https://console.firebase.google.com/).
3. Install the Firebase CLI: `npm install -g firebase-tools`.

### Setup
1. **Clone the repository:**
   ```bash
   git clone https://github.com/shubham230523/SocialMediaFlutterApp.git
   cd SocialMediaFlutterApp
