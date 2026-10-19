# Thương em · 20/10

Thiệp tương tác tặng người yêu nhân Ngày Phụ nữ Việt Nam. HTML/CSS/JavaScript thuần, không cần build.

## Xem trang

Mở `index.html` trực tiếp hoặc chạy `python3 -m http.server 8080`, rồi mở http://localhost:8080.

## Hiệu ứng và tương tác

- Màn nhận quà, chữ xuất hiện theo nhịp, hoa đung đưa và bung nở khi chạm.
- Cánh hoa trôi, ngôi sao lấp lánh, dải chữ chạy và nội dung hiện khi cuộn.
- Phong bì lật nắp, lá thư trượt ra, lời chúc hiện lần lượt.
- Nhận ôm với bộ đếm, lời nhắn luân phiên và tim bung bay.
- Nút tạm dừng hiệu ứng, hỗ trợ thiết lập giảm chuyển động, khóa cuộn và giữ focus khi mở thư. Số hạt hiệu ứng được giới hạn và tự dọn dẹp.

## GitHub Pages

1. Đẩy `index.html` vào thư mục gốc repository.
2. Vào **Settings → Pages → Deploy from a branch**.
3. Chọn nhánh chứa file (thường là `main`), thư mục **/(root)**, bấm **Save**.
4. Mở đường dẫn Pages sau khi GitHub triển khai xong.

## Cá nhân hóa

Sửa lời chúc ở phần `id="modal"`, chữ ký và các mảng `flowerMessages`, `messages` trong `index.html`. Không cần cài thư viện. Google Fonts là tài nguyên ngoài duy nhất; trang có font dự phòng khi offline.

Thiết kế dành cho Safari/Chrome hiện đại; hiệu ứng có phương án giảm chuyển động. Không có nhạc tự phát hay thu thập thông tin. Bộ đếm ôm đặt lại khi tải trang.

## Viết lời chúc cho Phương Linh

Mở `index.html`, tìm `id="personal-message"`. Thay đoạn văn mẫu bên trong bằng lời chúc của bạn; mỗi đoạn đặt trong `<p>...</p>`. Phần này có chú thích `VIẾT LỜI CHÚC CỦA BẠN Ở ĐÂY` để dễ tìm. Hãy thay lời nhắc trước khi gửi trang cho em.

Trang đã cá nhân hóa theo phong cách tổng đài cho Phương Linh. Trong mục đăng ký gói “Bà chã”, nút Không né chuột/chạm và nút Đồng ý lớn dần (giới hạn theo chiều rộng màn hình). Bàn phím cũng kích hoạt được. Đồng ý hiển thị lời xác nhận vui; không gửi hay lưu dữ liệu lên máy chủ.
