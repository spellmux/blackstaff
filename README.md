# Blackstaff Macropad

**Blackstaff** is a custom-built ESP32 macropad designed for smart home control, media automation, and TTRPG immersion. Inspired by arcane themes and powered by ESPHome, it combines a hand-wired numpad layout, rotary encoders, an OLED screen, and multi-mode logic to create a uniquely powerful interface for Home Assistant.

---

## ✨ Features

- 🖥️ OLED Display (SSD1306) with arcane-style animations
- 🎛️ Rotary encoder for volume, brightness, or contextual control
- 🎹 25-key hand-wired matrix keypad with multi-click input (click, double click, hold)
- 🔋 Battery-powered with MAX17048 fuel gauge integration
- 🔄 Idle screen animations, startup effects, and wake/sleep dimming
- 🧠 Mode switching for:
  - Music control (playlists, shuffle, radio)
  - Lighting automation
  - Dice roller for D&D sessions
  - Ambient/SFX channel controls
  - Diagnostic output and future expansion

---

## 🔧 Hardware Overview

- **ESP32 Feather** (or equivalent)
- **SSD1306 128x64 OLED Display**
- **MAX17048 LiPo Fuel Gauge**
- **25-key matrix keypad** (hand-wired)
- **Rotary encoder** with push-button support
- **LiPo battery** and charging circuit
- **Custom 3D-printed enclosure**
- **Optional**: Small speakers + passive radiators for local audio feedback

---

## 📁 Project Structure


---

## 📷 Demo Preview

_(Coming soon: photos and video showcasing dice rolls, encoder interactions, and arcane effects.)_

---

## 📜 Attribution

This project builds on the excellent work of others and is licensed to respect their contributions:

### Enclosure Design
- Based on the [Bignum Hot-Swappable and Hand-Wired Numpad Macropad](https://makerworld.com/en/models/610097-bignum-hot-swappable-and-hand-wired-numpad-macropa)  
  by [pokzy](https://makerworld.com/en/u/pokzy), licensed under  
  [Creative Commons Attribution-NonCommercial-ShareAlike 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).

  Modifications include support for:
  - OLED mounting
  - Dual rotary encoders
  - Internal battery space
  - Feather microcontroller standoffs

### Configuration Code
- ESPHome YAML adapted from [ESPDeck](https://github.com/AeroSteveO/EspDeck) by [AeroSteveO](https://github.com/AeroSteveO), licensed under the MIT License.  
  Modifications include multi-mode support, advanced display scripting, idle timers, dice logic, and battery state management.

---

## ⚖️ License

- **Enclosure and Hardware**:  
  [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

- **Original Blackstaff Code and Content**:  
  [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

- **ESPDeck-Derived Code**:  
  [MIT License](https://opensource.org/licenses/MIT)

See [`LICENSE.md`](LICENSE.md) for full details.

---

## 🔮 Future Plans

- GitHub Pages build guide with schematics and walkthroughs
- Expanded FoundryVTT integration
- Larger screen upgrade with mode-select menu
- Soundboard-style SFX triggers


---

## 📬 Contact

This project is a personal build but is shared for learning, collaboration, and fun.  
Feel free to open an issue or discussion if you’d like to contribute, remix, or just say hello.


