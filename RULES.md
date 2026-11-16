# QUY TẮC DỰ ÁN WEB ÔN TẬP TRẮC NGHIỆM - KHÍ CỤ ĐIỆN (khicudien-tnut1)

1. **Bảo vệ ngân hàng câu hỏi:**
   - Tuyệt đối không tự ý xóa hoặc đổi tên các trường dữ liệu (keys/schema) của câu hỏi trắc nghiệm đang hoạt động.
   - Mọi chỉnh sửa liên quan đến file câu hỏi (JSON/JS/HTML) bắt buộc phải kiểm tra hợp lệ cú pháp và đáp án đúng trước khi hoàn tất.

2. **Bảo vệ luồng ôn tập (Production):**
   - Giữ nguyên logic chấm điểm, đếm thời gian, trộn câu hỏi và lưu trạng thái làm bài.
   - Giao diện thêm mới hoặc chỉnh sửa phải hiển thị chuẩn trên cả điện thoại (Mobile) và máy tính (Desktop).

3. **Đồng bộ đa thiết bị:**
   - Luôn cập nhật tiến độ vào file BEADS.md sau khi hoàn thành một tính năng hoặc sửa lỗi để đồng bộ khi chuyển sang thiết bị khác.
