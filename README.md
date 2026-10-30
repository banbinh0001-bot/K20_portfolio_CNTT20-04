# Portfolio CV - Bàn An Bình

**Tác giả:** Bàn An Bình

Portfolio cá nhân bằng HTML và CSS dành cho sinh viên ngành Công nghệ Thông tin. Trang giới thiệu thông tin cá nhân, kỹ năng, dự án học tập, quá trình học và một form liên hệ mô phỏng.

- Repository: https://github.com/banbinh0001-bot/K20_portfolio_CNTT20-04
- GitHub Pages: https://banbinh0001-bot.github.io/K20_portfolio_CNTT20-04/
- Hồ sơ GitHub: https://github.com/banbinh0001-bot
- Email minh chứng liên hệ trên trang: `driveqpalzm@gmail.com`
- Minh chứng bàn giao: [RELEASE_NOTES.md](RELEASE_NOTES.md), [AI_LOG.md](AI_LOG.md)

## Cấu trúc thư mục

```text
.
├── index.html          # Trang Portfolio chính
├── ket-qua.html        # Trang kết quả mô phỏng form
├── css/
│   └── style.css       # Kiểu dáng, bố cục và responsive
├── assets/
│   └── images/         # Ảnh đại diện và ảnh dự án
├── README.md           # Hướng dẫn mở và kiểm tra sản phẩm
├── AI_LOG.md           # Nhật ký quyết định có hỗ trợ AI
└── RELEASE_NOTES.md    # Ghi chú bản v7 bàn giao
```

## Chạy local

Không cần cài đặt framework hoặc công cụ build. Đóng góp hay kiểm tra bằng một trong hai cách sau:

### Mở trực tiếp

1. Tải repository về máy.
2. Mở [index.html](index.html) bằng trình duyệt hiện đại.

### Chạy máy chủ tĩnh

Từ thư mục gốc, dùng VS Code extension **Live Server** hoặc chạy một máy chủ tĩnh, ví dụ:

```powershell
python -m http.server 8000
```

Sau đó truy cập `http://localhost:8000/`.

## Nguồn xuất bản

Sản phẩm được xuất bản bằng GitHub Pages. Repository được cấu hình để phục vụ tệp ở thư mục gốc từ nhánh được GitHub Pages thiết lập. Đối với GitHub Pages mặc định, nguồn được chọn trong **Settings > Pages > Build and deployment**.

## Danh sách kiểm tra sản phẩm

1. Mở trang chủ qua URL GitHub Pages hoặc `index.html`.
2. Kiểm tra menu neo: **Giới thiệu**, **Kỹ năng**, **Dự án**, **Học tập**, **Liên hệ** dẫn tới đúng vùng tương ứng.
3. Kiểm tra ảnh đại diện và ba ảnh trong mục Dự án tải đầy đủ.
4. Thay đổi chiều rộng cửa sổ trình duyệt; bố cục phải co giãn mà không làm tràn trang.
5. Nhập dữ liệu vào form liên hệ, nhấn gửi và xác nhận trình duyệt chuyển sang `ket-qua.html`.
6. Trên trang kết quả, xác nhận nội dung chỉ mô tả kết quả giả lập và có liên kết quay lại trang liên hệ.
7. Kiểm tra dữ liệu form xuất hiện trên thanh địa chỉ vì form dùng phương thức `GET`; không nhập thông tin nhạy cảm.

## Giới hạn hiện tại

Form liên hệ là minh họa front-end. Dữ liệu không được lưu, email không được gửi và trang kết quả không xác nhận xử lý phía máy chủ. Các liên kết dự án cũ trong thẻ Dự án cần được thay bằng URL dự án thực tế nếu đã có.