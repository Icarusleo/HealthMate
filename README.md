# HealthMate 🏥

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Platform](https://img.shields.io/badge/platform-Android-green.svg)
![Language](https://img.shields.io/badge/language-Java-orange.svg)
![Build](https://img.shields.io/badge/build-Gradle-blue.svg)

HealthMate is a native Android application designed as a personal health companion. It allows users to track their daily wellness, manage medical appointments, and keep a digital record of their vital signs through an intuitive and user-friendly mobile interface.

## 🌟 Key Features

- **Personal Health Dashboard:** Real-time tracking of health metrics and daily goals.
- **Medical Appointments:** A dedicated system to schedule, view, and manage doctor visits.
- **Vitals Tracking:** Log and monitor blood pressure, heart rate, and other essential health data.
- **Profile Management:** Securely store and update personal health information and medical history.
- **Local Persistence:** Reliable data management using modern Android storage practices.

## 🛠️ Technology Stack

- **Language:** [Java](https://www.java.com/) (Native Android Development)
- **Minimum SDK:** API 21+ (Android 5.0 Lollipop)
- **UI Design:** XML Layouts with Material Design components.
- **Database:** SQLite / Room Persistence Library (if applicable for local data).
- **Build System:** Gradle.
- **IDE:** Android Studio.


## ⚙️ Installation & Setup
Prerequisites
- Android Studio (Ladybug or newer recommended).

- Java Development Kit (JDK) 11 or 17.

- An Android Emulator or a physical Android device.

Steps
- Clone the repository:

- Bash
- git clone [https://github.com/mobilodevi2025-healthmate/HealthMate.git](https://github.com/mobilodevi2025-healthmate/HealthMate.git)
- Open the Project:

- Launch Android Studio.

- Select "Open an Existing Project".

- Navigate to the cloned folder and select the HealthMate directory.

- Sync Gradle:

- Wait for Android Studio to finish the Gradle sync process and download necessary dependencies.

- Run the App:

- Click the "Run" button (green play icon) in the toolbar to build and install the app on your device/emulator.
## 📸 Screenshots
  - <img width="1066" height="1956" alt="image" src="https://github.com/user-attachments/assets/dfc4263b-211b-4004-b4fc-a92009a8397a" />
  - <img width="1034" height="2048" alt="image" src="https://github.com/user-attachments/assets/9e98f954-03de-45f9-b1e5-7446adcf891f" />
  - <img width="1039" height="2030" alt="image" src="https://github.com/user-attachments/assets/84a6507a-342f-4056-ac66-7ed2ef49a975" />
  



## 📂 Project Structure

```text
HealthMate/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/healthmate/     # Java source files (Activities, Adapters, Models)
│   │   │   ├── res/                     # Resources (Layouts XML, Drawables, Values)
│   │   │   └── AndroidManifest.xml      # App configuration and permissions
│   └── build.gradle                     # Module-level build configuration
├── gradle/                              # Gradle wrapper files
└── build.gradle                         # Project-level build configuration
