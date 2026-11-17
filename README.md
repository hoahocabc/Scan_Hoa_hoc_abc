# ScanhoahocABC (v13.0 — Rim-Edge Subpixel Detector • Clean Library UX • Inspector & Multi-Select)

## 2 Nâng cấp trọng tâm trên ScanhoahocABC (v13.0)
1. **Nhận diện đối tượng chuẩn xác theo độ chênh sáng & màu cục bộ tại rìa tài liệu (Rim-Edge Subpixel Detector)**:
   - Xóa chữ bên trong bằng đóng hình thái học 5×5 để lấy bề mặt giấy, sau đó tính độ chênh sáng vĩ mô qua rìa (`±4px`) kết hợp đỉnh đạo hàm rìa 1px (`L[x+1] - L[x-1]`) và khớp đường thẳng IRLS nội suy Parabol 44 điểm.
   - Bắt chính xác 4 cạnh rìa tài liệu ngay cả khi ánh sáng đổ bóng chéo không đều, mặt bàn gỗ, bàn tối thiếu sáng, hoặc giấy trắng đặt trên nền trắng (sai số góc trung bình chỉ `~2.0 px`).
2. **Thiết kế lại hoàn toàn Thư viện ảnh theo chuẩn trải nghiệm người dùng smartphone**:
   - **Giao diện Thư viện tinh gọn**: Khi mở `🗂 Thư viện`, chỉ hiển thị danh sách hoặc lưới các ảnh đã chụp, loại bỏ toàn bộ bảng thông tin gây rối và bỏ hai nút xóa ở phía trên.
   - **Hai nút `Xem` và `Xóa` trên từng ảnh**: Mỗi ảnh trong Thư viện có đúng 2 nút trực quan `Xem` và `Xóa`.
   - **Cửa sổ `Xem` phóng to & chỉnh sửa toàn diện**: Khi bấm `Xem`, ứng dụng mở cửa sổ phóng to ảnh, hiển thị thông tin chi tiết (độ phân giải, chế độ màu, thời gian), cho phép thêm **Ghi chú** (kèm tùy chọn in ghi chú lên chân trang ảnh/PDF), đổi tên, đổi chế độ màu, xoay, cắt góc lại và tải về đa định dạng.
   - **Bấm giữ để chọn nhiều ảnh (Long-Press Multi-Select)**: Bấm giữ (~0.4 giây) vào bất kỳ ảnh nào trong Thư viện để bật chế độ chọn nhiều ảnh, hỗ trợ xuất gộp PDF, tải hàng loạt hoặc xóa nhiều ảnh cùng lúc.
