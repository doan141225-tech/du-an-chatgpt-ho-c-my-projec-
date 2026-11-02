# Tâm An Windows 1.3 — link HTTPS cho TikTok LIVE Studio

1. Tải `Tam-An-Windows.zip` qua Download raw file.
2. Đóng cửa sổ khởi động bản cũ, giải nén toàn bộ ZIP vào thư mục mới, mở `Khoi-dong.bat`.
3. Trên trang điều khiển, chọn **Link LIVE Studio → Tạo link HTTPS**.
4. Đợi **SẴN SÀNG**, bấm **Sao chép link HTTPS**.
5. Trong TikTok LIVE Studio: **Thêm nguồn → Liên kết**, dán link mới, bật âm thanh, độ phân giải **1080 × 1920**, luôn giữ hoạt động, rồi bấm **Thêm nguồn / Áp dụng**.

Giữ chương trình và Internet chạy trong lúc live. Link tạm có thể đổi khi khởi động lại; hãy chép link mới vào nguồn. Không cần tài khoản Cloudflare hoặc mua tên miền. Chỉ sân khấu được đưa lên HTTPS; API quản trị và PIN vẫn ở máy bạn. Ai có link có thể xem sân khấu. Nút **Dừng link** thu hồi link.

Bản này giữ toàn bộ giọng đọc, nhạc và quản trị của bản 1.2: giọng Edge Nam Minh/Hoài My, hai bản nhạc nền tham chiếu, chuông/mõ/tụng kinh, lời chúc, số lạy, tốc độ đi lên/về chỗ, camera/hiệu ứng, sao lưu cấu hình và PIN tùy chọn. Có thể xuất cấu hình từ bản cũ rồi nhập vào bản mới. ZIP không chứa PIN hoặc cài đặt riêng.

Bộ Cloudflare chính thức phiên bản 2026.10.7 có sẵn, được kiểm tra SHA256 trước khi chạy; giấy phép và thông tin nguồn được kèm trong ZIP. Node.js và eSpeak Windows cũng được kèm đầy đủ cùng giấy phép.

Đã qua 26 kiểm thử logic; kiểm tra trình duyệt cho nguồn phát có đường dẫn riêng, tài nguyên/ảnh/nhạc/giọng cục bộ, WebSocket, nghi lễ hai lạy và chặn các API quản trị trên link phát. Các thao tác tạo/sao chép/dừng link đã được kiểm tra với phản hồi Windows mô phỏng; bộ production được chạy thử bằng Node Linux. Chưa thực thi trực tiếp trên Windows, tạo Quick Tunnel thật hoặc xác nhận trên TikTok LIVE Studio. Dịch vụ mạng Cloudflare/Microsoft/TikTok cần hoạt động trên mạng của máy người dùng.
