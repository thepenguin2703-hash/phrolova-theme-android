# 🎴 Hiyuki Theme - Wuthering Waves

**A complete HyperOS 3 theme inspired by Hiyuki from Wuthering Waves**

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Platform](https://img.shields.io/badge/platform-HyperOS%203-red)

## 📋 Overview

This is a comprehensive Android theme for POCO devices running HyperOS 3, inspired by Hiyuki's elegant and mystical aesthetic from Wuthering Waves. The theme features red (#C41E3A) and white color schemes with smooth animations and minimalist design.

## 🎨 Theme Features

### Color Palette
- **Primary Red**: `#C41E3A` (Hiyuki's signature color)
- **Light Red**: `#E8A8B8` (Soft accents)
- **White**: `#F5F5F5` (Clean background)
- **Dark Red**: `#8B0000` (Shadows and contrast)
- **Off-white**: `#FAFAF8` (Secondary background)

### 🔧 Customized Components

✅ **Control Center**
- Red-themed quick settings
- Custom control center background
- Red accent icons on white background

✅ **Lock Screen**
- Hiyuki character wallpaper
- Custom lock widgets (clock, date)
- Themed lock icons with red accents
- Minimal notification display

✅ **Home Screen**
- Hiyuki-themed wallpaper
- Custom widgets (character, weather, calendar)
- App drawer with theme colors
- Smooth animations

✅ **System Icons**
- Status bar icons
- Navigation buttons
- System app icons

✅ **Battery Indicator**
- Animated charging effect with red glow
- Level-based color changes:
  - 0-20%: Red (critical)
  - 20-50%: Orange (low)
  - 50-80%: Yellow (medium)
  - 80-100%: Green (full)
- 20-frame smooth animation

✅ **Fingerprint Effects**
- Red scanning wave animation (20 frames)
- Success glow effect (Hiyuki character glow)
- Failed animation (red X)
- Particle effects

✅ **Settings UI**
- Red header background
- Themed toggles and switches
- Red accent colors
- Consistent with theme colors

✅ **Game Turbo Interface**
- POCO Game Turbo customization
- Performance monitoring UI (CPU, RAM, Temp, FPS)
- Red accent colors
- Transparent overlay layout

✅ **App Backgrounds**
- Consistent app background theme
- Red/white gradient effects
- Minimalist card design
- System apps customization

✅ **Hiyuki Widget**
- Custom character widget (2x2, 4x2, 4x4 sizes)
- Time and date display
- Weather integration
- Breathing and glow animations
- Interactive tap effects

## 📁 File Structure

```
hiyuki-theme/
├── theme-config.json                 # Main configuration
├── README.md                         # This file
├── control-center/
│   ├── colors.json
│   └── README.md
├── lockscreen/
│   ├── lock_config.json
│   └── README.md
├── homescreen/
│   ├── homescreen_config.json
│   └── README.md
├── system-icons/
│   ├── battery/
│   │   ├── battery_config.json
│   │   └── README.md
│   └── fingerprint/
│       ├── fingerprint_config.json
│       └── README.md
├── settings-ui/
│   ├── colors.json
│   └── README.md
├── game-turbo/
│   ├── game_turbo_config.json
│   └── README.md
├── app-backgrounds/
│   ├── app_config.json
│   └── README.md
└── widgets/
    └── hiyuki-widget/
        ├── widget_config.json
        └── README.md
```

## 🚀 Installation

### Method 1: Manual Installation (Recommended)
1. Download the theme files
2. Open **Themes** app on your POCO device
3. Go to **Local Themes** → **Import**
4. Select the `hiyuki-theme` folder
5. Tap **Apply**

### Method 2: Via File Manager
1. Copy the `hiyuki-theme` folder to `/sdcard/MIUI/theme/`
2. Open **Themes** app
3. Refresh the app (pull down to refresh)
4. Select **Hiyuki Theme** from available themes
5. Click **Apply**

### Method 3: Via ADB (Advanced)
```bash
adb push hiyuki-theme /sdcard/MIUI/theme/
```

## 📱 System Requirements
- **OS**: HyperOS 3 or later
- **Device**: POCO devices
- **RAM**: 2GB minimum
- **Storage**: 50MB free space
- **Tested on**: POCO F5 Pro

## 🎯 Supported Elements

| Component | Status | Details |
|-----------|--------|----------|
| Control Center | ✅ | Full customization |
| Lock Screen | ✅ | Wallpaper + widgets |
| Home Screen | ✅ | Wallpaper + widgets |
| System Icons | ✅ | Status bar icons |
| Battery | ✅ | Animated indicator + charging effect |
| Fingerprint | ✅ | Scan + success/fail animations |
| Settings | ✅ | UI colors + layout |
| Game Turbo | ✅ | Interface + overlays |
| App Backgrounds | ✅ | System apps + gradients |
| Widgets | ✅ | Hiyuki character widget |

## 🎨 Customization

Each component folder contains JSON configuration files. You can customize:

### Colors
Edit the color hex codes in:
- `control-center/colors.json`
- `settings-ui/colors.json`
- `game-turbo/game_turbo_config.json`

### Animations
Modify animation settings in:
- `system-icons/battery/battery_config.json`
- `system-icons/fingerprint/fingerprint_config.json`
- `widgets/hiyuki-widget/widget_config.json`

### Layout
Adjust positions and sizes in:
- `lockscreen/lock_config.json`
- `homescreen/homescreen_config.json`
- `game-turbo/game_turbo_config.json`

## 🔧 Troubleshooting

### Theme won't apply
- Ensure HyperOS 3 is fully updated
- Clear Themes app cache: Settings → Apps → Themes → Storage → Clear Cache
- Reboot your device
- Try Method 2 installation

### Missing elements
- Check file permissions (755 for folders, 644 for files)
- Verify all JSON files are valid
- Reinstall the theme
- Check available space

### Animations not working
- Enable animations in Settings → Display
- Increase animation speed in Developer Options
- Restart Themes app

### Widget not appearing
- Long press home screen → Widgets → Search "Hiyuki"
- Check if widget size matches your screen
- Reinstall theme and reboot

## 📝 Configuration Guide

### theme-config.json
Main configuration file with:
- Theme metadata (name, version, author)
- Device and OS target information
- Color scheme definition
- Component availability flags

### Component-specific configs
Each component has its own configuration file with:
- Color customization
- Animation settings
- Layout preferences
- Feature toggles

## 🎬 Features Detail

### Charging Animation
- High-intensity red glow (#C41E3A)
- 20 smooth animation frames
- Pulsing effect during charging
- Battery level-based color changes

### Fingerprint Effects
- **Scanning**: Circular red wave expanding from center
- **Success**: Character glow with red particles
- **Failed**: Red X shake animation
- **Colors**: All effects use theme red (#C41E3A)

### Game Turbo
- Compact overlay in top-right corner
- 90% opacity for visibility
- Real-time monitoring: CPU, RAM, Temp, FPS
- Smooth 300ms animations

### Hiyuki Widget
- Multiple sizes for flexibility
- Breathing animation in idle state
- Glow effect on tap
- Weather and date integration

## 📞 Support & Credits

### Credits
- **Character**: Hiyuki from Wuthering Waves
- **Game**: Wuthering Waves by Kuro Games
- **Developer**: @thepenguin2703-hash
- **Theme Platform**: HyperOS 3

### Getting Help
1. Check the README files in each component folder
2. Review the troubleshooting section above
3. Check file permissions and structure
4. Open an issue on GitHub with:
   - Device model (e.g., POCO F5 Pro)
   - HyperOS version
   - Problem description
   - Screenshots if possible

## 📄 License

MIT License - See repository for full license text

You are free to:
- Use this theme
- Modify and distribute
- Use for commercial purposes

Under the condition of:
- Keeping the license notice
- Crediting the original creator

## 🙏 Acknowledgments

Special thanks to:
- Kuro Games for Wuthering Waves
- POCO for HyperOS
- The Android theming community

---

**Made with ❤️ for Hiyuki fans using POCO devices with HyperOS 3**

*Last Updated: May 2026*
*Version: 1.0.0*
