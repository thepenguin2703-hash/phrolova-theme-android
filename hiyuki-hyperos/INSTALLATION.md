# Installation Guide - Hướng dẫn Cài đặt

## 🚀 Bước 1: Tải Theme

### Từ GitHub
1. Vào link: https://github.com/thepenguin2703-hash/phrolova-theme-android
2. Click **Code** → **Download ZIP**
3. Giải nén file ZIP
4. Tìm folder **`hiyuki-hyperos`**

---

## 📱 Bước 2: Chuyển vào Điện thoại

### Cách A: Dùng File Manager

1. **Mở File Manager** trên POCO
2. Vào **Internal Storage** (Bộ nhớ nội bộ)
3. Tìm hoặc **tạo folder** `Themes`
   - Nếu chưa có: Nhấn (+) → tạo folder mới → đặt tên `Themes`
4. **Copy toàn bộ folder** `hiyuki-hyperos` vào `Themes`

**Cấu trúc cuối cùng:**
```
Internal Storage/
└── Themes/
    └── hiyuki-hyperos/
        ├── theme.xml
        ├── config.json
        ├── colors.xml
        ├── manifest.xml
        └── README.md
```

### Cách B: Dùng USB (Nếu có Computer)

1. Kết nối điện thoại với máy tính
2. Kéo thả folder `hiyuki-hyperos` vào `Internal Storage/Themes/`
3. Ngắt kết nối

---

## 🎨 Bước 3: Áp dụng Theme

### Phương pháp 1: Qua ứng dụng Chủ đề

1. **Mở ứng dụng Chủ đề** (Themes)
   - Tìm trong ứng dụng hoặc Settings → Personalization → Themes
2. **Refresh danh sách** (kéo xuống)
3. Tìm **Hiyuki** trong danh sách
4. **Nhấn vào Hiyuki**
5. Nhấn nút **Áp dụng** (Apply)
6. **Chờ vài giây** để theme được áp dụng

### Phương pháp 2: Qua Personalization

1. Vào **Settings** (Cài đặt)
2. Chọn **Personalization** (Cá nhân hóa)
3. Chọn **Themes** (Chủ đề)
4. Chọn **Hiyuki**
5. Nhấn **Apply** (Áp dụng)

### Phương pháp 3: Qua ADB (Nâng cao)

Nếu bạn đã cài ADB:

```bash
adb push hiyuki-hyperos /sdcard/Themes/
```

Rồi mở ứng dụng Themes và áp dụng từ đó.

---

## ✅ Kiểm tra sau khi áp dụng

Sau khi áp dụng thành công, bạn sẽ thấy:

✅ **Control Center:** Icon và background sẽ có **màu đỏ Hiyuki**  
✅ **Settings:** Header sẽ **màu đỏ**, toggle sẽ **đỏ khi bật**  
✅ **Lock Screen:** Sẽ có **accent đỏ**  
✅ **Status Bar:** Sẽ **đỏ với chữ trắng**  
✅ **Navigation Bar:** Sẽ có **icon đỏ**  

---

## ⚠️ Nếu không thấy theme

### Vấn đề 1: Theme không xuất hiện trong danh sách

**Giải pháp:**
1. Kiểm tra folder name: Phải là `hiyuki-hyperos` (không phải `hiyuki-theme`)
2. Kiểm tra vị trí: `Themes/hiyuki-hyperos/theme.xml`
3. Mở lại ứng dụng Themes
4. Restart điện thoại
5. Xóa cache Themes app:
   - Settings → Apps → Themes → Storage → Clear Cache

### Vấn đề 2: Theme áp dụng nhưng không có hiệu lực

**Giải pháp:**
1. Kiểm tra file `theme.xml` - phải là XML hợp lệ
2. Kiểm tra `config.json` - phải là valid JSON
3. Xóa cache và thử lại
4. Restart điện thoại
5. Reboot vào Safe Mode rồi áp dụng lại

### Vấn đề 3: Chỉ một số phần có theme, số khác không

**Giải pháp:**
1. Có thể là theme chưa hỗ trợ phần đó trên HyperOS 3.0.6
2. Hoặc có lỗi trong file config
3. Thử clear cache Themes app
4. Áp dụng theme khác rồi áp dụng lại Hiyuki

---

## 🔧 Tùy chỉnh Theme

### Thay đổi màu sắc

1. **Mở folder** `hiyuki-hyperos`
2. **Edit file** `config.json`
3. Tìm màu bạn muốn thay:
   ```json
   "primaryColor": "#C41E3A"
   ```
4. **Thay đổi hex code:**
   ```json
   "primaryColor": "#FF0000"  // Đỏ sáng hơn
   ```
5. **Lưu file**
6. **Refresh** ứng dụng Themes
7. **Áp dụng lại** theme

### Các màu có thể thay đổi

| Phần | Tên config | Màu hiện tại |
|------|-----------|-------------|
| Control Center Background | `controlCenter.backgroundColor` | #F5F5F5 |
| Control Center Icon | `controlCenter.iconColor` | #C41E3A |
| Toggle On | `controlCenter.toggleOnColor` | #C41E3A |
| Settings Header | `settingsUI.headerColor` | #C41E3A |
| Lock Screen Accent | `lockScreen.accentColor` | #C41E3A |
| Battery Charging | `battery.chargingColor` | #C41E3A |

---

## 💡 Mẹo & Thủ thuật

### Backup theme hiện tại
Trước khi áp dụng theme mới:
1. Vào ứng dụng Themes
2. Chọn theme hiện tại → Menu (⋯) → **Save as Custom**
3. Lưu lại để dùng sau

### Quay lại theme mặc định
Nếu muốn quay về:
1. Mở ứng dụng Themes
2. Chọn **Default** hoặc **System Default**
3. Áp dụng

### Kết hợp multiple themes
Bạn có thể:
1. Dùng theme Hiyuki cho Control Center
2. Dùng theme khác cho Lock Screen
3. Thông qua Customization menu (nếu HyperOS hỗ trợ)

---

## 📞 Hỗ trợ

### Nếu còn vấn đề:

1. **Kiểm tra lại các bước**
2. **Restart điện thoại**
3. **Clear cache Themes app**
4. **Thử phương pháp khác**
5. **Nếu vẫn lỗi:**
   - Chụp ảnh error message
   - Mô tả vấn đề chi tiết
   - Open issue trên GitHub

### Liên hệ

- GitHub: https://github.com/thepenguin2703-hash
- Repository: https://github.com/thepenguin2703-hash/phrolova-theme-android

---

## ℹ️ Thông tin bổ sung

- **HyperOS Version:** 3.0.6
- **Được test trên:** POCO F5 Pro
- **Độ tương thích:** Cao
- **Kích thước theme:** ~5MB
- **Bộ nhớ cần:** 50MB free space

---

**Chúc bạn thích theme Hiyuki! ❤️**

*Made with love for Hiyuki fans*
