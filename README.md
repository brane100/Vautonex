# Vautonex

**Vautonex** is a lightweight Android app that toggles Wi-Fi and mobile data on or off using offline voice commands. Designed for privacy, speed, and accessibility, it enables hands-free control of connectivity without relying on cloud services.

> ⚠️ **Status:** Under active development. First release coming soon.

---

## Features

- Offline voice recognition (no internet required)  
- Toggle Wi-Fi and mobile data with simple commands  
- Instant feedback via toast, vibration, or icon change  
- Minimal UI for fast access and low resource usage  
- No background tracking or data collection

---

## Example Commands

- “Turn off Wi-Fi”  
- “Enable mobile data”  
- “Switch Wi-Fi on”  
- “Disable data”

---

## Tech Stack

- **Flutter** for UI and cross-platform structure  
- **Android native APIs** for connectivity control  
- **Local speech recognition** (e.g., Vosk, PocketSphinx)  
- Optional integration with system shortcuts or Tasker

---

## Permissions

- `ACCESS_WIFI_STATE`  
- `CHANGE_WIFI_STATE`  
- `ACCESS_NETWORK_STATE`  
- `MODIFY_PHONE_STATE` *(if targeting mobile data)*  
- `RECORD_AUDIO` *(for voice input)*

---

## Installation

1. Clone the repository  
2. Run `flutter pub get`  
3. Connect your device and run `flutter run`  
4. Grant required permissions on first launch

---

## Roadmap

- Add support for airplane mode and Bluetooth  
- Expand voice command vocabulary  
- Optional UI toggle buttons  
- Localization for multilingual voice commands

---

## License

MIT License. See `LICENSE` file for details.
