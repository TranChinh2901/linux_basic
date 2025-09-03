---
layout: default
title: Quản lý File
---

# 📄 Quản lý File

## Tạo và xem file

| Lệnh | Mô tả |
|------|-------|
| `touch file.php` | Tạo file rỗng |
| `cat file.txt` | Hiển thị nội dung file |

## Sao chép và di chuyển

| Lệnh | Mô tả |
|------|-------|
| `cp file1 file2` | Sao chép file |
| `mv file1 file2` | Đổi tên/di chuyển file |

## Xóa file

| Lệnh | Mô tả |
|------|-------|
| `rm file.php` | Xóa file |

## Chỉnh sửa file

| Lệnh | Mô tả |
|------|-------|
| `nano file.php` | Chỉnh sửa bằng nano editor |

> **⚠️ Lưu ý:** Lệnh `rm` sẽ xóa vĩnh viễn, không có thùng rác!

### Ví dụ sử dụng:
```bash
# Tạo file mới
touch myfile.txt

# Xem nội dung
cat myfile.txt

# Sao chép với tên mới
cp myfile.txt backup.txt
``` 
