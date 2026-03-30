# 🌐 Danh Sách Proxy Miễn Phí (Bảo Mật Tuyệt Đối)

> 🔄 Hệ thống tự động thu thập và kiểm tra proxy. Mã nguồn được bảo vệ bằng GitHub Secrets.
> Hoạt động hoàn toàn tự động mỗi **30 phút** qua GitHub Actions.

---

### 📊 Thống Kê Cập Nhật

- **Tổng số: `142`**
- **Proxy HTTP: `131`**
- **Proxy SOCKS4: `11`**
- **Proxy SOCKS5: `0`**

**📅 Cập nhật: `30/03/2026 23:35:59`** (Giờ Việt Nam - GMT+7)

---

## 🔒 Cấu Hình Bảo Mật (BẮT BUỘC)

Vì mã nguồn đã được đưa vào `.gitignore` để tránh bị lộ, bạn cần thực hiện các bước sau để Action hoạt động:

### Bước 1: Lưu trữ mã nguồn
1. Truy cập [GitHub Gist](https://gist.github.com/).
2. Tạo một Gist mới (Nên chọn **Create secret gist**).
3. Đặt tên file là `.scraper.py` và dán toàn bộ mã nguồn của bạn vào.
4. Nhấn **Create secret gist**.
5. Nhấn vào nút **Raw** ở góc trên bên phải khung mã nguồn và copy toàn bộ đường dẫn URL đó.

### Bước 2: Thiết lập GitHub Secrets
1. Vào Repo của bạn trên GitHub.
2. Chọn **Settings** > **Secrets and variables** > **Actions**.
3. Nhấn **New repository secret**.
4. **Name**: `SCRAPER_URL`
5. **Secret**: Dán đường dẫn URL Raw bạn vừa copy ở Bước 1.
6. Nhấn **Add secret**.

### Bước 3: Cấp quyền ghi cho Action
1. Vào **Settings** > **Actions** > **General**.
2. Tại mục **Workflow permissions**, chọn **Read and write permissions**.
3. Nhấn **Save**.

---

## 🛠️ Chạy Thủ Công (Tại máy cá nhân)

Sử dụng file `.scraper.py` bạn đang có:

```bash
# Cài đặt thư viện
pip install requests aiohttp

# Chạy quét và kiểm tra
python .scraper.py --validate
```

---
*Dự án đã được thiết lập bảo mật cấp cao bằng cơ chế curl-secret bởi Antigravity AI.*
