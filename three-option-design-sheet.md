# Three-Option Design Sheet — Human–AI Micro-Prototypes

> **Môn học:** AI Product Development — Track 1 Day 18  
> **Nhóm:** Team Moi  
> **Case:** Case B — AI Notes: Personal Learning Notes  
> **Thành viên nhóm:**  
> - Vũ Nguyễn Bảo Sơn (MHV: 2A202601116)
> - Hồ Lương An (MHV: 2A202601332)
> - Trần Chí Hiển (MHV: 2A202601162)

---

## 1. Chặng 1 — Tổng hợp Evidence & Chốt Hypothesis Problem

### 1.1. Bảng tổng hợp Evidence từ Practice Notes Day 17 (Evidence Snapshot)

| Practice Note | User đã thực sự làm/nói gì? (Observed facts & quotes) | Điều nhóm diễn giải (Interpreted) |
|---|---|---|
| **1. An → Trần Văn Ngọc** | *"Phải copy-paste, phải gõ phím liên tục, dẫn đến việc bị sao nhãng không tập trung nghe giảng tiếp được."* | Thao tác ghi chép thủ công (gõ phím/copy) gây phân mảnh chú ý ngay trong lúc học, làm mất dòng suy nghĩ. |
| **2. Sơn → P01528** | *"Khó note lại vì tìm kiếm lại khó — ghi chú bị rải rác nhiều nơi (Notion, giấy, messenger)."* | Friction không chỉ nằm ở lúc ghi, mà còn ở khâu tổ chức; ghi chú rời rạc khiến việc tìm lại sau này quá tốn công. |
| **3. An → Trần Văn Ngọc** | *"Về nhà quên không mở ra ôn lại... thực tế học viên cũng không có thói quen hay nhu cầu chủ động ôn tập lại."* | Việc ghi chép tốn công ban đầu không chuyển hoá thành hành vi ôn tập thực tế; học viên thiếu động lực hoặc friction mở lại quá lớn. |

### 1.2. Hypothesis Problem chốt của nhóm

> Khi đang nghe giảng trực tiếp trên lớp và gặp nội dung hoặc tài liệu quan trọng cần nhớ, **học viên VLearn** gặp khó khăn trong việc **vừa ghi lại đủ thông tin quan trọng vừa không bị gián đoạn theo dõi bài giảng, để sau đó có thể ôn tập lại**, vì **phải tự chuyển sang thao tác ghi chép thủ công (viết tay, gõ phím, copy-paste) sang công cụ ngoài — việc này chiếm sự chú ý ngay trong lúc học, và ghi chú tạo ra thường rải rác, khó tìm lại đúng chỗ cần** — dẫn đến **học viên bị mất tập trung ngay khi đang học, và sau đó phần lớn không quay lại mở ghi chú để ôn tập, khiến công sức ghi chép ban đầu không chuyển hoá thành giá trị ôn tập thực tế**.

### 1.3. Evidence ban đầu hỗ trợ giả thuyết
- Xác nhận barrier gián đoạn dòng học: Thao tác mở app ngoài, copy-paste, gõ phím làm mất nhịp bài giảng.
- Xác nhận barrier phân mảnh: Ghi chú rải rác nhiều nơi, khó liên kết lại với ngữ cảnh bài học.
- Xác nhận consequence: Ghi chú bị bỏ quên sau khi kết thúc buổi học.

### 1.4. Điều vẫn chưa được chứng minh
- Chưa chứng minh được: Liệu khi AI giải quyết xong friction lúc ghi chép, học viên có **thực sự chủ động mở ra ôn tập thường xuyên hơn không**, hay rào cản gốc rễ nằm ở thói quen học tập cá nhân.
- Tín hiệu đối nghịch (Hiển → Lê Quang Huy): Học viên tự xoay sở tốt bằng NotebookLM / công cụ có sẵn và không cảm thấy ghi chép thủ công là nỗi đau lớn. Cần kiểm chứng đây là đối tượng ngoại lệ (power user) hay phân khúc phổ biến.

---

## 2. Chặng 2 — Chọn ba Solution Options & Comparison Contract

### 2.1. Comparison Contract — Những thứ phải giữ nguyên (Controlled Baseline)
Để phép thử A/B/C có giá trị khoa học và so sánh được, cả 3 option bắt buộc dùng chung 100% các yếu tố sau:

| Thành phần | Quyết định chung cho cả 3 Option (A, B, C) |
|---|---|
| **Target user** | Học viên VLearn đang theo học các khoá học trực tuyến chuyên sâu có nhiều kiến thức mới cần ghi nhớ. |
| **Situation** | Đang xem video bài giảng dài (15–30 phút) có slide thuyết trình và lời giảng của giảng viên. |
| **Task giao cho tester** | *"Hãy trải nghiệm bài học mẫu này; ghi nhận lại các điểm kiến thức quan trọng bạn cần nhớ và chuẩn bị tài liệu để ôn tập lại sau bài học."* |
| **Desired outcome** | Có được bản ghi nhớ/tài liệu ôn tập chính xác, đúng trọng tâm mà không bị đứt đoạn quá trình nghe giảng. |
| **Content / Data fixture** | Cùng 1 bài giảng mẫu video + slide chuẩn hoá: *"Bài 3 — Phân tích Cấu trúc Chi phí Doanh nghiệp"* (gồm 3 khái niệm cốt lõi, 1 biểu đồ, 1 tình huống ví dụ). |

---

### 2.2. Những thứ được phép khác biệt giữa 3 Options

```text
[Option C: Don't Act]           [Option B: Ask]                 [Option A: Act]
User chủ động hoàn toàn  ───►  User + AI đồng sáng tạo   ───►  AI chủ động tổng hợp
(User-led / Pure tool)         (Human-in-the-loop)             (AI-led / High automation)
```

| Thành phần | Option A — AI Notes tự tổng hợp | Option B — AI gợi ý, User xác nhận | Option C — Quick Bookmark 1 chạm (Không AI) |
|---|---|---|---|
| **Solution Mechanism** | Highlight/đánh dấu icon trong bài → Khi bài kết thúc, AI tự động tổng hợp toàn bộ thành bản Smart Note có cấu trúc. | Khi bài kết thúc, AI phân tích bài giảng và đề xuất 3 thẻ "Key Takeaways"; User duyệt, sửa, bổ sung trước khi lưu. | Bấm 1 chạm (phím tắt/icon) ghim timestamp; hệ thống lưu chính xác vị trí và trích xuất ảnh slide + transcript thô. |
| **User làm gì?** | Highlight các câu quan trọng khi nghe; đọc lướt và chỉnh sửa bản note do AI tạo sau bài học. | Xem lướt 3 thẻ gợi ý của AI; chọn chấp nhận, chỉnh sửa câu chữ hoặc thêm ý riêng rồi bấm lưu. | Bấm nút Bookmark ngay khoảnh khắc muốn nhớ; tự mở xem lại slide và vị trí video khi ôn tập. |
| **AI làm gì?** | **Act** — Tự động xử lý NLP, trích xuất cấu trúc và tạo văn bản hoàn chỉnh. | **Ask** — Tạo bản nháp gợi ý dạng thẻ độc lập, chờ user tương tác và duyệt. | **Don't Act** — Không dùng AI, chỉ là công cụ capture dữ liệu thời gian thực. |
| **Trigger** | Tự động kích hoạt khi video kết thúc (hoặc khi user bấm "Hoàn thành bài"). | Hiện pop-up / panel 3 thẻ gợi ý khi video kết thúc. | User chủ động bấm phím tắt `B` hoặc nút `Bookmark` trong lúc video đang chạy. |
| **Trade-off chính** | Tiết kiệm công sức tối đa nhưng có nguy cơ AI tổng hợp sai lệch ý cá nhân; user dễ ỷ lại thụ động. | Cân bằng giữa tiết kiệm thời gian và sự ghi nhớ chủ động; tốn thêm 1–2 phút tương tác duyệt thẻ. | Không bao giờ lo AI bịa đặt/sai lệch; nhưng đòi hỏi user phải tự đọc lại transcript thô khi ôn tập. |

---

### 2.3. Distance Check (Kiểm tra độ khác biệt thực chất)
- **A khác B vì:** Option A tự động sinh toàn bộ tài liệu hoàn chỉnh mà không cần hỏi (AI-led), trong khi Option B bắt buộc user phải tương tác xác nhận từng thẻ ý kiến trước khi ghi vào sổ (Co-creation).
- **B khác C vì:** Option B dùng AI để hiểu nội dung và đề xuất ý nghĩa (Semantic synthesis), trong khi Option C hoàn toàn không có AI, chỉ ghi nhận dữ liệu toạ độ thời gian và hình ảnh thô (Deterministic bookmarking).
- **A khác C vì:** Option A chuyển giao toàn bộ quyền tổng hợp nội dung cho AI (High automation), còn Option C giữ toàn bộ quyền và trách nhiệm tổ chức nội dung cho con người (Zero AI).

---

## 3. Chặng 3 — Human–AI Design Pass

### 3.1. Human–AI Decision Table

| Tiêu chí | Option A: AI Notes tự tổng hợp | Option B: AI gợi ý, User xác nhận | Option C: Quick Bookmark 1 chạm |
|---|---|---|---|
| **1. User làm gì? AI làm gì?** | • **User:** Highlight/tag khi nghe; review & chỉnh sửa note sau bài.<br>• **AI:** Gom highlight + transcript bài học để tạo tài liệu có cấu trúc. | • **User:** Đọc 3 thẻ gợi ý, chọn giữ/sửa/thêm ý riêng.<br>• **AI:** Phân tích điểm nhấn, đưa 3 thẻ gợi ý súc tích kèm trích dẫn. | • **User:** Bấm phím tắt bookmark; tự xem lại slide và ghi chú thủ công khi ôn.<br>• **AI:** Don't act — Không can thiệp. |
| **2. Agency Level: Act / Ask / Don't Act?** | **ACT** — Giảm tối đa nhận thức và thao tác ghi chép trong lúc nghe giảng. | **ASK** — AI chỉ là trợ lý đề xuất; quyền kiểm soát thuộc về người học. | **DON'T ACT** — Làm điểm tựa đối chứng thuần công cụ (Pure tool). |
| **3. Expectation & Giới hạn** | Thông báo trước: *"AI sẽ tự động tổng hợp các đoạn highlight thành ghi chú. AI có thể diễn đạt khác ý bạn, bạn có thể chỉnh sửa lại."* | Tiêu đề giao diện: *"Gợi ý 3 điểm cốt lõi — Duyệt hoặc chỉnh sửa trước khi lưu vào sổ tay."* | Hướng dẫn: *"Bấm phím 'B' để đánh dấu ngay mốc quan trọng và lưu slide tương ứng."* |
| **4. Evidence & Uncertainty** | • **Evidence:** Gắn link trích dẫn `[04:15]` hoặc `[Slide 6]` ở từng bullet point.<br>• **Uncertainty:** Ý nào AI suy đoán độ tin cậy thấp sẽ gắn tag `[AI diễn giải]` và tô màu xám nhạt. | • **Evidence:** Mỗi thẻ ghi rõ: *"Dựa vào đoạn bạn xem lại tại [06:30]"*.<br>• **Uncertainty:** Thẻ mở, gắn nhãn `[Gợi ý tham khảo]`. | • **Evidence:** 100% dữ liệu gốc thật (Ảnh slide + Video timestamp + 10s transcript).<br>• **Uncertainty:** Bằng 0 (không suy diễn). |
| **5. Control & Recovery** | • **Kiểm soát:** Nút `[Chỉnh sửa trực tiếp]`, `[Tạo lại (Regenerate)]`.<br>• **Recovery:** Nút `[Xem highlight thô gốc]` để lấy lại toàn bộ dữ liệu ban đầu nếu AI tóm tắt hỏng. | • **Kiểm soát:** Nút `[Chấp nhận]`, `[Chỉnh sửa thẻ]`, `[Xóa thẻ]`, `[Thêm ý]`.<br>• **Recovery:** Nút `[Bỏ qua tất cả gợi ý]` để mở trang ghi chú trắng. | • **Kiểm soát:** Nút `[Gán nhãn]`, `[Kéo thả sắp xếp]`, `[Xoá bookmark]`.<br>• **Recovery:** 1 click xoá mốc đánh dấu nhầm. |

---

### 3.2. Feedback & Data Governance
- **Dữ liệu sử dụng:** Chỉ truy xuất dữ liệu học tập trong phiên (video timestamp, click highlight, transcript bài học). Không quét dữ liệu cá nhân ngoài phạm vi bài học.
- **Lưu trữ & Học hỏi:** Note và Bookmark được lưu riêng theo tài khoản cá nhân. Mọi chỉnh sửa của học viên không tự ý dùng để huấn luyện model mà không có sự đồng thuận.
- **Rút quyền:** Học viên có thể nhấn `[Xoá toàn bộ dữ liệu & ghi chú bài này]` bất cứ lúc nào.

---

## 4. Tự kiểm tra các tiêu chuẩn Gates

| Tiêu chuẩn Gate | Trạng thái | Đánh giá thực tế của nhóm |
|---|:---:|---|
| **GATE 1 — Evidence continuity** | ✅ ĐẠT | Hypothesis Problem bám sát 3 Practice Notes Day 17; nêu rõ user, situation, job, barrier, consequence và điều chưa chứng minh. |
| **GATE 2 — Meaningful options** | ✅ ĐẠT | 3 options chung 100% user, context, task và content fixture; khác nhau rõ rệt trên trục phân chia quyền hạn (Act vs Ask vs Don't Act). |
| **GATE 3 — Human control** | ✅ ĐẠT | Cả 3 options đều có điểm hiển thị Evidence, mức độ tự tin, và cơ chế kiểm soát / phục hồi rõ ràng khi AI làm sai. |

---
*Tài liệu này là căn cứ thiết kế chính thức của Team Moi để triển khai 3 Micro-prototypes trong Chặng 4.*
