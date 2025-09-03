---
layout: default
title: Quản lý Tiến trình và Dịch vụ
---

# ⚙️ Quản lý Tiến trình và Dịch vụ

## Xem tiến trình

| Lệnh | Mô tả |
|------|-------|
| `ps aux` | Xem tất cả tiến trình |
| `top` | Xem CPU/RAM real-time |
| `htop` | Giao diện đẹp hơn top (cần cài đặt) |

## Dừng tiến trình

| Lệnh | Mô tả |
|------|-------|
| `kill PID` | Dừng tiến trình theo PID |
| `kill -9 PID` | Dừng mạnh tiến trình |

## Quản lý dịch vụ

| Lệnh | Mô tả |
|------|-------|
| `systemctl start nginx` | Khởi động dịch vụ |
| `systemctl stop nginx` | Dừng dịch vụ |
| `systemctl status nginx` | Kiểm tra trạng thái |

---
> ⚠️ **Chú ý:** Sử dụng `kill -9` cẩn thận vì nó dừng mạnh tiến trình!
