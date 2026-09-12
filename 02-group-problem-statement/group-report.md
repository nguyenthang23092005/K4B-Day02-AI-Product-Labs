# 02 — Group Problem Statement

## Thông tin nhóm

| | |
|---|---|
| **Tên nhóm** | B1 - Không thích điểm danh |
| **Thành viên 1** | Lê Đức Hùng — 2A202602849 — Trưởng nhóm |
| **Thành viên 2** | Nguyễn Huy Hoàng — 2A202602738 — Thành viên |
| **Thành viên 3** | Nguyễn Hà Khuê — 2A202602938 — Thành viên |
| **Thành viên 4** | Nguyễn Văn Thăng — 2A202602835 — Thành viên |
| **Thành viên 5** | Đỗ Trọng Bình — 2A202602855 — Thành viên |
| **Ngày nộp** | 12/09/2026 |

---

## Candidate problem nhóm chọn

> **Summarize Meeting & Action Items:** Sau mỗi buổi họp/workshop online dài, trưởng nhóm hoặc người tổng hợp mất nhiều thời gian nghe lại record/đọc notes, gom các ý kiến rời rạc và chuyển chúng thành quyết định + Action Items rõ ràng.

---

# Phase 3 — Group Convergence

## Phase 3.1 — Trình bày Top 3 của từng thành viên

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Khuê | Tổng hợp nội dung ôn thi từ slides, textbook và notes rời rạc | Sinh viên | Đối chiếu nhiều nguồn rồi tự viết lại bản tổng hợp | Pain rõ, nhưng phụ thuộc chất lượng tài liệu đầu vào |
| 2 | Khuê | Ôn thụ động bằng highlight/đọc lại nên không biết mình yếu phần nào | Sinh viên | Thiếu bước self-test và feedback | AI phù hợp tạo quiz, nhưng quality metric khó hơn |
| 3 | Khuê | Lịch ôn 4–5 môn bị trượt là phải dựng lại từ đầu | Sinh viên | Re-plan thủ công khi lịch thay đổi | Workflow rõ, nhưng rule/process fix có thể giải quyết khá nhiều |
| 4 | Hoàng | Nhân viên mới không trả lời nhanh câu hỏi kỹ thuật của khách | Nhân viên showroom | Phải hỏi đồng nghiệp/tra Google tại quầy | Actor và bottleneck rõ, có impact tới trải nghiệm khách hàng |
| 5 | Hoàng | Soạn tin nhắn khuyến mãi thủ công cho khách cũ | Nhân viên bán hàng | Soạn và chỉnh từng tin gần giống nhau | Dễ automate nhưng pain chưa quá lớn |
| 6 | Hoàng | Bàn giao ca thiếu thông tin khiến ca sau phải hỏi lại | Nhân viên showroom | Sổ bàn giao không có format chuẩn | Có thể giải bằng process fix, chưa chắc cần AI |
| 7 | Thăng | Tổng hợp Weekly Progress Report từ Trello, GitHub, Discord/Zalo | Trưởng nhóm đồ án | Biến dữ liệu thô thành narrative/đánh giá tiến độ | Workflow và metric rất rõ |
| 8 | Thăng | Đọc và tóm tắt paper/tài liệu kỹ thuật dài | Sinh viên/NCKH | Đọc Methodology/Results và thuật ngữ chuyên ngành | AI giúp tốt nhưng cần kiểm hallucination |
| 9 | Thăng | Soạn Meeting Minutes và Action Items sau cuộc họp | Trưởng nhóm | Lọc ai làm gì, deadline khi nào từ thảo luận tự do | Pain lặp lại, phù hợp AI tóm tắt/trích xuất |
| 10 | Hùng | Viết content fanpage + video TikTok cho startup | Content Creator | Brainstorm góc tiếp cận và dựng video | Impact thời gian lớn nhưng lệch khỏi context chính của nhóm |
| 11 | Hùng | Đọc tài liệu Machine Learning dài trước seminar | Sinh viên | Đọc hiểu chi tiết nhiều tài liệu tiếng Anh | Pain lớn nhưng tương tự candidate #8 |
| 12 | Hùng | Phân loại lượng lớn email Gmail mỗi sáng | Sinh viên | Phân loại mail quan trọng/thường/rác | Rule + Workflow có thể xử lý khá tốt |
| 13 | Bình | Theo dõi lịch workshop từ Outlook, Discord rồi thêm Calendar thủ công | Học viên VinUni | Lọc thông báo lịch giữa nhiều kênh | Workflow rõ, nhưng phần lớn có thể automation bằng rule/API |
| 14 | Bình | Câu hỏi trong workshop bị hỏi và trả lời lại nhiều lần | Host + học viên | Câu trả lời cũ bị trôi, khó tìm lại | Có pain thật nhưng impact thời gian chưa lớn |
| 15 | Bình | Tổng hợp record họp/workshop dài thành ý chính và Action Items | Trưởng nhóm/người tổng hợp | Nghe lại record, gom ý kiến và chốt việc cần làm | Pain rõ, lặp lại, metric dễ đo và gần candidate #9 |

---

## Phase 3.2 — Gom trùng / Cluster

Sau khi nghe 15 candidates, nhóm gom lại thành 4 cluster dựa trên workflow và pain chung:

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| **A — Học tập & xử lý tài liệu** | #1, #2, #3, #8, #11 | Sinh viên mất nhiều thời gian tổng hợp tài liệu, đọc nội dung dài, tự đánh giá kiến thức hoặc lập kế hoạch học | #8 và #11 khá giống nhau về tóm tắt tài liệu học thuật |
| **B — Retail / Customer Operations** | #4, #5, #6, #10 | Công việc tại cửa hàng/startup bị lặp lại hoặc phụ thuộc nhiều vào thao tác thủ công và giao tiếp với khách | Một số bài có thể giải bằng template/rule mà chưa cần AI mạnh |
| **C — Meeting / Reporting / Action Items** | #7, #9, #15 | Sau quá trình làm việc/họp, một người phải gom thông tin rời rạc rồi biến thành narrative, quyết định hoặc Action Items rõ ràng | Cluster có overlap mạnh nhất; #9 và #15 gần như cùng một core problem |
| **D — Information Triage & Coordination** | #12, #13, #14 | Thông tin nằm rải ở nhiều kênh, người dùng phải tự lọc, tìm lại hoặc chuyển tiếp đúng thông tin vào đúng thời điểm | Nhiều bước có thể xử lý bằng Rule/Workflow Automation |

### Insight sau khi cluster

```text
Nhóm nhận thấy Cluster C có mức độ trùng lặp cao nhất giữa các thành viên. Weekly Report, Meeting Minutes và Record Summarization đều có chung một pattern: thông tin đầu vào rời rạc → con người phải đọc/nghe lại → xác định nội dung quan trọng → chuyển thành output có cấu trúc để người khác hành động.

Trong đó, candidate #9 và #15 gần như cùng một bài toán nên nhóm merge thành một candidate chung: “Summarize Meeting & Action Items”.
```

---

## Phase 3.3 — Shortlist

Sau khi gom trùng, nhóm giữ lại 3 candidate đại diện cho các hướng khác nhau:

| Candidate | Vì sao vào shortlist | Rủi ro / điều chưa rõ |
|---|---|---|
| **Summarize Meeting & Action Items** (#9 + #15) | Workflow rõ, lặp lại sau mỗi buổi họp, có baseline thời gian và phù hợp trực tiếp với context của nhóm | AI có thể nhầm task/owner/deadline nếu transcript thiếu hoặc câu nói mơ hồ |
| **Weekly Progress Report** (#7) | Tần suất cố định hàng tuần, bottleneck rõ ở bước viết narrative, impact đo được | Data đầu vào từ Trello/GitHub/chat có thể rời rạc và khó gom tự động |
| **Technical Q&A tại showroom** (#4) | Actor rõ, pain ảnh hưởng trực tiếp tới khách, success metric dễ đo bằng thời gian tra cứu | Cần nguồn dữ liệu sản phẩm đủ sạch và cập nhật |

**Candidate nhóm chọn:** **Summarize Meeting & Action Items**

**Vì sao chọn:**  
Problem này gần nhất với trải nghiệm thật của nhóm, xảy ra lặp lại sau các buổi họp/workshop và có workflow trước/sau rất dễ đo. Bottleneck nằm ở việc nghe/đọc lại nội dung dài rồi lọc ra quyết định và Action Items. AI phù hợp để hỗ trợ tóm tắt và trích xuất cấu trúc, nhưng vẫn có thể giữ human review để kiểm soát rủi ro.

**Vì sao không chọn các candidate còn lại:**  
- **Weekly Progress Report:** cũng có pain rõ nhưng scope rộng hơn vì phải gom dữ liệu từ nhiều nền tảng khác nhau.  
- **Technical Q&A:** bài toán tốt nhưng nằm ngoài context học tập/meeting mà cả nhóm đang có evidence trực tiếp.

---

## Phase 3.4 — Scoring

| Tiêu chí | Meeting & Action Items | Weekly Progress Report | Technical Q&A |
|---|:---:|:---:|:---:|
| Actor rõ | 5 | 5 | 5 |
| Workflow rõ | 5 | 5 | 4 |
| Pain có evidence | 5 | 4 | 4 |
| Impact đo được | 5 | 5 | 4 |
| Làm trong lab | 5 | 4 | 4 |
| So sánh R/W/A được | 4 | 5 | 4 |
| Nhóm hiểu domain | 5 | 5 | 3 |
| **Tổng** | **34/35** | **33/35** | **28/35** |

**Winner: Summarize Meeting & Action Items — 34/35 điểm.**

---

# Phase 4 — Quick Validation + Research

## Phase 4.1 — Quick Validation

### Source 1: Workshop AI In Action — 11/09/2026
- **Signal:** Nhóm phải xem/nghe lại record để tổng hợp nội dung cho các thành viên không tham dự đầy đủ.
- **Xác nhận:** Pain có thật và lặp lại sau các buổi workshop/họp dài.
- **Evidence:** Trong nhóm có nhu cầu hỏi lại “buổi sáng chốt cái gì” và cần người tổng hợp lại nội dung.

### Source 2: Nhóm chat Discord
- **Signal:** Nội dung thảo luận và quyết định bị trôi trong chat, thành viên phải hỏi lại.
- **Xác nhận:** Output sau cuộc họp chưa đủ tập trung để mọi người biết rõ quyết định và task.
- **Evidence:** Có nhiều tin nhắn hỏi lại nội dung/việc đã chốt sau buổi học.

### Source 3: Survey ngắn — 5 người trong nhóm
- **Signal:** 5/5 người xác nhận việc tổng hợp lại nội dung sau buổi họp/workshop là cần thiết và tốn thời gian.
- **Xác nhận:** Pain nhất quán giữa các thành viên.
- **Điều còn chưa chắc:** Mức độ chấp nhận của mọi người đối với Action Items do AI draft cần test trên 1–2 buổi họp thật.

### Insight sau validation

```text
Pain thật không nằm ở việc “ghi lại toàn bộ cuộc họp”, mà nằm ở đoạn biến transcript/notes dài và rời rạc thành quyết định + Action Items đủ rõ để mọi người biết ai làm gì và deadline khi nào.
```

---

## Phase 4.2 — Research giải pháp đã có

Nhóm tham khảo một số tool/pattern đã có để xem AI đang được dùng như thế nào trong bài toán tóm tắt và tổng hợp thông tin:

| Tool / case | Link | Họ giải quyết phần nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Slack AI | https://slack.com/help/articles/25076892548883-Guide-to-Slack-AI | Summary/search trong hội thoại | Tốt cho recap conversation | Chỉ xử lý nội dung trong Slack, không thay người xác nhận task cuối | AI summary nên là input cho người review |
| Gemini in Drive | https://support.google.com/drive/answer/15141241 | Tóm tắt nội dung file/tài liệu | Tốt cho summarization | Cần kiểm nguồn và không nên tự gửi output | AI draft, người thật review |
| Fellow AI Meeting Notes | https://fellow.ai/features/ai | Meeting notes, summary, action items | Gần với use case của nhóm | Action item vẫn có thể sai/ngầm hiểu nhầm context | Pattern phù hợp: AI draft + human confirmation |

### Research takeaway

```text
Nhóm không cần build một Agent tự vận hành toàn bộ meeting workflow. Hướng hợp lý hơn là một Workflow cố định: đưa transcript/notes vào → AI tóm tắt và trích Action Items → trưởng nhóm review → gửi cho nhóm.
```

---

# Phase 5 — Workflow + Problem Statement

## Phase 5.1 — Current Workflow

### Current state — 7 bước, khoảng 60 phút

```text
[1 Lấy record & note thô: 5']
→ [2 Nghe lại đoạn trọng tâm: 15']
→ [3 Gom & so sánh ý tưởng: 10']
→ [4 Tổng hợp vào Docs/Notion: 5']
→ [5 Viết narrative & Action Items: 20']  <-- bottleneck
→ [6 Review + format: 3']
→ [7 Gửi nhóm: 2']
```

| Bước | Actor | Input | Output | Thời gian | Ghi chú |
|---|---|---|---|---:|---|
| 1 | Trưởng nhóm | Record + note thô | Bộ input để xử lý | 5' | Manual |
| 2 | Trưởng nhóm | Record | Các đoạn quan trọng | 15' | Tốn thời gian |
| 3 | Trưởng nhóm | Ý kiến rời rạc | Nhóm ý tưởng | 10' | Cần hiểu context |
| 4 | Trưởng nhóm | Ý đã gom | Bản nháp | 5' | Manual |
| 5 | Trưởng nhóm | Bản nháp | Narrative + Action Items | 20' | **Bottleneck** |
| 6 | Trưởng nhóm | Bản nháp | Bản hoàn chỉnh | 3' | Human check |
| 7 | Trưởng nhóm | Bản hoàn chỉnh | Message gửi nhóm | 2' | Manual |

### Bottleneck

Bottleneck chính nằm ở **bước 5 — chuyển các ý kiến rời rạc thành narrative và Action Items rõ ràng**. Người tổng hợp phải xác định nội dung nào đã thực sự được chốt, ai phụ trách và deadline là khi nào, nên vừa tốn thời gian vừa dễ bỏ sót hoặc hiểu nhầm.

---

## Phase 5.2 — Future Workflow

### Future state — khoảng 13 phút

```text
[1 Upload transcript/note: 1' - người]
→ [2 AI phân loại ý tưởng: 1']
→ [3 AI draft narrative + Action Items: 1']
→ [4 Trưởng nhóm review + edit: 8']  <-- human boundary
→ [5 Gửi nhóm: 2']

Fallback:
Nếu AI trích xuất sai task, nhầm owner hoặc deadline → trưởng nhóm chỉnh tay trước khi gửi.
Nếu transcript thiếu hoặc chất lượng quá kém → quay lại record/note gốc và dùng AI draft như checklist tham khảo.
```

### Before / After

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Tổng thời gian | 60 phút | ~13 phút | Bấm giờ 1–2 buổi họp thật |
| Số bước | 7 | 5 | So workflow |
| Bước thủ công chính | 7/7 | 2/5 | Upload + review/gửi |
| Bottleneck | Viết narrative & Action Items | Review/edit | Bấm giờ bước lâu nhất |
| Risk mới | Bỏ sót khi làm tay | AI hallucination / nhầm owner/deadline | Đếm lỗi phải sửa |

---

## Phase 5.3 — Problem Statement v0

| Field | Nội dung |
|---|---|
| **Actor** | Trưởng nhóm hoặc người phụ trách tổng hợp biên bản sau buổi họp/workshop. |
| **Workflow** | Lấy record/note → nghe lại → gom ý → tổng hợp → viết narrative & Action Items → review → gửi nhóm. |
| **Bottleneck** | Chuyển các ý kiến rời rạc thành quyết định và Action Items rõ người phụ trách/deadline. |
| **Impact** | Mất khoảng 30–60 phút sau mỗi buổi họp; dễ bỏ sót task hoặc khiến thành viên phải hỏi lại. |
| **Success Metric** | Giảm tổng thời gian xuống dưới 15 phút; giảm số lần thành viên phải hỏi lại về task/deadline. |
| **Boundary** | AI chỉ draft summary/Action Items; không tự gửi và không tự quyết định task cuối cùng. Trưởng nhóm phải review trước khi gửi. |

---

# Phase 6 — Rule / Workflow / Agent + Decision

## Phase 6.0 — Ma trận độ phù hợp

- **Độ mơ hồ:** Cao — cùng một ý có thể được nói theo nhiều cách; owner/deadline đôi khi không được nói theo format cố định.
- **Độ phức tạp:** Trung bình — workflow có nhiều bước nhưng đi theo một pipeline tương đối cố định.

**Kết luận:** Bài toán phù hợp nhất với **Workflow có AI + human-in-the-loop**, chưa cần Agent tự lập kế hoạch động.

---

## Phase 6.1 — So sánh Rule / Workflow / Agent

| Mức | Phương án | Khi nào đủ | Rủi ro | Chọn? |
|---|---|---|---|---|
| **Rule** | Template meeting note + field cố định Task/Owner/Deadline | Đủ nếu mọi người nói và ghi chép theo format chuẩn | Không hiểu được ngôn ngữ tự do, dễ bỏ sót ý implicit | Dùng hỗ trợ format |
| **Workflow** | Transcript/notes → AI phân loại → AI draft summary/Action Items → trưởng nhóm review → gửi | Phù hợp với flow tuyến tính và có human review | AI có thể nhầm task/owner/deadline | **Chọn** |
| **Agent** | AI tự lấy record, tự phân tích, tự tạo task và tự gửi | Chỉ cần nếu phải tự quyết nhiều bước/tool động | Scope rộng, permission/risk cao | Chưa cần |

### 5 câu hỏi chốt

1. **Rule có giải được 70–80% case không?**  
   Không. Rule/template giúp format nhưng không đủ để hiểu thảo luận tự do.

2. **Các bước có đi thẳng một đường không hay phải rẽ nhánh?**  
   Chủ yếu đi thẳng: input → summary/extraction → review → gửi.

3. **Có thật sự cần Agent tự lập kế hoạch + gọi tool không?**  
   Chưa cần.

4. **Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu?**  
   Trưởng nhóm phát hiện ở bước review và chỉnh trực tiếp trước khi gửi.

5. **Có hạ được từ Agent → Workflow → Rule không?**  
   Có. Workflow là mức hợp lý nhất; Rule chỉ dùng hỗ trợ cấu trúc.

### Mức chọn

```text
Workflow
```

### Vì sao chọn

AI chỉ cần hỗ trợ một số bước ngôn ngữ cụ thể: tóm tắt, phân loại và trích Action Items. Workflow có đường đi cố định nên chưa cần Agent tự lập kế hoạch. Human review giữ lại quyền quyết định cuối cùng và giảm rủi ro hallucination.

---

## Phase 6.2 — Problem Statement v1

| Field | Nội dung |
|---|---|
| **Actor** | Trưởng nhóm/người phụ trách biên bản trong nhóm sinh viên hoặc workshop. |
| **Workflow** | Record/note → nghe/đọc lại → gom ý → tổng hợp → viết narrative & Action Items → review → gửi. |
| **Bottleneck** | Chuyển nội dung dài và rời rạc thành quyết định + Action Items rõ ràng. |
| **Impact** | Khoảng 30–60 phút/buổi; thành viên có thể phải hỏi lại hoặc bỏ sót task/deadline. |
| **Success Metric** | Giảm tổng thời gian xuống <15 phút/buổi; hướng tới 0 trường hợp phải hỏi lại task/deadline do biên bản thiếu thông tin. |
| **Boundary** | AI không tự gửi, không tự quyết định task cuối, không tự bịa owner/deadline nếu cuộc họp chưa chốt. |
| **AI intervention point** | Sau khi có transcript/notes và trước bước viết summary + Action Items. |
| **Mức chọn** | Workflow — vì flow tuyến tính, AI chỉ xử lý các bước ngôn ngữ và người thật review. |
| **Rủi ro & người thật kiểm tra** | Rủi ro lớn nhất là AI hiểu sai task/owner/deadline. Trưởng nhóm kiểm lại với transcript/notes trước khi gửi. |

---

## Phase 6.3 — Final Decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú |
|---|---|---|
| Actor + workflow rõ chưa? | Yes | Actor là trưởng nhóm/người tổng hợp; workflow sau họp có thể mô tả rõ từng bước |
| Baseline + metric đo được chưa? | Yes | Baseline 30–60 phút/buổi; target <15 phút |
| Data/input đủ dùng chưa? | Yes | Có record, transcript, chat hoặc note thô |
| AI sai, hậu quả chấp nhận được không? | Yes | Có human review trước khi gửi |
| Có người review/owner không? | Yes | Trưởng nhóm/người phụ trách biên bản |
| Có cách non-AI đơn giản hơn không? | Yes | Template meeting note + yêu cầu thành viên tự ghi task, nhưng chưa giải tốt phần tổng hợp nội dung dài |

### Decision

```text
GO với scope nhỏ
```

### Lý do

Problem có actor, workflow và bottleneck rõ. Nhóm có baseline thời gian và success metric cụ thể. AI can thiệp đúng vào bước tóm tắt/trích xuất, trong khi người thật vẫn giữ quyền review và gửi. Rủi ro chính có fallback rõ nên đủ an toàn để thử prototype.

### Pilot nhỏ nhất

```text
- Dùng transcript/notes của 1–2 buổi họp thật.
- Cho AI tạo:
  1. Meeting Summary
  2. Decisions
  3. Action Items
  4. Owner
  5. Deadline
- Trưởng nhóm review và chỉnh trước khi gửi.
- Đo 3 số:
  1. Tổng thời gian từ transcript → bản gửi cuối.
  2. Số Action Items AI bỏ sót / trích sai.
  3. Thời gian trưởng nhóm phải edit output.
```

### Exit / rollback

```text
Nếu AI thường xuyên nhầm owner/deadline, bỏ sót quyết định quan trọng hoặc trưởng nhóm phải viết lại phần lớn output trong 2 buổi liên tiếp, quay về template meeting note + nhập Action Items thủ công.
```

---

## Self-check

- [x] Có nhật ký hội tụ từ 15 candidates về 1 bài
- [x] Có cluster + shortlist + scoring
- [x] Có validation và research
- [x] Có workflow before/after, bottleneck, human boundary và fallback
- [x] Có Problem Statement v0 → v1
- [x] Có so sánh Rule / Workflow / Agent
- [x] Có Decision GO + pilot nhỏ nhất + exit/rollback
