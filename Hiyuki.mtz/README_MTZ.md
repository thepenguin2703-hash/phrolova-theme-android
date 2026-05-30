# 🎴 Hiyuki Theme - MTZ Format

## Cấu trúc file MTZ:

```
Hiyuki.mtz/
├── theme.xml           # Metadata chính
├── colors.xml          # Định nghĩa màu sắc
├── drawables.xml       # Tham chiếu hình ảnh
├── metadata.json       # Cấu hình theme
├── preview.png         # Ảnh preview
├── lockscreen/         # Lock screen resources
├── homescreen/         # Home screen resources
├── controlcenter/      # Control center icons
├── statusbar/          # Status bar icons
├── navbar/             # Navigation bar icons
├── battery/            # Battery animation frames
└── fingerprint/        # Fingerprint animation frames
```

## Cách sử dụng file MTZ:

1. **Rename**: Đổi tên file thành `Hiyuki.mtz`
2. **Transfer**: Copy vào `/sdcard/Themes/`
3. **Apply**: Mở ứng dụng "Chủ đề" → Chọn theme → Áp dụng

## Lưu ý:
- File `.mtz` là format nén của HyperOS/MIUI
- Không thể giải nén bằng file manager thường
- Phải dùng ứng dụng "Chủ đề" để áp dụng
