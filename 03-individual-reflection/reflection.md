# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Võ Công Danh   
- Mã học viên: 2A202602739
- Nhóm: A1-ProB
- Candidate problem nhóm chọn:
Sinh viên phải kiểm tra email, Discord và các kênh thông báo để tìm thông tin quan trọng rồi chép deadline vào lịch thủ công.
---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân |Liệt kê 3 vấn đề |Tạo danh sách ban đầu để nhóm chọn vấn đề. |
| Pitch Problem Card | Trình bày vấn đề sắp xếp lịch thủ công, giải thích người gặp và quy trình hiện tại. |Nhóm có cơ sở để hiểu vấn đề và thảo luận. |
| Challenge bài của bạn khác |Hỏi liệu có cần dùng AI cho vấn đề đó không và nên dùng Rule, Workflow hay Agent. |Nhóm xem xét mức tự động hóa phù hợp thay vì mặc định dùng AI. |
| Gom trùng / cluster | Góp ý gộp các vấn đề về email, Discord và nhập deadline vào cùng cụm quản lý thông báo và lịch cá nhân. | Giúp nhóm nhìn ra candidate “trích deadline từ thông báo vào lịch”.|
| Chọn candidate problem |Đề xuất làm vấn đề nhập deadline và lịch từ tin nhắn. | Đưa ra một hướng candidate để nhóm cân nhắc.|
| Validation / research |Hỏi các thành viên trong nhóm về vấn đề. |Thu thập ý kiến ban đầu để kiểm tra vấn đề có phù hợp với nhóm. |
| Workflow nhóm | Viết workflow cho các problem.|Làm rõ các bước hiện tại, bước có thể dùng AI và bước người dùng kiểm tra. |
| Problem Statement | Góp ý để thu hẹp phạm vi vấn đề   |Giúp problem statement rõ actor, workflow và bước AI can thiệp hơn. |
| Rule / Workflow / Agent |Đề xuất chọn Workflow vì trình tự thực hiện đã rõ. |Giúp nhóm xác định hướng giải pháp có người dùng duyệt. |
| Decision |Góp ý chọn Not Yet vì nhóm chưa có baseline thực tế và chưa thử trên email thật. |Nhóm xác định cần validation trước khi quyết định triển khai rộng. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```
Tôi xây dựng workflow từ email hoặc tin nhắn đã chọn đến bước người dùng kiểm tra trước khi lưu lịch. Tôi cũng góp ý thu hẹp problem statement để xác định rõ phạm vi AI hỗ trợ.

```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý các vấn đề có thể gặp của sinh viên năm 4. | Giúp tạo danh sách ban đầu nhanh. | Có nhiều vấn đề, chưa chắc là pain thật. | Chọn lọc và giữ các vấn đề thực tiễn. |
| Problem Card | Soạn khung actor, workflow, bottleneck và metric. | Giúp card đủ các mục cần có. | Có số phút minh họa nhưng chưa phải số đo thật. | Ghi rõ số liệu cần đo lại khi thử nghiệm. |
| Workflow | Gợi ý workflow trước và sau khi có AI. | Làm rõ bước Rule, AI, người dùng và fallback. | Phạm vi ban đầu quá rộng, gồm nhiều nền tảng. | Thu hẹp thử nghiệm vào email do người dùng chọn. |
| Research | Tóm tắt cách Zapier và Make hỗ trợ email, AI và lịch. | Giúp so sánh giải pháp có sẵn. | Có thể mô tả tính năng chưa chính xác hoặc đã thay đổi. | Kiểm tra lại link chính thức trước khi đưa vào bài. |
| Problem Statement | Viết lại vấn đề theo actor, workflow, bottleneck và impact. | Giúp câu vấn đề rõ, ngắn hơn. | Có xu hướng khẳng định pain phổ biến khi chưa có bằng chứng. | Đổi thành giả thuyết cần kiểm chứng. |
| Rule / Workflow / Agent | So sánh ba mức tự động hóa. | Giúp xác định Workflow phù hợp với quy trình. | So sánh còn chung chung nếu không gắn với từng bước. | Chọn Workflow vì người dùng cần duyệt trước khi lưu lịch. |
| Decision | Hỗ trợ rà lại các điều kiện Go, Not Yet và No-Go. | Nhắc nhóm về baseline, dữ liệu và rủi ro AI sai. | AI không thể tự quyết định thay nhóm. | Chọn Not Yet vì chưa có số đo thực tế và chưa thử trên email thật. |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```
Khi nghe top 3 problems của các bạn khác, tôi nhận ra một vấn đề quen thuộc chưa chắc đã phù hợp để làm dự án. Một problem tốt cần có actor, workflow và bottleneck rõ ràng. Problem cũng cần có cách đo impact trong thời gian ngắn. Tôi thấy nhiều ý tưởng hay nhưng quá rộng hoặc khó kiểm chứng. Điều này giúp tôi chú ý hơn đến phạm vi thử nghiệm.
Dấu tay của tôi trong artifact cuối nằm ở phần workflow. Tôi góp ý các bước từ chọn email đến lưu lịch. Tôi cũng nhấn mạnh bước người dùng kiểm tra trước khi lưu. Tôi góp ý thu hẹp AI vào email đã được chọn.
Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn về baseline. Tôi sẽ hỏi rõ nhóm đã đo thời gian xử lý thủ công chưa. Tôi cũng sẽ hỏi liệu bộ lọc email và mẫu nhập lịch có giải quyết đủ tốt trước khi dùng AI hay không.

```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [X] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [X] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [X] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [X] [15đ] Nhóm có workflow trước/sau
- [X] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [X] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [X] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [X] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [X] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

