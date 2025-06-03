# Blackstaff Macropad

**Blackstaff** is a custom ESP32-powered macropad designed for dynamic control of Home Assistant automations, media playback, and tabletop RPG utilities. Inspired by fantasy themes and DIY electronics, it combines a minimalist hand-wired numpad layout with a smart OLED UI, battery power, and multi-mode logic for lighting, sound, and dice rolling.

---

## ✨ Features

- **OLED display (SSD1306 128x64)** with animations, dice results, and status labels
- **Rotary encoders** for precise volume and light control
- **Matrix keypad (12 keys)** with multi-click input (click / double click / long hold)
- **Battery-powered with fuel gauge** (MAX17048)
- **Multiple operational modes**: Music, Lighting, SFX, Ambient, Dice Roller, Diagnostics
- **Home Assistant integration** via ESPHome
- **Sleep/wake display animations** with arcane flair

---

## 🔧 Hardware

- ESP32 Feather (or compatible)
- SSD1306 128x64 OLED Display
- MAX17048 LiPo fuel gauge
- 12-key matrix keypad (hand-wired)
- 2x Rotary encoders with push buttons
- Custom 3D-printed enclosure
- Internal LiPo battery
- Passive speakers and custom keycaps (optional)

---

## 📁 Folder Structure
Blackstaff/
├── config/ # ESPHome YAML configs
├── docs/ # Diagrams, wiring schematics
├── images/ # XBM image assets for display
├── media/ # Demo photos and video clips
├── enclosure/ # STL files for modified case
├── LICENSE.md # License for hardware
└── README.md
