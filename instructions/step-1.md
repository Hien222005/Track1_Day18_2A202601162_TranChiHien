# 1. Đề bài và cách làm

> **Bản đồ Lab:** Đọc trước khi bắt đầu  
> ⏱️ **Thời lượng:** 180 phút | 🎯 **Cấp độ:** Trung cấp

Nhóm tiếp tục đúng case VLearn của Day 17, thiết kế ba Solution Options và build ba micro-prototype. Mỗi thành viên chịu trách nhiệm chính một option và test cả bộ A/B/C với một người khác; nhóm tổng hợp ba feedback thành một thay đổi tiếp theo.

---

### Bài này đang nói về điều gì?

- Ba prototype cùng xuất phát từ một Hypothesis Problem nhưng đại diện cho ba cách giải khác nhau.
- Phép so sánh chỉ có nghĩa khi mỗi tester trải nghiệm cả A/B/C với cùng user context, task, content và desired outcome.
- Ba feedback đầu tiên giúp chọn iteration tiếp theo; không đủ để tuyên bố solution đã được validated.

```text
Day 17 Evidence → Hypothesis Problem → Three Solution Options → Human–AI Design → Three Micro-prototypes → Three A/B/C Tests → One Next Change
```

---

### Buổi Lab diễn ra như thế nào?

1. **0:00–0:15** `Nhóm` — **Tổng hợp evidence:** Đặt ba Practice Notes cạnh nhau và chốt Hypothesis Problem nhóm sẽ dùng làm điểm xuất phát.
2. **0:15–0:35** `Nhóm` — **Chọn ba Solution Options:** Mở lại Solution Parking Lot của Day 17 và chọn ba cách giải cho cùng một problem, user và task.
3. **0:35–1:05** `Nhóm` — **Human–AI Design pass:** Chốt expectation, role and agency, evidence and uncertainty, control and recovery cho từng option.
4. **1:05–2:25** `Cá nhân + Nhóm` — **Build ba micro-prototype:** Mỗi thành viên chịu trách nhiệm chính một option, dùng chung context, content và visual components.
5. **2:25–2:40** `Nhóm` — **Chuẩn bị test:** Chốt một context, một task và các hành vi cần quan sát khi tester dùng A/B/C.
6. **2:40–3:00 hoặc ngoài giờ** `Cá nhân` — **Test với ba người:** Mỗi thành viên cho một người ngoài nhóm trải nghiệm cả A/B/C; nhóm mang về ba Feedback Notes và chốt một Next Change.

---

### Kết thúc bài, bạn có gì?

- Một Three-option Design Sheet và ba micro-prototype.
- Ba Prototype Feedback Notes và một Group Synthesis có Next Change cùng điều vẫn chưa được chứng minh.

> [!TIP] **Chưa cần lo**  
> Bài không chấm độ đẹp hoặc việc option ban đầu phải đúng. Một kết quả tốt có thể là phát hiện AI đang làm quá nhiều, user không hiểu vì sao output xuất hiện, hoặc hai options cần được kết hợp ở iteration tiếp theo.

---

Cuối Day 17, nhóm đã có một **Hypothesis Problem**, ba **Practice Notes** và một **Solution Parking Lot**. Day 18 không yêu cầu nhóm đi tìm một problem mới. Nhiệm vụ là mở lại solution space, biến ba cách giải thành ba Human–AI micro-prototype và mang cả bộ A/B/C đi test:

```text
DAY 17
3 Practice Notes + Hypothesis Problem + Solution Parking Lot
                              ↓
DAY 18
3 Solution Options
→ Human–AI Design
→ 3 Micro-prototypes
→ 3 Testers × A/B/C
→ 3 Feedback Notes
→ 1 Group Next Change
```

| Chặng | Thời gian | Câu hỏi trung tâm | Đầu ra |
|---|---:|---|---|
| 1. Tổng hợp evidence | 15 phút | Từ ba Practice Notes, nhóm tiếp tục Hypothesis Problem nào? | Evidence Snapshot + Hypothesis Problem |
| 2. Chọn ba Solution Options | 20 phút | Ba cách giải nào cùng problem nhưng chia công việc user–AI khác nhau? | Option A/B/C + Comparison Contract |
| 3. Human–AI Design pass | 30 phút | User và AI làm gì; user hiểu, kiểm soát và phục hồi thế nào? | Human–AI Decision Table |
| 4. Build ba micro-prototype | 80 phút | Cần build tối thiểu gì để tester trải nghiệm được khác biệt? | Three Micro-prototypes |
| 5. Chuẩn bị test | 15 phút | Context, task và behavior cần quan sát là gì? | Test Prompt + Observation Focus |
| 6. Test với ba người | 20 phút cuối hoặc ngoài giờ | Ba tester làm gì, chọn gì và đánh đổi điều gì? | 3 Feedback Notes + 1 Group Next Change |

### Luật của bài lab

1. **Giữ một Hypothesis Problem.** A/B/C phải cùng giải một problem cho cùng user và situation.
2. **Build ba solution, không phải ba phiên bản giao diện.** Khác màu, wording hoặc layout chưa tạo thành ba option.
3. **Mỗi option phải thể hiện một Human–AI interaction.** Nhóm phải nói rõ user làm gì, AI làm gì và ai giữ quyền quyết định.
4. **Prototype vừa đủ để test.** Mỗi option chỉ cần 2–3 trạng thái quanh một critical interaction; không build full product.
5. **Mỗi tester trải nghiệm cả ba.** Mỗi thành viên test với một người khác, nhưng không được chỉ mang option mình làm đi test.
6. **Ghi hành vi trước, diễn giải sau.** “Tester chọn B” chưa đủ nếu không có lý do, trade-off và hành vi đi kèm.
7. **Không tuyên bố validated.** Ba feedback tạo input cho iteration tiếp theo, không chứng minh product value hoặc market demand.

### Cách làm việc nhóm

- Ở Chặng 1–3, cả nhóm cùng chốt evidence, ba options và Human–AI decisions.
- Ở Chặng 4, mỗi thành viên **chịu trách nhiệm chính một option** nhưng phải dùng chung context, content và visual components.
- Trong 10–15 phút cuối prototype sprint, mỗi người thử option do người khác build; cả nhóm chuẩn hóa A/B/C.
- Ở Chặng 6, mỗi thành viên tự facilitate và ghi một Feedback Note cho một tester ngoài nhóm. Cả ba tester đều phải dùng A/B/C.
- Sau buổi học, mỗi thành viên nộp repo cá nhân và ghi rõ phần mình đã đóng góp vào sản phẩm chung.

### Sử dụng AI trong bài lab

Được dùng AI để gợi ý cơ chế, tạo dữ liệu mẫu, canned output, code hoặc rà soát câu hỏi dẫn dắt. Không được dùng AI để tạo quote, observation hay feedback không tồn tại; làm sạch evidence đến mức không còn phân biệt lời user với diễn giải; hoặc viết thay phần đóng góp và reflection cá nhân. Mọi cách dùng AI phải được khai báo.
