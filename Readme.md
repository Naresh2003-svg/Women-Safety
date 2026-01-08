# Stree Raksha - Personal Safety Companion

## 📌 Problem Statement
Safety in public spaces and during late-night transit remains a significant concern. In emergency situations, victims often lack the time or ability to manually send multiple updates, call for help, and document evidence simultaneously. Existing solutions often fail when the app is minimized or the screen is locked.

## 💡 Solution Overview
**Stree Raksha** is a high-reliability personal safety app designed for immediate and automated distress response. 

### Core Features:
* **One-Touch SOS:** Instantly triggers a high-decibel siren and auto-dials emergency contacts.
* **Automated Background Tracking:** Utilizing a **Foreground Service**, the app sends automated SMS updates with live location links every 30 seconds.
* **Persistent Reliability:** Designed to bypass modern Android battery optimizations, ensuring the safety loop stays active even if the app is minimized.
* **Evidence Capture:** Automatically triggers background media/photo capture when SOS is initiated to preserve evidence.
* **Premium UI/UX:** Features a "Halo" pulse animation, haptic feedback, and a clean Material 3 interface for stress-free interaction.

## 🛠️ Setup & Run Instructions

### Prerequisites:
* Android Studio Ladybug (2024.x) or newer.
* Android Device/Emulator running **API 34 (Android 14)** or higher.
* Active SIM card (for SMS and Call features).

### Installation:
1.  **Clone the Repo:**
    ```bash
    git clone [https://github.com/yourusername/StreeRaksha.git](https://github.com/Naresh2003-svg/Women-Safety.git)
    ```
2.  **Open Project:** Open Android Studio and select `File > Open` to navigate to the cloned folder.
3.  **Sync Gradle:** Allow the IDE to download the Material Design and Guava dependencies.
4.  **Permissions:** Upon first launch, grant Location, SMS, Camera, and Phone permissions.
5.  **Run:** Click the `Run` button (Green Play Icon) to install on your device.

## 🏗️ Technical Architecture

The app leverages a specialized **Foreground Service** to maintain a "Special Use" type connection, allowing the 30-second SMS timer and Camera capture to function without being killed by the Android OS system.

## 👥 Team Details
* **Lead Developer:** Naresh N
* **Documentation:** Nithin D
* **UI/UX Design:** Chetan M 
* **Error Fixing:** Srujan P

---
*Developed with a mission to ensure every woman feels safe, tracked, and protected.*
