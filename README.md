# ScanhoahocABC (v16.0 — Non-Blocking Smartphone Hamburger Drawer • Coupled Page & Parallel Text-Line Dewarping)

## 2 Nâng cấp trọng tâm trên ScanhoahocABC (v27.0)
1. **Thanh công cụ Ba gạch (`☰`) phân tab siêu gọn trên Smartphone — Tuyệt đối không che khuất ảnh**:
   - Khi bấm vào nút **Ba gạch (`☰`)** ở góc trên bên trái màn hình sửa ảnh, thanh công cụ mở ra dưới dạng **Dải công cụ phân tab 2 dòng siêu gọn (`~86px`)** nằm tách biệt phía trên vùng chứa ảnh (khung ảnh bên dưới tự động co giãn `flex: 1`), giúp **100% bức ảnh luôn hiển thị trọn vẹn** để người dùng quan sát trực tiếp khi đổi màu, chỉnh độ sáng hay dàn phẳng sách trên điện thoại.
   - Bấm vào vùng ảnh bên dưới hoặc bấm lại nút ba gạch (`☰`) thì thanh công cụ tự động đóng lại ngay.
2. **Thuật toán Dàn phẳng trang sách & Nắn thẳng song song các dòng chữ uốn cong (2-Stage 1D Vertical Profile NCC + Harmonic Basis & Arc-Length Unrolling)**:
   - Tự động chia trang thành 32 cột chồng lấp, đo độ lệch dọc giữa các cột bằng Tương quan chéo chuẩn hóa (NCC) 2 tầng và khớp vào hệ hàm điều hòa trực giao 7 thành phần kèm giãn chiều ngang theo độ dài cung (`Arc-Length Unrolling`).
   - Kéo phẳng cả mép trang sách lẫn toàn bộ các dòng chữ bị uốn cong về **thẳng hàng và song song tuyệt đối với nhau**, đồng thời giữ nguyên 100% độ phẳng cho các tờ giấy phẳng thông thường (`0.00 px` biến dạng).
