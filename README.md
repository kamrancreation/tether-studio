# Tether Studio

Mirror your phone's screen and sound to your Windows PC over a USB cable or Wi-Fi. No account, no server, nothing leaves your PC.

**[Download for Windows](https://github.com/kamrancreation/tether-studio/releases/latest/download/TetherStudio-Setup.exe)** · Windows 10/11 64-bit · Free

## What it does
- **Android:** plug in, allow USB debugging once, and the screen and sound appear on the PC. No app on the phone. Up to the phone's native resolution, 30–120 fps, H.264 or H.265, decoded on your GPU. Optional mouse and keyboard control (off by default).
- **iPhone:** mirror only, with the free Tether iPhone app over USB. For full 1080p or 4K, use a USB-C to HDMI adapter and a capture card.
- **For streamers:** a clean mirror window for OBS Window Capture, phone frames, green screen or transparent background, full screen on any monitor, a virtual webcam ("Tether Mirror Camera"), rotation, screenshots, and a sound check.

## Install
1. Download `TetherStudio-Setup.exe` from the [latest release](https://github.com/kamrancreation/tether-studio/releases/latest).
2. Windows SmartScreen may warn because the installer isn't code-signed yet. Click **More info → Run anyway**.
3. Follow the first-time setup in the app.

## Included third-party components
- [scrcpy server](https://github.com/Genymobile/scrcpy) v4.1, Apache License 2.0
- [Softcam](https://github.com/tshino/softcam) v1.8.1, MIT License (renamed "Tether Mirror Camera")
- Android SDK Platform-Tools (adb) by Google, see NOTICE in the app's `resources/platform-tools` folder
- [Electron](https://www.electronjs.org/), MIT License

This repository hosts releases only.
