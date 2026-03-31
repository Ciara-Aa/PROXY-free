<div align="center">

# 🌐 PROXY FREE

### Danh Sách Proxy Miễn Phí — Tự Động Cập Nhật

[![Proxy Count](https://img.shields.io/badge/Tổng_Proxy-13_020-blue?style=for-the-badge&logo=serverless&logoColor=white)](https://github.com/Ciara-Aa/PROXY-free)
[![Update](https://img.shields.io/badge/Cập_nhật-Mỗi_30_phút-green?style=for-the-badge&logo=githubactions&logoColor=white)](https://github.com/Ciara-Aa/PROXY-free/actions)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

</div>

---

## 📥 Tải Về Nhanh

| Giao Thức | Số Lượng | Tải Về |
| :---: | :---: | :---: |
| 🔵 **HTTP** | `5,690` | [📄 http.txt](https://raw.githubusercontent.com/Ciara-Aa/PROXY-free/refs/heads/main/http.txt) |
| 🟢 **HTTPS** | `400` | [📄 https.txt](https://raw.githubusercontent.com/Ciara-Aa/PROXY-free/refs/heads/main/https.txt) |
| 🟠 **SOCKS4** | `4,501` | [📄 socks4.txt](https://raw.githubusercontent.com/Ciara-Aa/PROXY-free/refs/heads/main/socks4.txt) |
| 🔴 **SOCKS5** | `2,429` | [📄 socks5.txt](https://raw.githubusercontent.com/Ciara-Aa/PROXY-free/refs/heads/main/socks5.txt) |

## 📊 Thống Kê

```mermaid
pie showData title Phân Bố Proxy Theo Giao Thức
    "HTTP" : 5690
    "HTTPS" : 400
    "SOCKS4" : 4501
    "SOCKS5" : 2429
```

<div align="center">

| 📈 Chỉ Số | Giá Trị |
| :--- | :---: |
| **Tổng Proxy** | **13,020** |
| **Nguồn thu thập** | **6** |
| **Tần suất cập nhật** | **Mỗi 30 phút** |
| **Định dạng** | `IP:PORT # TYPE [CC]` |

</div>



## ⚡ Sử Dụng Nhanh

```bash
# Tải danh sách HTTP proxy
curl -sL https://raw.githubusercontent.com/Ciara-Aa/PROXY-free/refs/heads/main/http.txt -o http.txt

# Tải tất cả proxy
for type in http https socks4 socks5; do
  curl -sL "https://raw.githubusercontent.com/Ciara-Aa/PROXY-free/refs/heads/main/${type}.txt" -o "${type}.txt"
done
```

```python
# Python
import requests
proxies = requests.get("https://raw.githubusercontent.com/Ciara-Aa/PROXY-free/refs/heads/main/http.txt").text.splitlines()
print(f"Đã tải {len(proxies)} proxy")
```

---

<div align="center">

**📅 Cập nhật lần cuối: `31/03/2026 17:52:23`** (GMT+7)

⭐ Nếu dự án hữu ích, hãy bấm **Star** để ủng hộ!

</div>

> [!WARNING]
> **Miễn trách nhiệm:** Đây là proxy công cộng miễn phí, được thu thập từ các nguồn mở. Tốc độ và độ ổn định không được đảm bảo. Chỉ nên sử dụng cho mục đích nghiên cứu, học tập hoặc thử nghiệm. Người dùng tự chịu trách nhiệm về cách sử dụng.
