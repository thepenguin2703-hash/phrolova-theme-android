# 🎴 Hiyuki Theme - HyperOS 3.0.6

**A premium theme for POCO devices running HyperOS 3.0.6 inspired by Hiyuki from Wuthering Waves**

## ℹ️ Theme Information

- **Name:** Hiyuki
- **Version:** 1.0
- **Author:** @thepenguin2703-hash
- **Game Reference:** Wuthering Waves - Hiyuki Character
- **OS Target:** HyperOS 3.0.6 (International)
- **Device:** POCO

## 🎨 Color Scheme

### Primary Colors
- **Hiyuki Red:** `#C41E3A` (Main accent color)
- **Light Red:** `#E8A8B8` (Soft accents)
- **Dark Red:** `#8B0000` (Shadows)

### Neutral Colors
- **Off-White:** `#FAFAF8` (Main background)
- **Light White:** `#F5F5F5` (Secondary background)
- **Pure White:** `#FFFFFF` (Cards & elements)
- **Black:** `#000000` (Text)
- **Dark Gray:** `#666666` (Secondary text)

## ✨ Customized Components

### 📱 Status Bar
- **Background:** Red (#C41E3A)
- **Text & Icons:** White (#FFFFFF)
- **Effect:** Bold red header

### 🧭 Navigation Bar
- **Background:** Off-white (#FAFAF8)
- **Icons:** Red (#C41E3A)
- **Text:** Black (#000000)

### 🎛️ Control Center
- **Background:** Light white (#F5F5F5)
- **Icons:** Red (#C41E3A)
- **Toggle On:** Red (#C41E3A)
- **Toggle Off:** Gray (#CCCCCC)
- **Dividers:** Light red (#E8A8B8)

### 🔒 Lock Screen
- **Background:** Black (#000000)
- **Text:** White (#FFFFFF)
- **Accent Elements:** Red (#C41E3A)
- **Clock:** White (#FFFFFF)
- **Date:** Light red (#E8A8B8)

### 🏠 Home Screen
- **Background:** Off-white (#FAFAF8)
- **Icon Tint:** Red (#C41E3A)
- **Widgets:** White (#FFFFFF)
- **Folders:** Light white (#F5F5F5)

### ⚙️ Settings UI
- **Header Background:** Red (#C41E3A)
- **Header Text:** White (#FFFFFF)
- **Background:** Off-white (#FAFAF8)
- **Items:** White (#FFFFFF)
- **Text Primary:** Black (#000000)
- **Text Secondary:** Dark gray (#666666)
- **Toggle On:** Red (#C41E3A)
- **Toggle Off:** Gray (#CCCCCC)
- **Dividers:** Light gray (#E0E0E0)

### 🎮 Game Turbo
- **Background:** Black (#000000)
- **Accent:** Red (#C41E3A)
- **Text:** White (#FFFFFF)
- **Transparency:** 90%
- **Position:** Top-right corner

### 🔋 Battery Indicator
- **Charging:** Red (#C41E3A) with glow effect
- **Critical (0-20%):** Red (#FF0000)
- **Low (20-50%):** Orange (#FFA500)
- **Medium (50-80%):** Yellow (#FFFF00)
- **Full (80-100%):** Green (#00AA00)

### 👆 Fingerprint Sensor
- **Scanning Wave:** Red (#C41E3A)
- **Success Animation:** Red glow (#C41E3A)
- **Failed Animation:** Red X (#FF0000)
- **Particle Effects:** Enabled

## 📥 Installation Guide

### Method 1: File Manager (Recommended)

1. **Download the theme**
   - Go to: https://github.com/thepenguin2703-hash/phrolova-theme-android
   - Click **Code** → **Download ZIP**
   - Extract the ZIP file
   - Find the **`Hiyuki`** folder

2. **Transfer to Phone**
   - Open **File Manager** on your POCO
   - Navigate to **Internal Storage**
   - Go to **Themes** folder (create if doesn't exist)
   - Copy the entire **`Hiyuki`** folder into **Themes**

3. **Apply Theme**
   - Open **Themes** app (or **Personalization** → **Themes**)
   - Pull down to refresh
   - Find and tap **"Hiyuki"**
   - Tap **"Apply"** button
   - Wait 3-5 seconds for the theme to be applied

### Method 2: Direct Installation

1. Copy **Hiyuki** folder to: `/storage/emulated/0/Themes/`
2. Open Themes app
3. Refresh (pull down)
4. Select Hiyuki
5. Apply

### Method 3: Alternative Path

If Themes folder is elsewhere, try:
- `/sdcard/Themes/`
- `/data/theme/`
- Check Settings → Personalization → Themes → Choose storage location

## ✅ What Gets Themed

- ✅ Status bar (Red header)
- ✅ Navigation bar (Red icons)
- ✅ Control center (Red accents)
- ✅ Settings app (Red header)
- ✅ Lock screen (Black background, red accents)
- ✅ Home screen (Off-white background)
- ✅ Battery indicator (Color-coded)
- ✅ Fingerprint effects (Red animations)
- ✅ Game Turbo UI (Red interface)
- ✅ Toggle switches (Red when on)
- ✅ Dividers (Light red)

## ⚙️ Customization

### Change Primary Color

1. Open **Hiyuki** folder
2. Edit **theme.json**
3. Find `"primary": "#C41E3A"`
4. Change to desired color: `"primary": "#FF0000"`
5. Save file
6. Refresh Themes app
7. Reapply theme

### Available Customizable Colors

| Element | File | Default Color |
|---------|------|---------------|
| Primary | theme.json | #C41E3A |
| Primary Light | theme.json | #E8A8B8 |
| Background | theme.json | #FAFAF8 |
| Text Primary | theme.json | #000000 |
| Status Bar | colors.xml | #C41E3A |
| Control Center | colors.xml | #F5F5F5 |
| Settings Header | colors.xml | #C41E3A |

## 🔧 Troubleshooting

### Theme doesn't appear in list

**Solution:**
1. Verify folder name: Must be **`Hiyuki`** (exact)
2. Check path: Must be in **Themes** folder
3. Verify files inside:
   - `theme.xml` ✓
   - `theme.json` ✓
   - `colors.xml` ✓
4. Close Themes app completely
5. Reopen and refresh (pull down)
6. If still not visible, restart phone

### Theme applies partially

**Solution:**
1. Some UI elements may not be themed on all devices
2. Try clearing Themes app cache:
   - Settings → Apps → Themes → Storage → Clear Cache
3. Reapply theme
4. Restart phone

### Colors look different

**Possible causes:**
1. Display settings affecting color rendering
2. Night light or blue light filter enabled
3. Some elements use system colors override

**Solution:**
1. Disable Night Light (if enabled)
2. Check Display settings
3. Reapply theme

### Can't find Themes app

**Solution:**
1. Go to **Settings**
2. Search for **"Themes"** or **"Personalization"**
3. Or check **Settings** → **Display** → **Themes**
4. May be under different name on some regions

## 📊 Technical Details

### File Structure
```
Hiyuki/
├── theme.xml          (Main theme manifest)
├── theme.json         (Configuration file)
├── colors.xml         (Color definitions)
└── README.md          (This file)
```

### Compatibility
- **OS:** HyperOS 3.0.6+
- **Region:** International
- **Devices:** POCO (all models with HyperOS 3.0.6)
- **API Level:** 34-35 (Android 14-15)
- **Storage Required:** ~10MB free space

### System Requirements
- HyperOS 3.0.6 or later
- 2GB RAM minimum
- 50MB internal storage free
- Android 14 (API 34) or higher

## 🎯 Features

- ✨ **Red & White Color Scheme:** Elegant Hiyuki-inspired aesthetics
- 🎨 **Comprehensive Theming:** Covers all major UI elements
- 📱 **HyperOS Optimized:** Specifically tuned for HyperOS 3.0.6
- ⚙️ **Customizable:** Edit colors via JSON files
- 🔄 **Non-destructive:** Easy to revert to default
- 📲 **Lightweight:** Only ~10MB in size

## 📝 Version History

### v1.0 (Current)
- Initial release
- Full HyperOS 3.0.6 support
- Complete UI theming
- Optimized colors

## 🙏 Credits

- **Character:** Hiyuki from Wuthering Waves
- **Game Developer:** Kuro Games
- **Theme Creator:** @thepenguin2703-hash
- **Platform:** HyperOS by Xiaomi

## 📄 License

Free to use and modify for personal use. Please credit the original creator if redistributing.

## 🤝 Support

If you encounter issues:
1. Check this README file first
2. Review troubleshooting section
3. Verify file structure
4. Try restarting phone
5. Report issues on GitHub with:
   - Device model
   - HyperOS version
   - Problem description
   - Screenshots (if applicable)

---

**Made with ❤️ for Hiyuki fans on POCO devices**

*Enjoy the Hiyuki Theme! 🎴*
