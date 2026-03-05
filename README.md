# ⏱️ CountDown Timer Android App
A simple and efficient CountDown Timer app built using Kotlin and XML. This app allows users to set a custom countdown duration, manage the timer state with start, pause, and resume features, and even extend the time dynamically during gameplay or tasks.

# ✨ Features
- 🕒 **Custom Timer Setup** – Easily set your desired countdown duration via a clean input dialog.
- ⏯️ **Play/Pause/Resume** – Seamlessly control the timer flow with a dynamic action button.
- 🔄 **Quick Reset** – Reset the timer and progress bar back to the initial state with a single tap.
- ➕ **Add Extra Time** – Instantly add 15 seconds to the current countdown for quick extensions.
- 📊 **Visual Progress Tracking** – A circular progress bar provides a real-time visual representation of the remaining time.
- 🎨 **Custom UI Design** – Features custom-designed progress bar backgrounds and Material Design components for a modern look.
- 🔔 **Interactive Feedback** – Helpful toast notifications for "Time's Up" and status updates.

# 📸 Screenshots
<img width="377" height="797" alt="home screen" src="https://github.com/user-attachments/assets/3c4824c5-b37e-4cc5-be3e-c2f066f99f6f" />
<img width="376" height="797" alt="timer" src="https://github.com/user-attachments/assets/48dae204-ab1d-4031-99c3-c95ba7d1bdfb" />

# ⚙️ Tech Stack
- **Language**: Kotlin
- **UI Framework**: XML (ConstraintLayout)
- **Architecture**: Standard Android Architecture
- **Logic**: `CountDownTimer` API for precise time management
- **UI Components**: Material Components, Circular ProgressBar, Custom Dialogs, ImageButtons

# 📂 Project Structure
- **com/betanooblabs/countdowntimer/**: Main package containing the application logic
- **MainActivity.kt**: Core activity managing timer states, UI updates, and user interactions
- **res/layout/activity_main.xml**: Main screen layout with progress bar and controls
- **res/layout/add_dialog.xml**: Custom dialog layout for inputting timer duration
- **res/drawable/**: Contains custom shapes for progress bars and button styles
- **res/values/**: Resource files for colors, themes, and strings

# 🚀 Getting Started
Follow these steps to run the project locally:
1. Clone the repository
2. Open the project in Android Studio
3. Sync the project with Gradle files
4. Run the app on an emulator or physical device

# 🔧 Requirements
- Android Studio Hedgehog or later
- Minimum SDK: 23
- Target SDK: 36
- Kotlin 1.9.0 or higher

# 🤝 Contributing
Contributions are welcome! If you'd like to fix a bug or add a feature, feel free to fork the repository and submit a pull request.
