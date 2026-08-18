# Track1_Day18_2A202601162_TranChiHien

## 1. Thông tin cá nhân & nhóm

| Thông tin chung | Chi tiết |
|---|---|
| **Mã học viên (MHV)** | 2A202601162 |
| **Họ và tên** | Trần Chí Hiển |
| **Tên nhóm** | Team Moi |
| **Case** | Case B: AI Notes: Personal Learning Notes |

### Danh sách thành viên nhóm

| STT | Họ và tên | MHV | Vai trò Day 18 |
|:---:|---|:---:|---|
| 1 | Vũ Nguyễn Bảo Sơn | 2A202601116 | Chịu trách nhiệm chính Option C: Bookmark nhanh, không AI |
| 2 | Hồ Lương An | 2A202601332 | Chịu trách nhiệm chính Option B: AI gợi ý, user xác nhận |
| 3 | Trần Chí Hiển | 2A202601162 | Chịu trách nhiệm chính Option A: AI Notes tự tổng hợp |

---

## 2. Hypothesis Problem

### Hypothesis Problem nhóm dùng trong Day 18

> Khi đang nghe giảng và gặp nội dung cần nhớ, **học viên gặp** khó **khi vừa ghi chú vừa theo kịp bài để sau đó ôn lại**, vì **phải tự ghi chép thủ công sang công cụ ngoài và ghi chú thường khó tìm lại**, dẫn đến **mất tập trung ngay lúc học và phần lớn không quay lại ôn tập**.

### Evidence ban đầu hỗ trợ giả thuyết (từ Practice Notes Day 17)

- **An → Trần Văn Ngọc:** *"Phải copy-paste, phải gõ phím liên tục, dẫn đến việc bị sao nhãng không tập trung nghe giảng tiếp được"*: xác nhận trực tiếp khó khăn (thao tác thủ công) và hậu quả tức thời (mất tập trung ngay lúc học).
- **Sơn → P01528:** *"Khó note lại vì tìm kiếm lại khó: ghi chú bị rải rác nhiều nơi"*: xác nhận phần khó khăn "khó tìm lại đúng chỗ cần".
- **An → Trần Văn Ngọc:** *"Về nhà quên không mở ra ôn lại... thực tế học viên cũng không có thói quen hay nhu cầu chủ động ôn tập lại"*: xác nhận hậu quả "không quay lại ôn tập".

### Điều vẫn chưa được chứng minh

- Chưa rõ nếu giảm bớt khó khăn ở khâu ghi chú (bằng công cụ/AI tốt hơn) thì học viên có thực sự quay lại ôn tập nhiều hơn không: đây mới là suy đoán của nhóm, chưa được kiểm chứng.
- Ghi chép phỏng vấn của Hiển (người được phỏng vấn: Lê Quang Huy) cho thấy ít nhất một học viên không gặp khó khăn rõ ràng ở cả khâu ghi lẫn khâu ôn tập (đã tự giải quyết bằng NotebookLM): chưa biết đây là trường hợp cá biệt hay đại diện cho một nhóm học viên khác.
- Chưa xác định được nguyên nhân chính là do thiếu công cụ ghi chú (giả thuyết A) hay do thiếu thói quen/động lực ôn tập (giả thuyết B): ba ghi chép phỏng vấn hiện tại cho tín hiệu trái chiều nhau, không đủ để kết luận dứt khoát; ba bản mẫu (prototype) hôm nay được kỳ vọng giúp làm rõ thêm câu hỏi này.

---

## 3. Three Solution Options

_(Human–AI Design pass ở Chặng 3 và link prototype ở Chặng 4 chưa thực hiện: xem chi tiết mechanism đầy đủ tại `three-option-design-sheet.md`.)_

| Option | Solution mechanism (tóm tắt) | User làm gì? | AI làm gì? | Link prototype |
|---|---|---|---|---|
| A: AI Notes tự tổng hợp | Highlight/đánh dấu trong lúc học → AI tự gộp thành bản ghi chú có cấu trúc khi bài kết thúc | Highlight, đánh dấu, review & sửa bản ghi chú AI tạo | Act: tự tổng hợp toàn bộ | [Option A Live](https://day18-teammoi-optiona-b-c.netlify.app/option-a.html) |
| B: AI gợi ý, user xác nhận | AI đề xuất "3 điều quan trọng nhất bài này" khi bài kết thúc, user xác nhận/sửa/bổ sung trước khi lưu | Highlight, đánh dấu, chọn giữ/sửa/thêm gợi ý AI | Ask: đề xuất, chờ xác nhận | [Option B Live](https://day18-teammoi-optiona-b-c.netlify.app/option-b.html) |
| C: Bookmark nhanh, không AI | User tự bấm bookmark tại đoạn đang nghe, hệ thống lưu vị trí + preview ngắn | Bấm bookmark tại chỗ; tự lướt lại khi ôn | Don't act: không tham gia | [Option C Live](https://day18-teammoi-optiona-b-c.netlify.app/option-c.html) |

> **Landing Page chung:** [https://day18-teammoi-optiona-b-c.netlify.app/](https://day18-teammoi-optiona-b-c.netlify.app/) (Xem chi tiết tại [prototype-link.md](prototype-link.md))

---

## 4. Đóng góp của tôi trong nhóm

_(Chưa thực hiện: điền sau khi build prototype và test. Ghi cụ thể: option nào bạn chịu trách nhiệm chính, phần shared context/content bạn đóng góp, Human–AI decisions bạn tham gia chốt, tester bạn facilitate, phần tổng hợp feedback bạn làm.)_

---

## 5. Prototype Feedback

_(Chưa thực hiện: điền sau Chặng 6. Gồm: observation từ phiên bạn facilitate: xem `prototype-feedback-note.md`; ba-feedback synthesis: xem `group-feedback-synthesis.md`; một Next Change; một Still Unproven.)_

---

## 6. AI Support Log

_(Xem chi tiết tại [ai-support-log.md](ai-support-log.md))_

- **AI đã giúp tôi ở đâu:** Soạn thảo câu Hypothesis Problem theo đúng format chuẩn; sinh bộ dữ liệu content fixture cho bài giảng mẫu (*Bài 3 — Cấu trúc chi phí*) cùng các mẫu canned output cho Smart Note và Key Takeaways; hỗ trợ viết nhanh khung mã nguồn HTML/CSS/JavaScript cho 3 micro-prototypes.
- **AI sai, hời hợt hoặc làm các options giống nhau ở đâu:** Đề xuất thêm các tính năng phụ rườm rà (chatbot, sinh câu hỏi trắc nghiệm) làm loãng bài toán chính; tự dựng trang landing page chọn lựa khiến tester mất đi trải nghiệm tự nhiên; canned output ban đầu quá hoàn hảo, thiếu đi các điểm không chắc chắn (*uncertainty*) để kiểm tra phản ứng của người dùng.
- **Tôi đã tự sửa hoặc quyết định lại điều gì:** Ép chặt phạm vi 3 mức độ tự chủ (Act / Ask / Don't Act) xoay quanh hành vi ghi nhận kiến thức khi nghe giảng; xoá bỏ giao diện chọn phương án trung gian để dùng chung một luồng bài giảng mẫu duy nhất; chủ động thêm cờ `[AI diễn giải]` và các nút phục hồi (*Recovery*) để người dùng luôn nắm quyền kiểm soát; rà soát loại bỏ toàn bộ văn phong khuôn mẫu và icon trang trí thừa.
