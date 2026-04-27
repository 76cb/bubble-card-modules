# Fan Speed Visual Center

![Demo](demo.gif)

Advanced Bubble Card module for Home Assistant that provides dynamic fan control with automatic speed detection, per-speed animation, and fully unified color selection using native Home Assistant-style editor forms.

---

## ✨ Features

- Automatic fan speed detection:
  - Off
  - Low
  - Medium
  - High
- Dynamic UI styling based on current speed
- Per-speed animation control (fan spin speed)
- Active sub-button highlighting
- Optional glow effects for active state
- Off-state icon support
- Fully unified color system:
  - Preset (theme colors)
  - Color wheel (RGB picker)
  - Custom CSS / RGBA
  - Template support

---

## 📦 Installation

### Method — Import from YAML

1. Open Home Assistant
2. Go to **Bubble Card → Modules**
3. Click **Import from YAML**
4. Open this file:
   `fan_speed_visual_center.yaml`
5. Copy the contents and paste into the editor
6. Save

---

## 🧩 Usage

Example Bubble Card configuration:

```yaml
type: custom:bubble-card
card_type: button
entity: fan.your_fan
name: Fan
icon: mdi:fan
modules:
  - fan_speed_visual_center
