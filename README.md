# Quadever Scrcpy v3.3.1

A premium, modern, and high-performance GUI wrapper for **scrcpy** (Android Screen Mirroring).

Developed with a focus on fluid user experience, this tool allows you to easily display, mirror, and completely control Android devices over USB or Wi-Fi with zero configuration hassle.

---

## Key Features

- **Sleek, Modern Slate Theme:** Styled with a premium dark Slate-900 / Slate-800 visual system for maximum visual comfort and premium aesthetics.
- **Fluid & Non-Blocking GUI:** Built with an asynchronous multithreaded architecture. Operations like scanning devices, connecting, and sending key injections run in the background, keeping the GUI highly responsive at all times.
- **Remote Quick Controller:** Control your physical phone directly from the GUI with custom keys:
  - 📱 Power Toggle
  - 🔓 Screen Unlock / Keyguard
  - 🏠 Home button
  - 🔙 Back button
  - 📋 Recents menu switcher
  - 🔊 Volume Up / Volume Down
- **Bandwidth & Performance Control:** Configure max resolution scaling (Original, 1920, 1600, 1280, 1024, 800) to optimize stream speed and frame rates over wireless connections.
- **Flexible Source Selection:** Mirror the screen, back camera, front camera, or capture microphone audio only.
- **One-Click Wi-Fi Transition:** Retrieve device IP, enable TCP/IP on port 5555, and connect wirelessly without typing console commands.
- **Advanced Adjustments:** Easily tweak bitrates, rendering drivers (auto, opengl, direct3d, software), camera aspect ratios, orientation locks, always-on-top behavior, and recording paths.

---

## Project Structure

```
Quadever_Scrcpy/
├── QuadeverScrcpy.exe        # Main Application
├── adb.exe                   # Android Debug Bridge (ADB) executable
├── scrcpy.exe                # Core scrcpy utility engine
├── icon.ico / icon.png       # Assest
├── lib/
│   ├── library.zip          
│   └── python312.dll        
    ├── __main__scrcpygui.py  
    ├── build_and_replace.py  
    
```

## Requirements

1. **Android Device:** Enable **USB Debugging** in Developer Options on your phone.
2. **Windows OS:** Run the application directly on Windows 10/11.

---

## License & Credits

- GUI & Modernization by **Samir Alam**
- Powered by [scrcpy](https://github.com/Genymobile/scrcpy) by Genymobile.
