# OneUp 🚀

**OneUp** is a modern, gamified push-up tracker designed to help you build a habit of daily exercise.
Built with **Vibe Coding**.

## 📱 Mobile App (Android)

OneUp is available as a native Android application!

### How to Install (User)
1.  **Download the APK**: Get the `OneUp.apk` file.
2.  **Allow Unknown Sources**: On your phone, if prompted, allow installation from your file manager or browser.
3.  **Install**: Open the APK file and tap "Install".

---

## 🛠️ Installation (Developer)

If you want to build the app yourself or contribute:

### Prerequisites
- Node.js installed.
- Android Studio installed (for mobile build).

### Setup
1.  **Clone the repository**
    ```bash
    git clone https://github.com/LucasM548/OneUp.git
    cd OneUp
    ```

2.  **Install Dependencies**
    ```bash
    npm install
    ```

3.  **Run Web Version** (Local Development)
    ```bash
    npm run dev
    ```

### 🤖 Build for Android

1.  **Build the Web Assets**
    ```bash
    npm run build
    ```

2.  **Sync with Capacitor**
    ```bash
    npx cap sync
    ```

3.  **Open in Android Studio**
    ```bash
    npx cap open android
    ```
    - Once Android Studio opens, wait for Gradle to sync.
    - Connect your phone via USB.
    - Click the **Run (Play)** button to install on your device.

---

## 🏗️ Built With
- **React + Vite** - Fast web framework.
- **Capacitor** - Cross-platform native runtime.
- **Tailwind-free** - Custom CSS for maximum style control.
