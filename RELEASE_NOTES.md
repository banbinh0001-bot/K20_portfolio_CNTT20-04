# Release Notes - Portfolio CV v7

## Phiên bản

- Tên/mã phiên bản: **v7**
- Ngày cập nhật: **30/10/2026**
- Mã nguồn kiểm tra tại thời điểm lập tài liệu: `6a4b0939ea003133d3f53f123276ea70fbd62490`

## Repository và bản công bố

- Repository: https://github.com/banbinh0001-bot/K20_portfolio_CNTT20-04
- GitHub Pages: https://banbinh0001-bot.github.io/K20_portfolio_CNTT20-04/
- Commit kiểm tra: https://github.com/banbinh0001-bot/K20_portfolio_CNTT20-04/commit/6a4b0939ea003133d3f53f123276ea70fbd62490

## Thay đổi chính của bản v7

- Hoàn thiện trang Portfolio với các vùng giới thiệu, kỹ năng, dự án, học tập và liên hệ.
- Tách stylesheet sang [css/style.css](css/style.css).
- Thêm [ket-qua.html](ket-qua.html) để mô tả kết quả mô phỏng của form liên hệ bằng phương thức `GET`.
- Thêm hướng dẫn vận hành trong [README.md](README.md).
- Thêm hồ sơ quyết định AI trong [AI_LOG.md](AI_LOG.md).
- Thêm tài liệu release này để đối chiếu mã nguồn bàn giao.

## Lỗi đã sửa hoặc trạng thái đã xử lý

- Đường dẫn stylesheet trang chủ đã được cập nhật tới [css/style.css](css/style.css).
- Nội dung tài liệu không ghi nhận form là gửi email hoặc lưu dữ liệu; trang kết quả mô tả đúng hành vi hiện tại.
- URL GitHub Pages đã kiểm tra trả về HTTP 200.

## Commit liên quan

- `6a4b093` - `Add files via upload`.
- `08e3f2a` - `Update index.html`.
- `ea3adcb` - `Update stylesheet link to use css/style.css`.
- `535e20d` - `Delete style.css`.
- `5cc509d` - `Delete index2.html`.

SHA đầy đủ của mã nguồn hiện tại: `6a4b0939ea003133d3f53f123276ea70fbd62490`.

## Hạn chế còn lại

- Form liên hệ chưa có xử lý phía máy chủ, xác thực phía máy chủ hoặc lưu trữ cơ sở dữ liệu.
- Một số thẻ dự án vẫn dùng văn bản liên kết chờ cập nhật thay vì URL thực tế.
- Repository không có bộ test tự động được VS Code phát hiện.
- Chưa có công cụ chuyên dụng để kiểm tra hợp đồng khả năng truy cập đầy đủ.

## Cách tiếp tục kiểm tra

1. Dùng URL GitHub Pages ở mục repository phía trên.
2. Theo [README.md](README.md), kiểm tra menu neo, ảnh, bố cục responsive và luồng form.
3. Sau khi gửi form, kiểm tra URL chuyển sang `ket-qua.html` và dữ liệu xuất hiện trên query string.
4. Kiểm tra bằng ít nhất hai kích thước cửa sổ hoặc thiết bị.
5. Không nhập thông tin nhạy cảm cho đến khi website có backend và chính sách xử lý dữ liệu.

## Hướng dẫn bàn giao tiếp

1. Commit và push đầy đủ [README.md](README.md), [AI_LOG.md](AI_LOG.md), [RELEASE_NOTES.md](RELEASE_NOTES.md).
2. Đợi GitHub Pages hoàn tất build.
3. Kiểm tra lại URL Pages và các liên kết trong tài liệu.
4. Nếu commit bàn giao cuối khác commit mã nguồn ghi trên, cập nhật SHA trong release notes trước khi nộp.