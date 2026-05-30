# Hiyuki Theme for HyperOS 3.0.6

## 📱 Thông tin Theme

**Tên Theme:** Hiyuki - Wuthering Waves  
**Phiên bản:** 1.0.0  
**Hỗ trợ:** HyperOS 3.0.6 (Quốc tế) trên POCO  
**Tác giả:** @thepenguin2703-hash

## 🎨 Màu sắc chính

- **Màu chính (Red):** `#C41E3A` (Hiyuki signature color)
- **Màu nhẹ (Light Red):** `#E8A8B8` (Accents)
- **Nền trắng:** `#F5F5F5` (Clean background)
- **Nền tối:** `#000000` (Lock screen)

## ✅ Các thành phần được tùy chỉnh

### Control Center (Trung tâm điều khiển)
- Nền: Trắng (#F5F5F5)
- Icon: Đỏ Hiyuki (#C41E3A)
- Toggle: Đỏ khi bật, xám khi tắt
- Góc bo tròn: 12dp

### Lock Screen (Màn hình khóa)
- Nền: Đen (#000000)
- Chữ: Trắng (#FFFFFF)
- Accent: Đỏ (#C41E3A)
- Hỗ trợ hiển thị hình nền custom (thêm sau)

### Home Screen (Màn hình chính)
- Nền: Trắng nhạt (#FAFAF8)
- Icon: Theo hệ thống
- Widget: Nền trắng (#FFFFFF)
- Accent: Đỏ (#C41E3A)

### Settings UI (Giao diện cài đặt)
- Header: Đỏ Hiyuki (#C41E3A)
- Nền: Trắng nhạt (#FAFAF8)
- Toggle: Đỏ khi bật
- Text: Đen (#000000)

### Game Turbo (Turbo Trò chơi)
- Nền: Đen (#000000)
- Accent: Đỏ (#C41E3A)
- Vị trí: Góc trên phải
- Độ trong suốt: 90%
- Hiển thị: CPU, RAM, Nhiệt độ, FPS

### Battery Indicator (Chỉ báo pin)
- Đang sạc: Đỏ (#C41E3A) với hiệu ứng glow
- Thấp: Cam (#FFA500)
- Trung bình: Vàng (#FFFF00)
- Đầy: Xanh (#00AA00)
- Hiệu ứng: Mượt với 20 frame

### Fingerprint Effects (Hiệu ứng vân tay)
- Quét: Sóng tròn đỏ
- Thành công: Glow đỏ
- Thất bại: X đỏ
- Particle effect: Bật

## 📁 Cấu trúc thư mục

```
hiyuki-hyperos/
├── theme.xml                    # Main theme file
├── config.json                  # Configuration
├── colors.xml                   # Color definitions
├── README.md                    # This file
├── wallpapers/                  # (Optional) Hình nền
│   ├── lockscreen_wallpaper.png
│   └── homescreen_wallpaper.png
├── animations/                  # (Optional) Hiệu ứng
│   ├── charging/
│   ├── fingerprint/
│   └── other/
└── assets/                      # (Optional) Assets
    ├── icons/
    └── images/
```

## 📥 Cách cài đặt trên HyperOS 3.0.6

### **Phương pháp 1: Thông qua File Manager (Khuyên dùng)**

1. **Tải repository**
   - Vào: https://github.com/thepenguin2703-hash/phrolova-theme-android
   - Download ZIP
   - Giải nén

2. **Copy folder theme**
   - Tìm folder `hiyuki-hyperos`
   - Copy toàn bộ folder này

3. **Chuyển vào điện thoại**
   - Vào: **Internal Storage → Themes/**
   - Paste folder `hiyuki-hyperos` vào

4. **Mở ứng dụng Chủ đề (Themes)**
   - Refresh (kéo xuống)
   - Tìm **Hiyuki**
   - Nhấn → **Áp dụng**

### **Phương pháp 2: Qua ứng dụng Themes trực tiếp**

1. Mở ứng dụng **Chủ đề**
2. Nhấn menu (⋯) → **Import** / **Nhập khẩu**
3. Chọn folder `hiyuki-hyperos`
4. Nhấn **Áp dụng**

### **Phương pháp 3: Qua ADB (Nâng cao)**

```bash
adb push hiyuki-hyperos /sdcard/Themes/
```

## ⚙️ Tùy chỉnh Theme

### Thay đổi màu sắc

1. Mở file `config.json`
2. Tìm phần màu bạn muốn thay đổi
3. Sửa hex color code
   ```json
   "primaryColor": "#C41E3A"  // Đổi sang màu khác
   ```
4. Lưu file
5. Refresh ứng dụng Themes

### Thêm hình nền custom

1. Tạo folder `wallpapers` (nếu chưa có)
2. Thêm hình ảnh:
   - `lockscreen_wallpaper.png` (1440x3120px)
   - `homescreen_wallpaper.png` (1440x3120px)
3. Edit `config.json` để trỏ tới hình ảnh

### Thêm hiệu ứng animation

1. Tạo folder `animations`
2. Thêm các frame PNG:
   - Charging: `charging_0.png` → `charging_19.png`
   - Fingerprint: `fingerprint_0.png` → `fingerprint_19.png`
3. Update `config.json`

## 🔧 Khắc phục sự cố

### Theme không hiển thị

**Vấn đề:** Không thấy theme trong ứng dụng Chủ đề

**Giải pháp:**
1. Kiểm tra folder name: Phải là `hiyuki-hyperos`
2. Kiểm tra file `theme.xml` có ở trong folder không
3. Refresh ứng dụng Themes (kéo xuống)
4. Đóng app Themes và mở lại
5. Restart điện thoại

### Theme áp dụng nhưng không đầy đủ

**Vấn đề:** Chỉ một số phần được theme

**Giải pháp:**
1. Kiểm tra `config.json` có đúng định dạng không
2. Đảm bảo tất cả color codes có # ở đầu
3. Xóa cache Themes app: Settings → Apps → Themes → Storage → Clear Cache
4. Áp dụng lại theme

### Không thể áp dụng theme

**Vấn đề:** Khi nhấn Áp dụng, bị lỗi

**Giải pháp:**
1. Kiểm tra file `theme.xml` - phải là XML hợp lệ
2. Kiểm tra encoding: UTF-8
3. Thử restart điện thoại
4. Thử xóa cache Themes app
5. Nếu vẫn không, thử phương pháp ADB

## 📊 Thông tin kỹ thuật

| Thành phần | Định dạng | Yêu cầu |
|-----------|----------|--------|
| Theme file | XML | UTF-8 |
| Config | JSON | Valid JSON |
| Colors | Hex | #RRGGBB |
| Images | PNG/WebP | 1440x3120px |
| Animation | PNG sequence | 30fps |

## 🎯 Tính năng chi tiết

### Control Center
- ✅ Màu icon tùy chỉnh
- ✅ Màu background tùy chỉnh
- ✅ Toggle color
- ✅ Divider color
- ✅ Corner radius

### Lock Screen  
- ✅ Hỗ trợ wallpaper custom
- ✅ Clock color tùy chỉnh
- ✅ Date color tùy chỉnh
- ✅ Lock icon color
- ✅ Notification color

### Home Screen
- ✅ Wallpaper custom
- ✅ Icon tint color
- ✅ Widget background
- ✅ Folder theme
- ✅ App drawer theme

### Settings
- ✅ Header background
- ✅ Toggle color
- ✅ Text color
- ✅ Item background
- ✅ Divider color

### Game Turbo
- ✅ Interface color
- ✅ Text color
- ✅ Position customization
- ✅ Transparency control
- ✅ Performance indicators

### Battery & Fingerprint
- ✅ Multi-level coloring
- ✅ Animation effects
- ✅ Particle effects
- ✅ Smooth transitions

## 📝 Ghi chú

- Theme này được tối ưu cho HyperOS 3.0.6
- Hỗ trợ các POCO models
- Có thể cần điều chỉnh nhỏ tùy thuộc vào sub-version HyperOS
- Backup cài đặt trước khi thay đổi theme

## 🙏 Credits

- **Nhân vật Hiyuki:** Wuthering Waves - Kuro Games
- **Theme:** Được thiết kế cho HyperOS 3.0.6
- **Inspirations:** Hiyuki's elegant aesthetic

---

**Made with ❤️ for Hiyuki fans on POCO devices**

*Last Updated: May 2026*
*Version: 1.0.0 - HyperOS 3.0.6 Edition*
