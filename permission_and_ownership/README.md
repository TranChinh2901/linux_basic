# 🔐 Quyền và Sở hữu

## Xem quyền file

| Lệnh | Mô tả |
|------|-------|
| `ls -l` | Xem quyền chi tiết của file |

## Thay đổi quyền

| Lệnh | Mô tả |
|------|-------|
| `chmod 755 file.sh` | Đặt quyền rwxr-xr-x |
| `chmod +x file.sh` | Thêm quyền thực thi |

## Thay đổi chủ sở hữu

| Lệnh | Mô tả |
|------|-------|
| `chown user:user file.txt` | Đổi chủ sở hữu file |

## Quyền root

| Lệnh | Mô tả |
|------|-------|
| `sudo command` | Chạy lệnh với quyền root |
| `su -` | Chuyển sang user root |

---
> ⚠️ **Lưu ý:** Quyền 755 = Owner(rwx) + Group(rx) + Others(rx)
