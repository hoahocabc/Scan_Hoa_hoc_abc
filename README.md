# ScanhoahocABC (v14.0 — 2-Stage Subpixel Rim Detector • Minimalist Full-Screen Editor Dropdown • Dedicated Export Popups)

## 6 Nâng cấp trọng tâm trên ScanhoahocABC (v14.0)
1. **Bắt rìa tài liệu 2 tầng độ chính xác Sub-pixel (`~0.55 - 0.78 px` error)**:
   - **Tầng 1**: Phát hiện khung tứ giác rìa tài liệu ở độ phân giải `360px` bằng cổng độ chênh sáng/màu vĩ mô `±4px` kết hợp đỉnh đạo hàm rìa 1px.
   - **Tầng 2 (Full-Resolution Normal-Profile Snapping)**: Lấy mẫu 64 mặt cắt pháp tuyến trực tiếp trên ảnh gốc độ phân giải đầy đủ (`1:1 native pixels`) dọc theo 4 cạnh rìa, nội suy đỉnh Parabol sub-pixel và khớp đường thẳng IRLS.
2. **Giao diện màn hình chính siêu gọn gàng**:
   - Bỏ hàng nút chế độ màu trên màn hình chính và thay nút `Cắt & Xoay` bằng nút **`✨ Sửa`**.
   - Thanh dưới cùng chỉ còn đúng 3 nút cân đối: **`✨ Sửa`**, **`⬇ Tải ảnh này`**, **`📄 Lưu PDF`**.
3. **Màn hình `✨ Sửa` & `Xem` toàn màn hình kèm Menu xổ (`✨ Sửa ▾`)**:
   - Khi bấm **`✨ Sửa`** trên màn hình chính hoặc bấm **`Xem`** trong **`🗂 Thư viện`**, ứng dụng mở ảnh toàn màn hình với nút **Menu xổ `✨ Sửa ▾`** chứa đầy đủ công cụ: chọn chế độ (`Ảnh gốc`, `Tài liệu màu`, `Đen trắng`, `Làm rõ chữ`), `Tách nền Alpha`, thanh trượt `Tăng/giảm sáng`, `Làm sạch nền`, `📐 Cắt góc`, `↻ Xoay 90°`, `📖 Tách đôi`, đổi tên và thêm `📝 Ghi chú`.
4. **Thông tin phụ nằm gọn phía dưới ảnh**: Hiển thị tỉ lệ ảnh (`A4`), độ phân giải, chế độ màu và ngày giờ ngay bên dưới khung ảnh.
5. **Loại bỏ hoàn toàn các nút "Mẫu thử" vô nghĩa**.
6. **Tùy chọn định dạng & chất lượng/DPI chỉ xuất hiện trong Popup `⬇ Tải ảnh này` hoặc `📄 Lưu PDF`**.
