# 6. Chặng 4 — Build ba micro-prototype · 80 phút

### 1. Scope chuẩn

Mỗi option chỉ cần 2–3 màn hình hoặc trạng thái:

```text
COMMON CONTEXT
      ↓
CRITICAL INTERACTION
      ↓
RESULT / USER DECISION
```

Cả ba options nên dùng chung khoảng 70%:

- context screen;
- content/data fixture;
- component và visual style;
- task và desired outcome.

Chỉ critical interaction cần khác rõ.

---

### 2. Definition of testable

Prototype sẵn sàng khi:

- Tester có thể tự mở và thao tác A/B/C.
- Cả ba bắt đầu từ cùng một context và task.
- Option không cần facilitator narrate để hiểu.
- Nội dung đủ thật để tester ra quyết định.
- Mỗi option thể hiện được điểm user lấy lại control.
- Có đường reset về common context.

**Được dùng:**

- Figma, Framer hoặc công cụ tương đương.
- HTML/CSS/JavaScript.
- Prototype giấy có flow rõ.
- Canned AI output.
- Wizard of Oz, miễn người mô phỏng AI không giải thích giao diện hộ tester.

**Không cần:**

- Model hoặc API thật.
- Full onboarding hoặc dashboard.
- Responsive cho nhiều thiết bị.
- Visual polish hoàn chỉnh.
- Một failure catalog đầy đủ.

---

### 3. Build order

| Phút | Việc cần làm |
|---:|---|
| 0–10 | Vẽ common context, task và content fixture dùng cho cả ba. |
| 10–55 | Mỗi thành viên build một option bằng shared components. |
| 55–65 | Thêm control/recovery và evidence/uncertainty cần thiết. |
| 65–75 | Mỗi thành viên tự test option do người khác build. |
| 75–80 | Chuẩn hóa A/B/C, kiểm link và reset path. |

---

### 4. Prototype annotation

Đặt annotation ngoài frame, không hiện cho tester:

```text
OPTION ___
We expect the tester to: ______________________________________
Watch for: ____________________________________________________
Do not explain: _______________________________________________
```

---

> [!NOTE] **Tự kiểm · GATE 4 — Test-ready**  
> Một người không build có thể mở, thực hiện cùng task qua A/B/C và quay về context ban đầu mà không cần người khác giải thích.
