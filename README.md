# ⚡ MakerOS

> A minimal, glassmorphism-focused Debian derivative designed for technical professionals.

![Version](https://img.shields.io/badge/version-1.0.0-84cc16?style=for-the-badge&logo=linux)
![Base](https://img.shields.io/badge/base-Debian%20Bookworm-0f172a?style=for-the-badge&logo=debian)
![WM](https://img.shields.io/badge/wm-i3wm-0f172a?style=for-the-badge)

## 🎨 Aesthetic: CodeMakers Design System
- **Colors:** Lime (`#84cc16`) & CyberDark (`#020617`)
- **Typography:** Space Grotesk
- **UI:** Glassmorphism (Picom Dual Kawase Blur)
- **Shell:** Starship Prompt
- **Dashboard:** Lua-based Conky HUD

## 🛠️ Stack
- **Window Manager:** i3wm (gaps, no titlebars)
- **Bar:** Polybar (floating modules)
- **Launcher:** Rofi (card style)
- **Compositor:** Picom
- **Terminal:** Kitty

## 🚀 How to Build

Requirements: `apt install live-build debootstrap squashfs-tools`

```bash
# 1. Clone the repo
git clone https://github.com/marciolopesjr/makerOS.git
cd makerOS

# 2. Config (if needed)
lb config

# 3. Build
sudo lb build

