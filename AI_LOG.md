# Nhật ký quyết định sử dụng AI

## Thông tin chung

- Bản ghi dành cho việc hoàn thiện tài liệu bàn giao của Portfolio.
- Repository chưa có `AI_LOG.md` có nội dung trước khi hoàn thiện yêu cầu này.
- Công cụ hỗ trợ: GitHub Copilot/AI assistant trong VS Code.

## Nhật ký 1: Chuẩn hóa tài liệu bàn giao

### Hiện tượng và dữ kiện ban đầu

- Repository có trang Portfolio chính, trang kết quả form và tài nguyên ảnh/CSS.
- `README.md` ban đầu không có nội dung.
- Repository chưa có tài liệu nhật ký AI hoặc release notes có nội dung.
- URL GitHub Pages đã được kiểm tra và trả về HTTP 200.
- `HEAD` hiện tại là commit `6a4b0939ea003133d3f53f123276ea70fbd62490`.
- Form gửi dữ liệu bằng `GET` tới trang kết quả; không có máy chủ hoặc cơ sở dữ liệu.

### Nhận định trước khi dùng AI

- README phải mô tả đúng hành vi hiện tại, không giới thiệu form là chức năng gửi thư thật.
- Nội dung kiểm tra cần thực hiện bằng trình duyệt, không phụ thuộc test framework hoặc build tool.
- Nhật ký cần phân biệt rõ phần AI đề xuất và quyết định đã được sinh viên xác nhận.

### Công cụ, prompt và phản hồi mẫu

- Prompt yêu cầu tạo README, nhật ký AI và release notes theo yêu cầu giảng viên.
- AI đề xuất: viết tài liệu theo cấu trúc README → AI_LOG → RELEASE_NOTES; hướng dẫn kiểm tra bằng trình duyệt; ghi rõ form chỉ mô phỏng.

### Quyết định và lý do

- Chấp nhận cách tổ chức tài liệu sau khi đối chiếu dữ liệu thực tế trong repository.
- Không ghi nhận test tự động vì workspace không có bộ điều khiển test.
- Không chỉnh sửa mã trang trong bước này vì phạm vi yêu cầu là tài liệu.
- Không ghi nhận các thông tin chưa kiểm chứng như ngày kích hoạt Pages.

### Phần sửa

- Tạo README với hướng dẫn mở trực tiếp, chạy local, kiểm tra trang và giới hạn sản phẩm.
- Tạo nhật ký này để lưu căn cứ quyết định.
- Tạo release notes cho bản v7 theo trạng thái mã thực tế.

### Cách thử lại và kết quả

- Kiểm tra remote và xác nhận URL repository trong README.
- Kiểm tra Git log để xác nhận commit `6a4b0939ea003133d3f53f123276ea70fbd62490`.
- Kiểm tra URL Pages bằng HTTP HEAD và nhận trạng thái `200 OK`.
- Đọc `index.html`, `ket-qua.html` và `css/style.css` để xác nhận luồng form và tài liệu liên kết.
- Kiểm tra workspace không phát hiện test tự động; chỉ ghi nhận kiểm tra bằng trình duyệt thay cho kết quả test không tồn tại.