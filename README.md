# ScanhoahocABC (v12.0 — Pure Geometric Flatness • <30ms Ultra-Fast Engine • Full Library Deletion)

## 3 Khắc phục & Nâng cấp trọng tâm trên ScanhoahocABC (v12.0)
1. **Giữ phẳng tuyệt đối cho giấy phẳng (Không bao giờ bị biến thành lượn sóng)**:
   - Loại bỏ hoàn toàn bước tự động uốn sóng theo cột gây méo dòng chữ trên giấy phẳng. Mặc định phép chiếu phối cảnh 3D giữ thẳng tắp 100% các dòng chữ và khung bảng.
   - Khi chụp sách mở bị cong gáy, người dùng có thể chủ động kéo thanh trượt **`Phẳng gáy sách (0%–100%)`** hoặc kéo 4 điểm giữa cạnh trong mục **`📐 Cắt & Xoay`**.
2. **Tốc độ xử lý tức thì (`< 30 ms` — nhanh gấp 15 lần) & Bắt đối tượng chuẩn xác**:
   - Thuật toán bắt góc **`v12.0`** chạy ở độ phân giải `320px` với bộ lọc tách chiều 1D (`< 12 ms`), đo tương phản độ sáng và sắc độ của vùng trung tâm (`30%..70%`) trực tiếp so với viền ngoài 4% của khung ảnh (kèm Radon Crease cho giấy trắng trên nền trắng).
   - Cơ chế **Lazy Filter Cache**: Khi chụp/tải ảnh ở chế độ mặc định **`Ảnh gốc`**, ứng dụng hiển thị ngay ảnh đã cắt phẳng trong `< 1 ms` mà không tốn thời gian tính trước bộ lọc màu; chỉ khi bấm sang `Tài liệu màu`, `Đen trắng` hoặc `Rõ chữ mờ` mới tính bộ lọc trên lưới `1/4` siêu tốc.
3. **Cho phép xóa hết ảnh (kể cả ảnh cuối cùng về `0 ảnh`) trong Thư viện**:
   - Hỗ trợ xóa từng ảnh cho đến khi Thư viện về trạng thái trống (`0 ảnh`) hoặc bấm **`🗑 Xóa hết`** để làm trống toàn bộ Thư viện ngay lập tức.
