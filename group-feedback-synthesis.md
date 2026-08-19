# Group Feedback Synthesis — Tổng hợp Kết quả Test 3 Người

> **Nhóm:** Team Moi  
> **Case:** Case B — AI Notes: Personal Learning Notes  
> **Thành viên tham gia:**  
> - Trần Chí Hiển (MHV: 2A202601162)
> - Hồ Lương An (MHV: 2A202601332)
> - Vũ Nguyễn Bảo Sơn (MHV: 2A202601116)  
> **Link Prototype A/B/C:** [https://day18-teammoi-optiona-b-c.netlify.app/](https://day18-teammoi-optiona-b-c.netlify.app/)  

---

## 1. Bảng Ma trận Tổng hợp 3 Feedback

| Nội dung | Feedback 1 (Hiển) | Feedback 2 (An) | Feedback 3 (Sơn) | Pattern hoặc khác biệt |
|---|---|---|---|---|
| **First action** | Giao diện rõ ràng, tester nhìn là biết cách thao tác cơ bản | Tester lướt nhanh slide để nắm nội dung, chú ý ngay các nút đánh dấu nhanh (Quan trọng, Chưa hiểu) và thử luôn tính năng bôi đen chọn chữ để lưu keyword | Tester mở lần lượt cả 3 option, thử tương tác ngay | Cả ba tester đều chủ động thao tác/khám phá ngay trên giao diện mà không cần hướng dẫn thêm — cả 3 option đủ trực quan để bắt đầu |
| **Breakdown chính** | Tester khúc mắc về sự khác nhau giữa Option A và B về mặt tính năng | Option A mượt mà, không khó khăn; Option B giống A nhưng yếu hơn, phải dừng lại duyệt từng thẻ gợi ý nên mất thời gian, lắt nhắt; Option C phải "note chay" hoàn toàn vì không có AI | Option A: một số tính năng chưa hiểu hết nhưng vẫn dùng tiếp; Option C: do dự vì chỉ đánh dấu được 1 slide, chưa rõ bước tiếp theo | Option A vận hành mượt nhất trong cả 3 ca; điểm nghẽn lặp lại ở Option B (duyệt từng thẻ gợi ý gây lắt nhắt) và Option C (thiếu AI khiến phải tự ghi chép hoặc không rõ bước kế tiếp) |
| **Cách lấy lại control** | Muốn cải thiện thêm cho Option B để xử lý đúng vấn đề đang gặp | Option A: bấm Chỉnh sửa/Tạo lại, mở Xem lại đánh dấu gốc; Option B: bấm Chỉnh sửa thẻ, Thêm ghi chú riêng; Option C: bôi đen trực tiếp keyword/công thức để tạo bookmark | Quay lại Option A vì thấy đầy đủ chức năng nhất | Khi vướng mắc, cả ba đều tìm cách chỉnh sửa/xem lại nội dung gốc do AI tạo ra thay vì bỏ cuộc — nhu cầu chung về khả năng kiểm soát output AI |
| **Option được chọn** | **A** | **A** | **A** | Đồng nhất 3/3 — Option A được chọn ở cả ba ca test |
| **Trade-off** | Option A giải quyết đúng vấn đề, nhanh và thuận lợi nhất; trade-off là chất lượng note AI gen có thể bị ảnh hưởng do thiếu context/ngữ cảnh lúc đó | Chấp nhận câu chữ AI viết lại có thể khác văn phong cá nhân, nhưng sửa được trực tiếp và xem được mốc nguồn nên không đáng ngại | Option A tiện nhất, làm được nhiều thứ dù có một số tính năng tester chưa hiểu rõ | Cả ba đều đánh đổi độ chính xác/văn phong của nội dung AI tạo ra để lấy tốc độ và độ đầy đủ, miễn là có thể chỉnh sửa lại được |

---

## 2. Các Quyết định & Phát hiện của Nhóm

### 🎯 Một Next Change nhóm chốt:
> Phát triển tiếp theo hướng **Option A**: giữ cơ chế AI tự tổng hợp Smart Note sau bài giảng kèm trích dẫn thời gian/nguồn, đưa tính năng bôi đen chữ trực tiếp trên slide từ Option C vào làm đầu vào cho AI ở Option A, và bổ sung onboarding/tooltip cho các tính năng mà tester chưa hiểu rõ ngay lần đầu dùng.

### 📌 Evidence nào dẫn tới quyết định này:
> Cả 3/3 tester (Hiển, An, Sơn) đều chọn Option A, mô tả là "đầy đủ nhất", "tiện nhất", "giải quyết đúng vấn đề" dù một số tính năng chưa hiểu hết ngay từ đầu. Option B bị đánh giá yếu hơn vì thao tác duyệt từng thẻ gợi ý gây cảm giác lắt nhắt, dở dang (An, Sơn). Option C được đánh giá cao ở điểm bôi đen chữ trên slide giúp tiết kiệm thời gian ghi chép thủ công (An), nhưng thiếu flow rõ ràng sau khi đánh dấu (Sơn) và không được tester nào chọn làm phương án chính (Hiển: "Option C không được các Tester ủng hộ").

### 🔴 Still Unproven sau ba feedback:
> Chưa rõ chất lượng/độ chính xác của Smart Note do AI tổng hợp ở Option A có đủ tốt khi gặp bài giảng dài, nhiều thuật ngữ chuyên môn hoặc thiếu ngữ cảnh hay không (Hiển, An); chưa biết các tính năng tester chưa hiểu rõ trong Option A có trở thành rào cản khi dùng lâu dài không (Sơn); và chưa xác định được liệu học viên có thực sự chủ động mở lại Smart Note để ôn tập định kỳ hay vẫn bị thói quen lười ôn tập cản trở (An).
