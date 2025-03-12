# 📸 Gramify - Social Media Platform

## Overview
Gramify is a **social media platform** built using **Android (Java & XML)** that allows users to share posts, connect with friends, and interact with a dynamic feed. The app focuses on a smooth user experience, secure authentication, and real-time interactions.

## Features
- **User Authentication**
  - Sign up & login using email/password authentication.
  - Profile setup with bio, profile picture, and personal details.

- **Social Feed**
  - Post images, captions, and hashtags.
  - Like, comment, and share posts.

- **User Interaction**
  - Follow/unfollow users.
  - View followers and following lists.
  - Chat and send direct messages.

- **Notifications**
  - Real-time notifications for likes, comments, and new followers.

## Tech Stack
- **Framework:** Android (Java, XML)
- **Backend:** Firebase (Firestore & Realtime Database)
- **Authentication:** Firebase Authentication
- **Storage:** Firebase Storage (for image uploads)
- **Push Notifications:** Firebase Cloud Messaging (FCM)
- **UI Design:** Material Design Components

## Installation & Setup
### Prerequisites
Ensure you have the following installed:
- **Android Studio** (latest version)
- **Java SDK**
- **Firebase Project** (set up in Firebase Console)

### Clone the Repository
```sh
git clone https://github.com/yourusername/Gramify.git
cd Gramify
```

### Install Dependencies
1. Open the project in **Android Studio**.
2. Sync Gradle dependencies.
3. Connect the app with **Firebase**:
   - Download `google-services.json` from Firebase Console.
   - Place it inside `app/` directory.

### Run the Application
```sh
Run the project on an emulator or a physical device via Android Studio.
```

## Folder Structure
```
app/
│── src/
│   ├── main/
│   │   ├── java/com/yourcompany/gramify/ # Main source code
│   │   ├── res/layout/                   # XML UI files
│   │   ├── res/drawable/                 # Icons and images
│   │   ├── res/values/                    # Strings, colors, styles
│   │   ├── FirebaseConfig.java           # Firebase authentication and database
│   │   ├── adapters/                     # RecyclerView adapters
│   │   ├── models/                       # Data models (User, Post, Comment)
│   │   ├── activities/                   # Main UI screens (Login, Feed, Profile)
│   │   ├── fragments/                    # Fragments for different views
```

## Contributing
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch`
3. Commit changes: `git commit -m 'Add new feature'`
4. Push to the branch: `git push origin feature-branch`
5. Open a Pull Request.

## License
This project is licensed under the MIT License.

## Contact
For any queries, contact kshitijdesai179@gmail.com.

