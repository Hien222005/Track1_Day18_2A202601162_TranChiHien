# AI Support Log — Nhật ký sử dụng AI cá nhân

> **Học viên:** Hồ Lương An  
> **Mã học viên:** 2A202601332  
> **Nhóm:** Team Moi  
> **Case:** Case B — AI Notes: Personal Learning Notes  

---

### 1. AI đã giúp tôi ở đâu?

- **Soạn thảo và chuẩn hoá nội dung:** Hỗ trợ ráp nối các trích dẫn từ Practice Notes Day 17 vào đúng cấu trúc Hypothesis Problem tiêu chuẩn (`Khi [ngữ cảnh], [học viên] gặp khó khăn... vì [rào cản], dẫn đến [hậu quả]`).
- **Tạo content fixture và canned output:** Tạo nội dung bài giảng mẫu *"Bài 3 — Phân tích Cấu trúc Chi phí Doanh nghiệp"* (4 slides có số liệu cụ thể) và sinh các đoạn ghi chú giả lập (canned output) cho Smart Note (Option A) và 3 thẻ tóm tắt (Option B).
- **Lập trình khung Micro-prototype:** Hỗ trợ viết nhanh mã nguồn HTML/CSS/JavaScript cho 3 bản mẫu tương tác, giúp nhóm nhanh chóng triển khai lên môi trường web mà không mất nhiều thời gian xử lý kỹ thuật.

---

### 2. AI sai, hời hợt hoặc làm các options giống nhau ở đâu?

- **Đề xuất tính năng lan man:** Ban đầu AI gợi ý thêm nhiều tính năng phụ (như chatbot hỏi đáp bên lề, sinh câu hỏi trắc nghiệm tự động) làm phân tán trọng tâm bài toán ghi chú và ôn tập.
- **Thiết kế luồng trải nghiệm chưa sát thực tế test:** AI dựng sẵn một trang chọn lựa (Landing page chọn Option A, B, C) khiến người dùng dễ bị phân tâm và so sánh tính năng thay vì trải nghiệm tự nhiên từ góc độ học viên đang nghe giảng.
- **Đầu ra AI quá trơn tru:** Các đoạn tóm tắt mẫu AI sinh ban đầu quá hoàn hảo, thiếu đi các điểm không chắc chắn (uncertainty) hoặc các trường hợp AI diễn giải sai ý người dùng — điều bắt buộc phải có để kiểm tra phản ứng của tester khi lấy lại quyền kiểm soát.

---

### 3. Tôi đã tự sửa hoặc quyết định lại điều gì?

- **Kiểm soát chặt chẽ bài toán cốt lõi:** Lược bỏ toàn bộ các tính năng AI phụ trợ không liên quan, giữ đúng phạm vi 3 mức độ tự chủ (Act / Ask / Don't Act) xoay quanh hành vi ghi nhận kiến thức khi nghe giảng.
- **Tái cấu trúc luồng prototype:** Bỏ giao diện chọn phương án trung gian; thống nhất đưa bài giảng mẫu làm điểm xuất phát chung duy nhất (Common Context) và tách link riêng biệt cho từng tester.
- **Bổ sung cơ chế minh bạch và phục hồi (Human Control & Recovery):** Chủ động thêm nhãn cảnh báo `[AI diễn giải]` tại các điểm suy luận không chắc chắn của Option A, thêm nút xem lại dữ liệu gốc (highlight thô), và bổ sung tuỳ chọn "Bỏ qua tất cả gợi ý" ở Option B để đảm bảo người dùng luôn nắm quyền chủ động.
- **Chuẩn hoá văn phong:** Tự rà soát toàn bộ tài liệu thiết kế và giao diện, loại bỏ các chi tiết trang trí thừa và văn phong khuôn mẫu để báo cáo mang tính chuyên môn, khách quan.
