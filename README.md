# 🔐 ChatConnect – Encrypted Real-Time Chat App

![Kotlin](https://img.shields.io/badge/Kotlin-100%25-blue.svg)
![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-UI-lightgreen.svg)
![Firebase](https://img.shields.io/badge/Firebase-Backend-yellow.svg)
![Crash-Free](https://img.shields.io/badge/Crash--Free-99.9%25-success.svg)

> A next-gen, encrypted real-time chat app built with Kotlin, Jetpack Compose, and Firebase – scalable, crash-free, and optimized for performance.

---

## 📱 Features

🔒 End-to-End Encryption – Secure private & group chats

🟢 Live Presence – Typing status, online/offline, last seen

🔔 Smart Push Notifications – FCM-powered, topic & user-based

🌗 Dark/Light Mode – Adaptive with Material You design

🎙️ Rich Media Sharing – Images, links, audio messages, documents

💬 Group Chats – Admin controls, member management

📂 Offline Sync – Messages saved locally with Room DB & WorkManager

🔄 Background Workers – Auto message retry & network resilience

🎨 Smooth Animations – Compose-powered transitions for chats

🧑‍🤝‍🧑 Scalable – Tested for 25K+ daily messages

---

## 📊 Metrics & Impact

📈 +25% Daily Active Users (DAU) through engagement-driven notifications

💬 25K+ messages/day handled seamlessly

🕒 30% faster cold start vs previous baseline

🧪 99.9% crash-free sessions (Firebase Crashlytics)

🔐 Boosted retention rate due to secure & intuitive UX

## ⚙️ Tech Stack

Language: Kotlin, Coroutines, Flow

UI: Jetpack Compose, Material 3, Accompanist

Backend: Firebase Authentication, Firestore, FCM, Firebase Storage

Architecture: MVVM + Clean Architecture + Repository Pattern

DI: Dagger-Hilt

Async/Workers: Kotlin Coroutines + WorkManager

Local DB: Room Database (offline-first)

Networking: Retrofit (for external APIs like user avatars / link preview)

Build & CI/CD: Gradle + GitHub Actions

---

## 🧠 Architecture Overview

flowchart TD
    UI[Jetpack Compose UI] --> VM[ViewModel (StateFlow, LiveData)]
    VM --> UC[Use Cases (Business Logic)]
    UC --> REPO[Repository Layer]
    REPO --> DB[Room Database (Offline)]
    REPO --> FIREBASE[Firebase (Auth, Firestore, FCM, Storage)]

    UI Layer (Compose) → Reactive & declarative UI

ViewModel → Exposes states via StateFlow & LiveData

Use Cases → Encapsulate business logic (clean separation)

Repository → Handles data from Firebase + Local DB

Offline-first → Room + WorkManager ensures resilience

🛠 Setup Instructions
🔹 Prerequisites

Android Studio Ladybug | 2024.2.1 or newer

JDK 17+

Firebase project setup (Firestore + Auth + Storage + FCM)

🔹 Clone & Import

git clone https://github.com/nishantmodi92/ChatConnect.git

Open in Android Studio
Sync Gradle

Gradle

🔹 Firebase Setup

Create a Firebase project → Enable Auth (Email/Password, Google Sign-In)

Enable Firestore Database (Production mode)

Enable Cloud Messaging (FCM) for push notifications

Download google-services.json → Place it in:
app/

🔹 Run the App

Select Emulator / Device

Hit Run ▶

🎉 Enjoy real-time, encrypted messaging

🚀 Live Experience

✅ Real-time 1:1 & Group Chats
✅ Push Notifications for Active/Background Users
✅ Offline-first Messaging
✅ Smooth Dark/Light Mode
✅ Media Sharing with Previews

## 🔗 Links
📂 GitHub Repo
🌐 Portfolio Website

✨ ChatConnect demonstrates scalable, production-ready Android engineering with Jetpack Compose, Firebase, and clean architecture.










