# ⚡ LK PRO ADB TOOLS v4.2

A powerful, modern, and user-friendly **Android Debugging Suite** built with Python and Tkinter.

---

## 📖 Introduction

**LK PRO ADB TOOLS** is a comprehensive GUI application designed to simplify Android device management, debugging, and automation using ADB (Android Debug Bridge).

Whether you're a developer, tester, or power user, this tool provides an intuitive interface to perform complex ADB operations with just a few clicks — no command-line expertise required.

### ✨ Key Features

- **📱 Device Management**
  - List devices and get full device information
  - Battery status, reboot, restart ADB server

- **🔌 WiFi Debugging**
  - Enable WiFi ADB (TCP/IP mode)
  - Connect to devices wirelessly
  - Disconnect and manage connections

- **📁 File Manager**
  - Pull/Push files between PC and Android
  - List SD Card contents
  - Delete files remotely

- **📦 App Management**
  - List installed apps (user + system)
  - Install/uninstall APKs
  - Clear app data, disable apps

- **⌨️ Input Simulation**
  - Send text input
  - Tap and swipe gestures
  - Volume control

- **🎥 Media Tools**
  - Take screenshots
  - Record screen (up to 60 seconds)
  - Launch **scrcpy** for screen mirroring

- **📤 Export Tools**
  - Export Contacts to clean CSV
  - Export SMS to clean CSV
  - Full device backup

- **⚙️ Advanced Features**
  - Live Logcat
  - CPU/Memory monitoring
  - Custom ADB command terminal

- **💻 Live Terminal Output**
  - Real-time command execution logs
  - Color-coded output (success/error)
  - Copy and clear functionality

---

## 🛠️ Technologies Used

- **Python** with **Tkinter** for the GUI
- **ADB** (Android Debug Bridge) commands
- **subprocess** for running shell commands
- **threading** for non-blocking operations
- **CSV** module for clean data exports

---

## 🚀 How to Use

1. **Prerequisites**
   - Install [ADB](https://developer.android.com/tools/adb) on your system
   - Enable **USB Debugging** on your Android device
   - (Optional) Install **scrcpy** for screen mirroring

2. **Run the Tool**
   ```bash
   python lk_pro_adb_tools.py
   ```

3. Connect your Android device via USB and authorize ADB debugging.

---

## 📂 Project Structure

```
.
├── screenshots/      # Auto-saved screenshots
├── recordings/       # Screen recordings
├── backups/          # Device backups (.ab files)
├── apks/             # (Optional) APK storage
├── pulled_files/     # Files pulled from device
├── exports/          # CSV exports (contacts, SMS)
└── lk_pro_adb_tools.py   # Main application
```

---

## 🎨 UI Highlights

- Dark modern theme
- Responsive layout with tabs
- Live terminal with timestamps and color coding
- User-friendly dialogs and confirmations
- Unicode-safe command execution

---

## 📌 Version

**v4.2** - Enhanced stability, improved Unicode handling, better error management, and refined export features.

---

## 🤝 Contributing

Feel free to fork the project and submit pull requests for new features or bug fixes.

## 📄 License

This project is open-source. Feel free to use and modify it.

---

**Made with ❤️ for the Android community**

Happy Debugging! 🔧
