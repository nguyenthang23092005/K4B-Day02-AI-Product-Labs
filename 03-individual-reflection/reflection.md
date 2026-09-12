# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Nguyễn Văn Thăng
- Mã học viên: 2A202602835
- Nhóm: B1 - Không thích điểm danh
- Candidate problem nhóm chọn: Summarize Meeting & Action Items

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tôi scan 8 vấn đề trong công việc học tập và trưởng nhóm, có số đo thời gian/tần suất cho từng vấn đề. | Đưa vào nhóm 3 vấn đề có evidence rõ: Weekly Report, tóm tắt paper và Meeting Minutes. |
| Pitch Problem Card | Tôi pitch Card #1 về việc mất 100 phút/tuần để gom Trello, GitHub và Discord/Zalo thành Weekly Progress Report. | Nhóm thấy workflow, bottleneck ở phần narrative và metric giảm xuống dưới 35 phút khá rõ. |
| Challenge bài của bạn khác | Tôi challenge rủi ro dữ liệu chat rời rạc và nguy cơ AI bịa tiến độ, owner hoặc deadline. | Nhóm bổ sung human review, fallback và giới hạn scope thay vì coi output AI là kết quả cuối. |
| Gom trùng / cluster | Tôi cùng nhóm nhận ra Weekly Report, Meeting Minutes và record summarization đều có pattern dữ liệu rời rạc → output có cấu trúc. | Ba candidate được gom vào Cluster C; #9 và #15 được merge vì gần như cùng một core problem. |
| Chọn candidate problem | Tôi tham gia so sánh Weekly Progress Report với Summarize Meeting & Action Items theo actor, workflow, impact và khả năng làm trong lab. | Nhóm chọn Summarize Meeting & Action Items với 34/35 điểm vì scope hẹp và phù hợp hơn để pilot. |
| Validation / research | Tôi đóng góp góc nhìn về nhu cầu tổng hợp nội dung sau họp và xem xét các pattern từ Slack AI, Gemini in Drive và Fellow AI Meeting Notes. | Nhóm xác định pain chính là biến nội dung dài thành quyết định và Action Items, không phải chép lại toàn bộ cuộc họp. |
| Workflow nhóm | Tôi góp phần làm rõ bottleneck là bước lọc ý kiến thành task, owner và deadline, đồng thời giữ bước review của trưởng nhóm. | Workflow được thu từ 7 bước/60 phút xuống 5 bước/khoảng 13 phút, có fallback khi transcript kém. |
| Problem Statement | Tôi góp ý chốt baseline 30–60 phút/buổi, mục tiêu dưới 15 phút và boundary không tự gửi/không tự quyết định task. | PS v0 được phát triển thành PS v1 có metric, điểm can thiệp AI và người chịu trách nhiệm kiểm tra. |
| Rule / Workflow / Agent | Tôi tham gia phân biệt template Rule, pipeline Workflow và Agent tự lấy dữ liệu/tự gửi. | Nhóm chọn Workflow có AI + human-in-the-loop vì flow tuyến tính, chưa cần Agent. |
| Decision | Tôi cùng nhóm xác định pilot nhỏ nhất là dùng transcript/notes của 1–2 buổi họp thật và đo thời gian, lỗi trích xuất, thời gian edit. | Nhóm ra quyết định GO với scope nhỏ và đặt điều kiện rollback nếu AI sai liên tiếp hoặc phải viết lại phần lớn output. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Tôi đóng góp rõ nhất ở việc đưa problem Weekly Progress Report có số đo 100 phút/tuần vào thảo luận, sau đó giúp nhóm nhận ra nó cùng pattern với Meeting Minutes. Dấu tay của tôi còn nằm ở các metric thời gian, phần human boundary và các câu hỏi về hallucination khi AI xử lý dữ liệu chat.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý các công việc lặp lại/tốn thời gian trong bối cảnh trưởng nhóm đồ án. | Gợi ý thêm việc gom dữ liệu từ Discord/Zalo/GitHub và tổng hợp biên bản họp. | Gợi ý tự động nhắc lịch học nhưng đó không phải pain thật của tôi. | Tôi bỏ ý nhắc lịch và chỉ giữ các vấn đề tôi đã đo được bằng thời gian/tần suất. |
| Problem Card | Phản biện các card và giúp kiểm tra actor, bottleneck, metric, fallback. | Giúp tôi thấy Card #1 có workflow cố định và bottleneck rõ ở narrative. | Có thể nói chung rằng AI sẽ tự gom dữ liệu từ nhiều nền tảng mà không tính công sức nhập liệu. | Tôi thu hẹp input thành text summary Trello và các commit/PR chính, không cào toàn bộ chat. |
| Workflow | Hỗ trợ diễn đạt current/future workflow và chia thời gian từng bước. | Giúp so sánh 100 phút hiện tại với quy trình có AI draft và human review. | Ước lượng thời gian AI quá lạc quan nếu transcript thiếu hoặc dữ liệu đầu vào bẩn. | Nhóm giữ bước review 8 phút và thêm fallback về record/note gốc. |
| Research | Hỗ trợ hệ thống hóa các tool/pattern meeting summary đã có. | Giúp nhóm nhận ra pattern phổ biến là AI draft rồi người thật xác nhận. | Không thể chứng minh các tool luôn trích đúng owner/deadline trong ngữ cảnh nhóm. | Tôi coi research là tham khảo thiết kế, không dùng như bằng chứng rằng prototype chắc chắn đúng. |
| Problem Statement | Gợi ý kiểm tra sự nhất quán giữa actor, workflow, impact và metric. | Giúp nhóm nhìn ra cần nêu rõ AI can thiệp sau transcript và trước bước viết output. | Có xu hướng làm PS rộng thành một hệ thống tự động toàn bộ meeting workflow. | Tôi giữ scope là summary + Action Items, không tự gửi và không tự quyết task cuối. |
| Rule / Workflow / Agent | Hỗ trợ lập bảng so sánh ba mức giải pháp. | Làm rõ flow tuyến tính phù hợp với Workflow hơn Agent. | Nếu chỉ nhìn vào khả năng của AI, giải pháp Agent có vẻ hấp dẫn nhưng vượt scope và tăng permission risk. | Tôi dùng câu hỏi 70–80% và human review để bảo vệ lựa chọn Workflow. |
| Decision | Hỗ trợ rà lại pilot, metric và điều kiện rollback. | Giúp biến ý tưởng thành phép thử 1–2 buổi họp với ba số cần đo. | Không thay thế được quyết định về mức lỗi owner/deadline mà nhóm có thể chấp nhận. | Nhóm tự chốt GO với scope nhỏ và rollback nếu phải viết lại phần lớn output trong hai buổi liên tiếp. |

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

Khi nghe top 3 problems của các bạn khác, tôi học được rằng một pain có thể rất thật nhưng vẫn chưa phải bài phù hợp nhất để làm trong lab. Candidate Weekly Progress Report của tôi có metric rõ, nhưng khi đặt cạnh Meeting & Action Items thì scope gom dữ liệu từ nhiều nền tảng rộng hơn. Tôi thay đổi cách nhìn từ việc muốn tự động hóa cả quy trình báo cáo sang chỉ giải quyết bước ngôn ngữ đang gây tốn thời gian nhất. Nhóm có lúc dễ solution-first khi nói về Agent tự lấy record, tự tạo task và tự gửi, nhưng việc hỏi lại về permission và hậu quả khi AI nhầm owner đã kéo thảo luận về Workflow. Tôi đóng góp thật sự vào artifact cuối bằng cách đưa evidence 100 phút/tuần, đặt câu hỏi về hallucination và thúc đẩy human review. Điều khó nhất khi viết Problem Statement là giữ metric tham vọng nhưng vẫn đo được, đồng thời viết boundary đủ rõ để AI không bị hiểu là người ra quyết định. Sau khi thảo luận, nhóm sửa mục tiêu thành dưới 15 phút/buổi thay vì chỉ nói “nhanh hơn”, và xác định ba số phải đo trong pilot. Tôi cũng hiểu rằng summary tốt không nhất thiết là chép đủ mọi nội dung, mà phải giúp người đọc biết quyết định nào đã chốt và ai cần làm gì. Nếu làm lại, tôi sẽ challenge sớm hơn về chất lượng transcript và cách định nghĩa một Action Item “đúng”, thay vì chỉ tập trung vào thời gian tiết kiệm. Tôi sẽ thử ngay trên một buổi họp thật để có số lỗi owner/deadline trước khi kết luận Workflow đã hiệu quả.

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

