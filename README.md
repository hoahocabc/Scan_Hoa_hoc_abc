# ScanhoahocABC (v32.0 — Hướng Dẫn Sử Dụng Nhanh)

## Các nâng cấp trọng tâm trên ScanhoahocABC (v32.0)
1. **Nhận diện Dòng chữ & Đường kẻ ngang/dọc — Căn thẳng đồng bộ với Toàn trang giấy (`v32.0`)**:
   - **Tự động kích hoạt (`📏 Căn thẳng dòng & kẻ`)**: Ngay sau khi nắn phối cảnh 4 góc và đa điểm rìa trang giấy, thuật toán trích xuất đồng thời đường chân chữ (baseline) và đường kẻ ngang/dọc (vở kẻ ngang, bảng biểu, mẫu đơn), giải hệ 15 tham số (độ nghiêng tuyến tính, độ xòe phối cảnh trên-dưới và 4 bậc sóng hài) kèm hàm neo biên mềm (`vTaper`, `uTaper`) để làm thẳng tuyệt đối từng dòng chữ và đường kẻ mà vẫn giữ nguyên vẹn 4 mép trang giấy.
   - **Nút `📏 Căn theo dòng` trong `📐 Căn chỉnh`**: Tự động phân tích độ cong và hướng của các dòng chữ/đường kẻ bên trong để đồng bộ ngược lại 24 điểm neo của khung cắt đa điểm và hiển thị lưới căn chỉnh trực quan.
2. **Thuật toán Bắt rìa đối tượng chính xác khi Giấy đặt chồng lên Giấy khác (Paper-on-Paper) & Bàn gỗ**:
   - Bảo toàn khe bóng rìa siêu mảnh độ phân giải gốc (`L_minX`, `L_minY`) kết hợp đóng thái học chịu nghiêng 3 điểm (`L_creaseX`, `L_creaseY`) và kiểm chứng 8 đầu mút góc, bắt chuẩn tờ giấy nằm trên kể cả khi đặt chồng lên tờ giấy khác hoặc trên mặt bàn gỗ.
3. **Tùy chỉnh Ghi chú toàn diện, Bật đèn Flash & Giữ 1 ngón di chuyển ảnh**:
   - Tùy chọn **⬛ Có nền / ⬜ Không nền**, **🔲 Có viền / ▫ Không viền**, bảng màu chữ/nền/viền, bật đèn Flash khi chụp và bấm giữ 1 ngón tay lên vùng trống để kéo di chuyển ảnh.
