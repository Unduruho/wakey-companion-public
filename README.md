### A lightweight companion app for Wakey – Wake On LAN.

The Wakey Companion App allows your Android Wakey app to interact with your Windows PC over the local network. It enables device status monitoring and remote control features such as lock, sleep, shutdown, and reboot. Designed to run silently in the background with minimal system resources, it integrates seamlessly with the Wakey Android app.

### Features
- Runs as a background Windows service with a system tray icon.
- Automatic startup on Windows login.
- Provides remote commands via HTTP API:
  `Lock`
  `Sleep`
  `Shutdown`
  `Reboot`
  `Status (ON/OFF)`

- Minimal memory footprint and CPU usage.
- No user interface besides the system tray icon.
- Fully compatible with Wakey Android app for device discovery and remote control.

### How It Works
1. Install and run the companion app on your Windows PC.
2. The app requests admin privileges to allow system control commands.
3. It runs silently in the background, accessible via the system tray.
4. Once running, the Android app can detect the PC over the local network and show its status.

From Wakey Android, you can:
- Wake the PC (if Ethernet/WoL supported).
- Lock, Sleep, Shutdown, or Reboot the PC directly.

### Installation
Download the latest wakey.exe release from this GitHub page.
Run the .exe file and grant admin privileges.
Confirm that the system tray icon appears.
The app will automatically start on future Windows logins.
