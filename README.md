# Castor (Beta) 📱✨

A sleek, borderless, low-latency Android screen mirroring desktop application for Windows built with WPF and scrcpy.

![Platform](https://img.shields.io/badge/Platform-Windows-0078D6?style=for-the-badge&logo=windows)
![Status](https://img.shields.io/badge/Status-Beta%20v1.0-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

---

## 🌟 Key Features

- **Floating & Borderless Design:** macOS-inspired rounded corners, dark acrylic aesthetic, and traffic-light window controls (Close, Minimize, Center).
- **Responsive Sizing:** Automatically launches at **~85% of your screen's work area height**, perfectly centered on any display.
- **Aspect-Ratio Preserving Resizing:**
  - **Resize Grip:** Drag the bottom-right corner grip (`⤡`) to resize up or down smoothly.
  - **Mouse Wheel Scaling:** Hold `Ctrl + Scroll Wheel` (or scroll on the hover bar) to quickly scale the mirror size without distortion.
- **Smart Hover Navigation:** Hover over the top of the window to reveal the title bar and controls; moves out of the way for a clean view.
- **Auto-Detection & Reconnect:** Automatically detects when an Android device is plugged in via USB and begins mirroring immediately.
- **Ultra-Low Latency:** Powered by `scrcpy` 5.x for fluid, real-time interaction.
- **Full Mouse & Keyboard Control:** Click, scroll, drag, and type directly from your desktop.

---

## 📥 Download & Usage

1. Go to the [Releases](https://github.com/Murreaa/Castor/releases) section on the right side of this repository.
2. Download the latest **`Castor-v1.0.0-beta-win-x64.zip`**.
3. Extract the ZIP to any folder and run **`Castor.exe`**.

### Prerequisites
- **Android Device:**
  - Enable **Developer Options** > **USB Debugging**.
  - *(For Xiaomi / MIUI / HyperOS)* Also enable **USB Debugging (Security settings)** to allow input simulation.
- Connect your phone to your PC with a USB cable.

---

## 🎮 Shortcuts & Controls

| Action | Control |
|---|---|
| **Move Window** | Drag the top bar (`⠿ Move`) or click and drag the placeholder area |
| **Resize Mirror** | Drag the bottom-right corner grip or use `Ctrl + Mouse Wheel` |
| **Center Window** | Click the Green traffic button or right-click > "Center Window" |
| **Minimize** | Click the Yellow traffic button |
| **Close** | Press `Esc` or click the Red traffic button |
| **Reconnect** | Click the "Reconnect" button anytime |

---

## 📄 License
This project is licensed under the MIT License.
