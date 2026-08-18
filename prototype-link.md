# Prototype Links — AI Notes: Personal Learning Notes

> **Nhóm:** Team Moi  
> **Case:** Case B — AI Notes  
> **Ngày:** Day 18

---

## Cách trải nghiệm

Truy cập trực tiếp vào đường link web bên dưới bằng trình duyệt bất kỳ (trên máy tính hoặc điện thoại). Không cần cài đặt bất kỳ công cụ nào.

---

## Link Prototype Trực Tuyến (Live on Netlify)

**Trang chủ Prototype (Landing Page):** [https://day18-teammoi-optiona-b-c.netlify.app/](https://day18-teammoi-optiona-b-c.netlify.app/)

### Link trực tiếp từng Option:

| Option | Mô tả Agency | Link trực tiếp |
|---|---|---|
| **A — AI tự tổng hợp** | **Act** (AI tự động tạo Smart Note sau bài) | [Trải nghiệm Option A](https://day18-teammoi-optiona-b-c.netlify.app/option-a.html) |
| **B — AI gợi ý, bạn duyệt** | **Ask** (AI gợi ý 3 Key Takeaways, user duyệt/sửa/xoá) | [Trải nghiệm Option B](https://day18-teammoi-optiona-b-c.netlify.app/option-b.html) |
| **C — Bookmark nhanh** | **Don't Act** (Ghim mốc 1 chạm, không AI can thiệp) | [Trải nghiệm Option C](https://day18-teammoi-optiona-b-c.netlify.app/option-c.html) |

---

## Common Context dùng chung cho cả A/B/C

- **Bài giảng mẫu:** "Bài 3 — Phân tích Cấu trúc Chi phí Doanh nghiệp" (4 slides)
- **Nội dung:** Chi phí cố định vs biến đổi, Điểm hoà vốn (BEP), Case Study quán cafe startup
- **Task cho tester:** "Hãy trải nghiệm bài học mẫu; ghi nhận lại các điểm kiến thức quan trọng bạn cần nhớ bằng từng phương án."
- **Nền tảng:** Web HTML/CSS/JavaScript (deploy trực tiếp trên Netlify)

---

## Prototype Annotations (nội bộ nhóm — không hiện cho tester)

### OPTION A — AI tự tổng hợp
- **We expect the tester to:** Highlight vài đoạn quan trọng khi xem slide, rồi đọc lướt bản Smart Note do AI tạo ra.
- **Watch for:** Tester có đọc toàn bộ note hay chỉ lướt? Có bấm "Chỉnh sửa" hoặc "Xem highlight thô" không? Có phát hiện tag `[AI diễn giải]` không?
- **Do not explain:** Không giải thích nút Chỉnh sửa, Tạo lại hoặc Xem highlight thô làm gì; để tester tự khám phá.

### OPTION B — AI gợi ý, bạn duyệt
- **We expect the tester to:** Đọc từng thẻ gợi ý, quyết định chấp nhận/sửa/xoá, có thể thêm ý riêng.
- **Watch for:** Tester chấp nhận hết mà không đọc hay cân nhắc từng thẻ? Có dùng nút "Thêm ghi chú riêng" không? Có bấm "Bỏ qua tất cả" không?
- **Do not explain:** Không giải thích sự khác biệt giữa chấp nhận/chỉnh sửa; không gợi ý tester nên giữ hay xoá thẻ nào.

### OPTION C — Bookmark nhanh
- **We expect the tester to:** Bấm nút Bookmark hoặc phím B khi gặp nội dung muốn nhớ.
- **Watch for:** Tester có biết phím tắt B không? Bookmark bao nhiêu mốc? Có cảm thấy thiếu tóm tắt khi xem lại danh sách thô không?
- **Do not explain:** Không nhắc phím B nếu tester không tự phát hiện; không giải thích tại sao không có AI tóm tắt.
