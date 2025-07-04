# advancedfuncapp

📱 Firebase Authentication Android App
A fully functional Android app using Java, XML, and Firebase Authentication to support email/password login and registration.




🚀 Features
🔐 Login and Register with Email/Password

✅ Firebase Authentication Integration

🧾 Real-time form validation

🔁 Screen-to-screen navigation

🏠 Home screen after login

📱 Built with Material Design in XML

🧠 Technologies Used
Layer	Tech Stack
Language	Java
UI Layout	XML + ConstraintLayout
Backend	Firebase Authentication
IDE	Android Studio (Meerkat FD)
Build System	Gradle (Kotlin DSL)

📂 Project Structure
pgsql
Copy
Edit
FirebaseAuthApp/
├── app/
│   ├── java/
│   │   └── com.example.advancedfuncapp/
│   │       ├── LoginActivity.java
│   │       ├── RegisterActivity.java
│   │       └── HomeActivity.java
│   ├── res/
│   │   └── layout/
│   │       ├── activity_login.xml
│   │       ├── activity_register.xml
│   │       └── activity_home.xml
│   └── AndroidManifest.xml
├── build.gradle.kts (Project + App)
├── google-services.json
└── gradle-wrapper.properties


⚙️ Setup Instructions
✅ Prerequisites: Android Studio + Firebase Account

Clone the repo

git clone https://github.com/your-username/firebase-auth-app.git
Register your app in Firebase Console

Enable Email/Password in Auth > Sign-in method

Download the google-services.json file

Place it inside:

app/google-services.json
Sync Gradle and Run

📄 Firebase Dependencies Used

implementation("com.google.firebase:firebase-auth:21.0.1")

📌 Key Files Explained
LoginActivity.java
Handles user sign-in using FirebaseAuth.

RegisterActivity.java
Handles user registration and validation.

HomeActivity.java
Displayed after successful login.

activity_login.xml / activity_register.xml / activity_home.xml
Material design UI screens for login, register, and home.

AndroidManifest.xml
Registers all activities and enables Internet permissions.

🧠 Learnings
Integration of FirebaseAuth in Android Studio

Connecting Java logic with Material UI

Managing Gradle plugins (Kotlin DSL)

Debugging and handling sync issues

📽️ Demo
Watch the demo video here:
📺 YouTube Demo : Garalapalli Veda sri

🧑‍💻 Author
Veda Sri Garalapalli
📧 vedagaralapalli@email.com
🔗 LinkedIn : https://www.linkedin.com/in/veda-sri-19743b367/
🐱 GitHub : https://github.com/Vedadev5

🪪 License
This project opened can used by everyone freely.

