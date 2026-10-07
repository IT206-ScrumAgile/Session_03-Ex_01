
## Phần 1 – Phân tích

| Hạng mục | Đúng/Sai | Vi phạm tiêu chí/quy tắc nào | Lý do (1 câu) |
|---|---|---|---|
| H1. Thẻ trên cùng "Làm tính năng đi ghép" chỉ có tiêu đề, không mô tả | **Sai** | D.E.E.P – **D**etailed appropriately (chi tiết vừa đủ theo vị trí ưu tiên); chưa sẵn sàng để Developers nhận | Thẻ ở đầu cột sắp được làm nên phải chi tiết nhất (mô tả, tiêu chí chấp nhận), nhưng thẻ này quá mơ hồ khiến Developers phải hỏi lại yêu cầu. |
| H2. "Đổi màu giao diện theo mùa lễ hội" nằm trên "Tự động chia tiền cho các khách đi ghép" | **Sai** | D.E.E.P – **P**rioritized (sắp xếp ưu tiên theo giá trị) | Thẻ chia tiền là giá trị cốt lõi của tính năng đi ghép nhưng bị xếp dưới thẻ chỉ mang tính trang trí, nên thứ tự không theo giá trị. |
| H3. "Khách đánh giá bạn đi ghép" ở cuối cột, chỉ có tiêu đề ngắn, ước lượng sơ bộ "lớn" | **Đúng** | — | Thẻ ở cuối cột chưa cần làm sớm nên chỉ cần tiêu đề ngắn và ước lượng sơ bộ là đã đạt **D**etailed appropriately và **E**stimated; việc chưa chi tiết là đúng chuẩn, không phải lỗi. |
| H4. Tú tự thêm thẻ "Tối ưu tốc độ tải bản đồ" và kéo lên đầu cột Product Backlog vì thấy cần làm gấp | **Sai** | Quy tắc quyền sở hữu: chỉ Product Owner được thêm, bớt, sắp xếp thứ tự (Product Backlog là nguồn sự thật duy nhất) | Tú là Developer nên không có quyền thêm thẻ hay đổi thứ tự, và lý do "cần gấp" không thay thế được quyết định ưu tiên của PO Đức. |
| H5. Bảng chỉ có 4 cột Product Backlog → Sprint Backlog → In Progress → Done; thẻ code xong kéo thẳng sang Done | **Sai** | Quy tắc luồng cột: chỉ thẻ đạt tiêu chuẩn "xong" (Definition of Done) mới vào Done | Thiếu cột kiểm tra/nghiệm thu nên thẻ mới code xong chưa được xác nhận đạt DoD vẫn bị coi là đã hoàn thành. |

---

## Phần 2 – Sửa lỗi

**H1.** Thẻ "Làm tính năng đi ghép" được PO Đức làm rõ và tách thành thẻ cụ thể (ví dụ "Khách tìm và đặt chuyến đi ghép"), bổ sung mô tả, tiêu chí chấp nhận và ước lượng để Developers hiểu ngay mà không phải hỏi lại.

**H2.** PO Đức xếp lại thứ tự để "Tự động chia tiền cho các khách đi ghép" nằm phía trên "Đổi màu giao diện theo mùa lễ hội" (thẻ giá trị thấp được đẩy xuống dưới).

**H3.** *Giữ nguyên* – thẻ "Khách đánh giá bạn đi ghép" ở cuối cột với tiêu đề ngắn và ước lượng sơ bộ "lớn" là đã đúng.

**H4.** Thẻ "Tối ưu tốc độ tải bản đồ" được gỡ khỏi đầu cột; Tú chỉ *đề xuất* với PO Đức, và chỉ khi Đức đồng ý thì Đức mới thêm thẻ và đặt vào vị trí phù hợp với giá trị.

**H5.** Bảng Trello gồm đủ các cột theo thứ tự từ trái sang phải:

1. **Product Backlog**
2. **Sprint Backlog**
3. **In Progress**
4. **Review / Testing** (kiểm tra theo Definition of Done)
5. **Done** (chỉ thẻ đã đạt DoD mới được kéo vào)

**Kết quả:** Developers nhìn vào đầu cột Product Backlog là biết ngay thẻ nào làm trước (thẻ đã chi tiết, xếp theo giá trị, do PO sắp xếp), và chỉ những thẻ nằm ở cột Done mới thật sự hoàn thành.
