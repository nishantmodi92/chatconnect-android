 # 🔐 ChatConnect – Encrypted Real-Time Chat App  

<p align="center">
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" />
  <img src="https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" />
  <img src="https://img.shields.io/badge/Hilt-DI-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Crash--Free-99.9%25-success?style=for-the-badge" />
</p>

> A **scalable, encrypted real-time chat app** built with **Kotlin, Jetpack Compose & Firebase**, delivering **25K+ messages/day**, **DAU ↑25%**, and **99.9% crash-free sessions**.

---

## 📱 Features  

- 🔒 **End-to-End Encryption** – Private & group chats secured  
- 🟢 **Live Presence** – Typing indicator, last seen, online/offline  
- 🔔 **Smart Notifications** – FCM-powered, user/topic-based  
- 🌗 **Dark/Light Mode** – Adaptive Material You design  
- 🎙 **Rich Media Sharing** – Images, audio, docs, links  
- 💬 **Group Chats** – Admin roles & member management  
- 📂 **Offline Sync** – Room DB + WorkManager resilience  
- 🔄 **Background Workers** – Auto retry for failed messages  
- 🎨 **Smooth Animations** – Compose transitions for chat  
- 🧑‍🤝‍🧑 **Scalable** – Tested for **25K+ daily messages**  

---

## 📊 Business Impact  

- 📈 **+25% DAU** through engaging notifications  
- 💬 **25K+ messages/day** handled seamlessly  
- 🚀 **30% faster cold start** with performance tuning  
- 🧪 **99.9% crash-free sessions** (Firebase Crashlytics)  
- 🔐 **Improved retention** with secure & intuitive UX  

---

## ⚙️ Tech Stack  

**Language & Core**  
`Kotlin` · Coroutines · Flow  

**UI & Design**  
`Jetpack Compose` · Material 3 · Accompanist  

**Backend**  
`Firebase Auth` · `Firestore` · `Firebase Storage` · `Cloud Messaging (FCM)`  

**Architecture**  
MVVM · Clean Architecture · Repository Pattern  

**Dependency Injection**  
Dagger-Hilt  

**Async & Workers**  
Coroutines · WorkManager  

**Local DB**  
Room (offline-first persistence)  

**Networking**  
Retrofit (for avatars & link previews)  

**Build & CI/CD**  
Gradle · GitHub Actions  

---

## 🧠 Architecture Overview  

```mermaid
flowchart TD
    UI[Jetpack Compose UI] --> VM[ViewModel (StateFlow, LiveData)]
    VM --> UC[Use Cases (Business Logic)]
    UC --> REPO[Repository Layer]
    REPO --> DB[Room Database (Offline-First)]
    REPO --> FIREBASE[Firebase: Auth · Firestore · Storage · FCM]

✅ UI Layer (Compose) → Declarative, reactive UI
✅ ViewModel → Manages state with StateFlow
✅ Use Cases → Encapsulated business logic
✅ Repository → Combines local (Room) + remote (Firebase)
✅ Offline-First → WorkManager ensures resilience

🛠 Setup Instructions
🔹 Prerequisites

Android Studio Ladybug | 2024.2.1+

JDK 17+

Firebase project (Firestore, Auth, Storage, FCM)



🔹 Clone & Import
git clone https://github.com/nishantmodi92/ChatConnect.git


Open in Android Studio → Sync Gradle

🔹 Firebase Setup

Enable Auth (Email/Google Sign-In)

Enable Firestore DB (Production mode)

Enable Cloud Messaging (FCM)

Download google-services.json → Place in /app/

🔹 Run the App

Select Emulator/Device → ▶ Run

🎉 Enjoy real-time, encrypted messaging

🚀 Live Experience

✅ Real-time 1:1 & Group Chats
✅ Smart Push Notifications
✅ Offline-First Messaging
✅ Dark/Light Mode
✅ Rich Media Sharing

🔗 Links
📂 GitHub Repo
🌐 Portfolio Website

<p align="center"><b>✨ ChatConnect proves production-grade Android engineering with Compose, Firebase & scalable clean architecture ✨</b></p> ```








