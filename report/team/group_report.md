# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: DULU
- Thành viên: Nguyễn Mạnh Hùng, Vương Quang Thắng, Ngô Duy Khánh, Lê Sỹ Long Nhật; cần đối chiếu lại với `TEAM.md`
- Candidate problem được chọn (1 câu): Khi chuẩn bị nộp bài lab GitHub theo nhóm, thành viên mất khoảng 30 phút để kiểm tra đủ file, đúng cấu trúc, đúng link và đủ nội dung trong repository.
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện ghi nhận / cần xác nhận |
|---:|---|---|---|---|---|
| 1 | Nguyễn Mạnh Hùng | Khi so sánh các gói vay trả góp cho VF5, tôi muốn xem lịch trả nợ chi tiết để biết dòng tiền cần chuẩn bị. | Người mua / sales showroom | Tính và đối chiếu lịch trả nợ theo từng tháng. | Câu hỏi cần xác nhận: khách hàng cần so sánh nhiều gói vay hay chỉ cần một vài con số chính? |
| 2 | Nguyễn Mạnh Hùng | Khi có nhiều comment review app VinFast, tôi muốn phân loại chúng theo nhóm lỗi để báo cáo cho Product team/CSKH. | Product team / CSKH | Đọc và gán nhãn comment thủ công. | Câu hỏi cần xác nhận: việc phân loại sai hoặc bỏ sót ảnh hưởng thế nào đến ưu tiên xử lý? |
| 3 | Nguyễn Mạnh Hùng | Khi nhận mã lỗi ADAS, tôi muốn xác định nguyên nhân phần cứng hay phần mềm để chọn hướng xử lý phù hợp. | Kỹ thuật viên xưởng | Tra manual và đối chiếu phiên bản phần mềm. | Câu hỏi cần xác nhận: có thể thu hẹp candidate vào một nhóm mã lỗi cụ thể không? |
| 4 | Vương Quang Thắng | Khi đóng form workshop, tôi muốn gom nhóm kỳ vọng và câu hỏi của người tham gia để điều chỉnh nội dung sự kiện. | Ban Truyền thông / Nội dung | Đọc và gắn tag thủ công cho 150–200 form. | Câu hỏi cần xác nhận: insight cần sâu đến mức nào để thực sự thay đổi kịch bản? |
| 5 | Vương Quang Thắng | Khi có bài thông báo gốc, tôi muốn chuyển thành nội dung phù hợp cho Facebook, Instagram và email. | Content writer | Viết lại và đổi giọng văn cho từng nền tảng. | Câu hỏi cần xác nhận: chất lượng và độ hấp dẫn của các phiên bản sẽ được đo bằng metric nào? |
| 6 | Vương Quang Thắng | Khi sự kiện sắp diễn ra, tôi muốn đăng nội dung lên nhiều group sinh viên để tăng độ phủ. | Ban Truyền thông | Copy, chỉnh format và hashtag theo từng group. | Câu hỏi cần xác nhận: luật của group thay đổi có làm candidate vượt quá phạm vi lab không? |
| 7 | Ngô Duy Khánh | Khi nhận góp ý cho báo cáo từ nhiều nguồn, tôi muốn biết từng góp ý cần sửa ở đoạn nào để tránh bỏ sót. | Người tổng hợp báo cáo | Đối chiếu góp ý với đúng mục cần sửa. | Câu hỏi cần xác nhận: bottleneck nằm ở nhiều nguồn góp ý hay ở việc góp ý không chỉ rõ vị trí? |
| 8 | Ngô Duy Khánh | Khi các thành viên gửi phần riêng, tôi muốn ghép thành một bản Markdown chung có cấu trúc và link đúng. | Người phụ trách ghép báo cáo | Chỉnh cấu trúc, bảng và đường dẫn. | Câu hỏi cần xác nhận: thời gian chủ yếu nằm ở định dạng/link hay ở việc chờ các phần hoàn tất? |
| 9 | Ngô Duy Khánh | Khi sửa báo cáo sau họp, tôi muốn tìm lại quyết định cuối cùng và lý do chọn để không dùng phương án đã bị loại. | Thành viên sửa báo cáo | Đọc ngữ cảnh để phân biệt quyết định cuối với đề xuất bị loại. | Câu hỏi cần xác nhận: nhóm có thường ghi rõ quyết định cuối sau mỗi cuộc họp không? |
| 10 | Lê Sỹ Long Nhật | Khi chuẩn bị nộp bài lab GitHub theo nhóm, tôi muốn kiểm tra đủ file và yêu cầu trong repository để tránh sai cấu trúc hoặc bỏ sót deliverable. | Thành viên phụ trách hoàn thiện bài | Đối chiếu README, rubric, submission guide và repository. | Câu hỏi đã nêu trong card: bottleneck nằm ở đọc tài liệu, kiểm tra cấu trúc hay đối chiếu nội dung với rubric? |
| 11 | Lê Sỹ Long Nhật | Khi bắt đầu assignment, tôi muốn gom yêu cầu từ README, rubric và worksheet thành checklist để biết cần hoàn thành gì. | Thành viên bắt đầu assignment | Tổng hợp yêu cầu trùng lặp từ nhiều tài liệu. | Câu hỏi cần xác nhận: thời gian tạo checklist có đủ lớn để trở thành problem độc lập không? |
| 12 | Lê Sỹ Long Nhật | Khi rà soát trước deadline, tôi muốn phát hiện mục còn trống theo rubric để có thời gian bổ sung. | Thành viên review bài | Đối chiếu từng mục report với rubric. | Câu hỏi cần xác nhận: số mục bị bỏ sót có thể đo được qua các assignment trước không? |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A — Kiểm tra và phối hợp deliverable | Khánh #1, #2; Nhật #1, #2, #3 | Gom, đối chiếu và kiểm tra nhiều phần trước khi báo cáo hoặc nộp bài |
| B — Tìm kiếm và chẩn đoán thông tin | Hùng #1, #3; Khánh #3 | Tìm và đối chiếu nhiều nguồn để đưa ra thông tin hoặc quyết định đúng |
| C — Phân loại và chuyển đổi nội dung | Hùng #2; Thắng #1, #2, #3 | Xử lý nhiều đầu vào văn bản, gắn nhãn hoặc chuyển đổi theo mục đích |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Giảm thời gian và lỗi khi hoàn thiện deliverable của nhóm
├── Opportunity A: Thành viên phải gom và đối chiếu thông tin từ nhiều nguồn rời rạc
├── Opportunity B: Một bước xử lý thủ công lặp lại chiếm phần lớn thời gian
└── Opportunity C: Khó kiểm tra đầu ra có đủ, đúng cấu trúc và đúng yêu cầu hay chưa
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

- Các công cụ hoặc tính năng cụ thể như chatbot, AI tự động đăng bài, dashboard hoặc hệ thống tự gửi báo cáo; đây là solution, chưa phải opportunity.

### 2.4. Chấm điểm shortlist (1–5)

> Điểm dưới đây là điểm sơ bộ được tổng hợp từ evidence trong bốn báo cáo cá nhân; nhóm cần xác nhận lại trong buổi pitch trước khi coi là điểm chính thức.

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Kiểm tra đủ file và yêu cầu trong repository trước khi nộp | 5 | 5 | 3 | 4 | 5 | 5 | 5 | **32** |
| Gom và phân loại góp ý cho báo cáo từ nhiều nguồn | 4 | 4 | 2 | 4 | 5 | 5 | 4 | **28** |
| Phân loại kỳ vọng và câu hỏi từ form đăng ký workshop | 4 | 5 | 4 | 4 | 4 | 5 | 4 | **30** |

**Candidate được chọn:** Kiểm tra đủ file và yêu cầu trong repository trước khi nộp bài lab GitHub.

**Vì sao chọn:** Candidate có actor rõ, quy trình cụ thể, baseline khoảng 30 phút/bài, phạm vi vừa sức lab và có thể bắt đầu bằng `No AI/Rule`. Đây cũng là candidate có evidence trực tiếp rõ nhất trong các báo cáo hiện có.

**Vì sao loại các candidate còn lại:** Candidate gom góp ý có evidence còn ở dạng minh họa và phạm vi phụ thuộc nhiều vào cách nhóm ghi chú. Candidate phân loại form có process rõ nhưng cần kiểm chứng thêm về chất lượng insight và mức độ ảnh hưởng tới quyết định sự kiện. Hai candidate này vẫn có thể được xem xét lại nếu CP4 cung cấp evidence mạnh hơn.

**Xử lý bất đồng (nếu có):** Bản hiện tại dùng điểm số sơ bộ từ các báo cáo cá nhân. Nhóm cần xác nhận lại điểm, câu hỏi phản biện và candidate được chọn trong buổi pitch; nếu có bất đồng, ưu tiên candidate có evidence hành vi rõ hơn và phạm vi kiểm chứng được trong lab.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |

*Điền 4–6 giả định; xóa dòng thừa.*

Giả định nhóm kiểm chứng trong buổi này:

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey / Log, ticket, review

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | |
| Câu nói đáng nhớ nhất (nguyên văn) | |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | |
| Hiện đang xử lý bằng cách nào (workaround)? | |
| Mất bao lâu, bao lần? | |
| Insight / opportunity rút ra | |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| | | | |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |
| | | | | | |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |

**Bottleneck chính:**

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text

```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | | | |
| Tổng thời gian | | | |
| Số bước thủ công | | | |
| Bottleneck chính | | | |
| Rủi ro mới phát sinh | | | |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

-

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô:

Vì sao:

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | | | | |
| **Rule** | | | | |
| **Workflow** | | | | |
| **Agent** | | | | |

**Mức chọn:**

**Vì sao không chọn mức đơn giản hơn:**

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | |
| **Judgment** — con người cân nhắc, quyết định gì? | |
| **Action** — hành động cuối cùng là gì, ai làm? | |
| **Outcome** — đo kết quả bằng gì? | |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** | |
| **AI intervention point** | |
| **Mức chọn** | No AI / Rule / Workflow / Agent |
| **Rủi ro & người kiểm tra** | |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| | | | |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | | |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | | |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | | |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | | |

### 8.2. Kết luận

**Quyết định:** Go / Not Yet / No-Go

**Lý do:**

**Nếu Go — pilot nhỏ nhất:**

**Nếu Not Yet — cần kiểm chứng gì trước:**

**Nếu No-Go — nên làm gì thay AI:**

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

---

## 9. Hạn chế và hướng tiếp theo

-

## 10. Tài liệu tham khảo

-
