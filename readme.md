# ✈️ Android Flight Info UI App

This project is a simple Android application built using **Kotlin**, **Android Studio**, and **Backpack UI components**. The app displays flight details in a visually appealing format, demonstrating how to integrate third-party UI libraries and build structured layouts in Android.

---

## 📱 Features

- ✅ Built using Kotlin and Android Studio
- ✅ Clean and modern UI using Backpack components
- ✅ Displays:
  - ✈️ Flight Number
  - 🛫 Departure details (airport code + time)
  - 🛬 Arrival details (airport code + time)

---

## 🛠️ Tech Stack

- **Language:** Kotlin  
- **IDE:** Android Studio (Electric Eel recommended)  
- **Minimum SDK:** API 33 (Android Tiramisu)  
- **UI Library:** [Backpack by Skyscanner](https://github.com/Skyscanner/backpack-android)

---

## 🚀 Getting Started

### 1. Clone the Repository

bash
git clone https://github.com/your-username/flight-info-ui-app.git
cd flight-info-ui-app
2. Open in Android Studio
Launch Android Studio

Select Open Project

Navigate to the cloned repo

✅ Make sure Android Studio is up-to-date (recommended: Electric Eel)

3. Run the App
Click the Run ▶️ button in Android Studio

Use either a connected device or the built-in emulator

📦 Adding Backpack Dependency
This app uses Backpack UI components. To add it manually:

Open build.gradle (Module: app)

Inside dependencies block, add:

gradle
Copy
Edit
implementation 'net.skyscanner.backpack:backpack-android:43.0.0'
Click "Sync Now" when prompted.

🧩 UI Structure
activity_main.xml includes:
BpkCardView for each section

BpkText for displaying text (like "Departure", "Arrival", etc.)

LinearLayout for structured vertical stacking

Proper constraints for clean design and alignment

🧑‍🎨 Components
Flight Card

Flight Number

Departure Card

3-digit Airport Code (e.g., JFK)

Departure Time (e.g., 09:00 AM)

Arrival Card

3-digit Airport Code (e.g., LAX)

Arrival Time (e.g., 12:30 PM)

All components styled using Backpack’s @style/bpkTextHeading1 and cornerStyle="large"

🧪 Troubleshooting
If Backpack components don’t render properly in the design view:

Try switching to Android Studio Electric Eel version

Refer to the known Backpack bug tracker

✅ Completion Checklist
 Android Studio installed and set up

 Kotlin project created with Empty Activity

 Backpack added via Gradle

 All required UI components designed

 App tested via emulator

 Code pushed to public GitHub repository
