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
| 1 | Thành viên phụ trách nộp bài ở nhóm khác cũng phải rà soát repository lặp lại và mất thời gian đáng kể. | Value | 5 | 1 | Ưu tiên 1: hỏi 2–3 người ngoài nhóm về lần nộp gần nhất. |
| 2 | Khoảng 30 phút/bài là thời gian rà soát thực tế, tách được khỏi thời gian viết bài, chờ thành viên và sửa nội dung. | Value | 5 | 2 | Ưu tiên 1: dựng lại lần gần nhất và bấm giờ một lượt review. |
| 3 | Đối chiếu yêu cầu với file/mục trong báo cáo là bước mất nhiều thời gian nhất, thay vì kiểm tra link hoặc chờ bàn giao. | Value | 5 | 1 | Ưu tiên 1: ghi thời gian từng bước, không suy từ tổng 30 phút. |
| 4 | Các yêu cầu về file, tên thư mục và liên kết có thể chuyển thành checklist hoặc kiểm tra xác định; chất lượng lập luận vẫn cần người đọc. | Feasibility | 4 | 3 | Ưu tiên 2: đối chiếu SUBMISSION.md, rubric và khả năng của công cụ hiện có. |
| 5 | Người review có thể truy ngược mỗi cảnh báo tới yêu cầu và vị trí cần sửa, không tốn thêm nhiều công kiểm tra lại. | Usability | 4 | 1 | Ưu tiên 2: quan sát người ngoài nhóm dùng checklist trên repository của họ. |
| 6 | Quy trình rà soát phù hợp quy định môn học và quyền truy cập repository, không đòi chia sẻ thông tin đăng nhập hoặc tự nộp bài. | Viability | 4 | 2 | Ưu tiên 2: đọc RULES.md, xác nhận quyền truy cập và người chịu trách nhiệm review. |

Thang điểm: **quan trọng** 5 = nếu sai phải xem lại candidate; **bằng chứng** 1 = chưa có dữ liệu trực tiếp, 2 = tự báo cáo đơn lẻ/tài liệu nội bộ, 3 = có tài liệu đối chiếu nhưng chưa thử với người dùng, 4–5 = có quan sát hoặc đo lặp lại. Điểm là đánh giá sơ bộ, không phải kết quả khảo sát.

Phân ô hai trục: cả 6 giả định đều quan trọng cao (4–5); #1, #2, #3, #5, #6 thuộc ô ít bằng chứng (1–2), #4 có bằng chứng tài liệu ở mức trung bình (3). Chưa có giả định nào thuộc ô bằng chứng mạnh (4–5). **Kiểm chứng #1–#3 trước** vì quyết định pain có phổ biến, baseline có đúng và bottleneck nằm ở đâu.

### 3.2. Kiểm chứng

Cách đã dùng: đọc bằng chứng có sẵn trong báo cáo cá nhân và đối chiếu tài liệu repository. **Chưa có phỏng vấn/survey ngoài nhóm; phần kiểm chứng người dùng của CP4 chưa hoàn tất.** Các báo cáo thành viên là nguồn hình thành giả thuyết, không thay thế phỏng vấn 2–3 người ngoài nhóm hoặc survey 5–10 người theo yêu cầu.

**Bằng chứng hiện có:** [báo cáo cá nhân đề xuất candidate, mục 2 và Problem Card #1](../individual/2A202603881_LeSyLongNhat.md) ghi khoảng 30 phút/bài và gần như mỗi assignment. Đây là tự báo cáo của một thành viên; chưa có ngày của lần nộp cụ thể, log bấm giờ, số lỗi hay số liệu từ người ngoài nhóm. Không diễn giải thành “mọi nhóm đều mất 30 phút” hoặc “bước đối chiếu riêng mất 30 phút”.

**Kế hoạch phỏng vấn nhanh (chưa thực hiện):** chọn 2–3 sinh viên thuộc nhóm khác đã trực tiếp review/nộp một bài lab GitHub gần đây. Mỗi người khoảng 5 phút; xin xem checklist hoặc file liên quan nếu họ đồng ý, ghi vai trò và thời điểm, không ghi thông tin nhận dạng.

1. Lần gần nhất bạn kiểm tra repository trước khi nộp là khi nào? Bạn phụ trách phần nào?
2. Kể lại từng bước từ lúc bắt đầu rà soát đến lúc nộp; bạn đã mở những tài liệu nào?
3. Mỗi bước mất khoảng bao lâu? Khoảng nào là chờ người khác, viết bổ sung hoặc sửa bài?
4. Lần đó bạn phát hiện thiếu/sai mục nào? Bạn phát hiện bằng cách nào và đã xử lý ra sao?
5. Lần đó bạn dùng checklist, script hay cách kiểm tra nào khác? Cho một ví dụ nó giúp được hoặc bỏ sót điều gì.
6. Kể một lần việc kiểm tra diễn ra nhanh, không gặp khó khăn; điều gì khác so với lần mất nhiều thời gian?

**Snapshot tham khảo cho TH1 — giả lập, không phải buổi phỏng vấn thật.** Bảng dưới minh họa cách điền; khi phỏng vấn thực tế, thay bằng dữ liệu có nguồn và tạo bảng riêng cho từng người.

| Trường | Nội dung tham khảo — tình huống giả lập TH1 |
|---|---|
| Mã người được hỏi / vai trò / nhóm khác | TH1 là mã tình huống; vai trò giả định: sinh viên phụ trách tổng hợp và review bài lab GitHub của một nhóm khác. Không đại diện cho người thật. |
| Ngày giờ / cách hỏi / người phỏng vấn | Không có buổi phỏng vấn diễn ra. AI tạo kịch bản tham khảo theo bộ câu hỏi phía trên; không có ngày giờ hoặc người phỏng vấn thực tế. |
| Câu nói đáng nhớ nhất (nguyên văn) | Không có trích dẫn thật. Ý chính của kịch bản: kiểm tra đủ file tương đối dễ, nhưng phải mở nhiều tài liệu để biết từng mục đã đáp ứng yêu cầu hay chưa. Đây là diễn giải minh họa, không phải lời người được hỏi. |
| Lần gần nhất gặp vấn đề: bối cảnh, các bước, lỗi cụ thể | Trong kịch bản, sau khi ghép các phần báo cáo, người review đọc lại yêu cầu, kiểm tra cấu trúc, đối chiếu từng mục rồi mở link. Phát hiện một mục bắt buộc chưa có nội dung và một link ảnh sai đường dẫn. Không có assignment thật được quan sát. |
| Workaround và bằng chứng được cho xem | Cách xử lý giả định: mở README, rubric, submission guide song song với báo cáo và ghi các mục cần sửa. Không có file, ảnh chụp hay log được người dùng cung cấp; tài liệu trong repository chỉ là bối cảnh xây dựng kịch bản. |
| Thời gian từng bước / tần suất / cách ước lượng hoặc đo | Số phút giả định: đọc yêu cầu 5 + kiểm tra file/cấu trúc 5 + đối chiếu nội dung 15 + kiểm tra link 5 = 30 phút/lượt. Không tính chờ bàn giao hoặc sửa bài. Tần suất chưa xác định; đây là số liệu đặt cho ví dụ, không được bấm giờ hay thu từ người dùng. |
| Tín hiệu phản bác / điều trái giả định | Trong TH1, đối chiếu nội dung chỉ chiếm 15/30 phút, nên không thể coi toàn bộ 30 phút là bottleneck này. TH3 ở phần dưới còn minh họa khả năng checklist có mapping đã giúp review nhanh; đây đều là phản ví dụ giả lập cần kiểm tra với người thật. |
| Insight / giả định nào được xác nhận hoặc bác bỏ | Insight tham khảo: nên gắn yêu cầu với file/mục và tách kiểm tra cấu trúc khỏi đánh giá nội dung. Kịch bản gợi cách kiểm tra giả định #2–#3 nhưng không xác nhận hoặc bác bỏ bất kỳ giả định nào bằng bằng chứng thực tế. |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Báo cáo cá nhân đề xuất candidate | 1 thành viên; số assignment chưa được ghi cụ thể | Tự báo cáo khoảng 30 phút/bài, gần như mỗi assignment. | Chưa tách thời gian từng bước; chưa chứng minh đối chiếu yêu cầu là bottleneck chính. |
| SUBMISSION.md trong repository | 1 tài liệu | Có checklist trước khi nộp và cấu trúc file bắt buộc để đối chiếu. | **Tín hiệu phản bác từ tài liệu:** đã có checklist; giả định “thiếu checklist nên review chậm” chưa đứng vững. Cần hỏi vì sao cách hiện có chưa đủ. |
| Phỏng vấn ngoài nhóm | 0 người | Chưa có. | Chưa có dữ liệu hành vi để biết người khác có gặp pain hoặc review nhanh hơn đáng kể. |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

Sau đối chiếu nguồn hiện có, đề xuất thu hẹp candidate thành: **Khi rà soát bài lab GitHub theo nhóm trước lúc nộp, người phụ trách phải đối chiếu yêu cầu trong tài liệu với file và các mục báo cáo để tìm phần còn thiếu hoặc sai; chưa rõ bước nào chiếm nhiều thời gian nhất.** Mốc khoảng 30 phút chỉ mô tả trải nghiệm ban đầu của một thành viên và toàn bộ lượt review. Chưa kết luận đây là pain phổ biến, chưa quy nguyên nhân cho việc thiếu công cụ và chưa chọn mức can thiệp AI.

Điều kiện cập nhật sau phỏng vấn: nếu ít nhất 2 người ngoài nhóm kể được lần review cụ thể có công đối chiếu đáng kể, tiếp tục đo từng bước; nếu phần lớn thời gian là chờ bàn giao/viết bổ sung thì chuyển trọng tâm sang phối hợp hoàn thiện bài; nếu checklist hiện có đã giúp review nhanh và ít lỗi thì xem lại mức độ đáng giải của candidate. Đây là quy tắc đọc kết quả dự kiến, không phải kết quả đã xảy ra.

#### Kết quả tham khảo — tình huống giả lập

> **Toàn bộ dữ liệu dưới đây do AI tạo để minh họa cách tổng hợp CP4 theo yêu cầu tham khảo. Không có người tham gia thật, không có buổi phỏng vấn hay phép đo đã diễn ra. Không dùng phần này làm bằng chứng kiểm chứng hoặc kết quả phỏng vấn khi nộp bài.** Các mã TH1–TH3 là tình huống giả lập, không phải mã người được hỏi. Không tạo câu trích dẫn nguyên văn vì không có lời nói thật.

| Trường | TH1 — Người tổng hợp bài (giả lập) | TH2 — Người review cuối (giả lập) | TH3 — Nhóm đã có checklist (giả lập) |
|---|---|---|---|
| Bối cảnh minh họa | Các thành viên đã ghép báo cáo, người tổng hợp bắt đầu kiểm tra trước khi nộp. | Nhiều phần báo cáo được cập nhật riêng, người review đối chiếu bản cuối với đề. | Nhóm dùng checklist có sẵn, mỗi yêu cầu đã gắn với một file/mục và người phụ trách. |
| Cách xử lý trong kịch bản | Mở README, rubric và submission guide rồi dò lần lượt trong repository. | Đọc rubric theo từng tiêu chí, mở file tương ứng, ghi mục cần bổ sung. | Đi theo checklist, mở vị trí đã ghi và kiểm tra trạng thái thực tế. |
| Thời gian giả định, chỉ tính rà soát | 30 phút: đọc lại yêu cầu 5, kiểm tra file/cấu trúc 5, đối chiếu nội dung 15, kiểm tra link 5. | 25 phút: đọc lại yêu cầu 4, kiểm tra file/cấu trúc 4, đối chiếu nội dung 13, kiểm tra link 4. | 10 phút: đọc lại yêu cầu 1, kiểm tra file/cấu trúc 2, đối chiếu nội dung 5, kiểm tra link 2. |
| Vấn đề giả định phát hiện | Một mục bắt buộc chưa có nội dung và một link ảnh sai đường dẫn. | Một trường metric chưa có baseline và một mục còn nguyên template. | Không phát hiện thiếu file hoặc mục bắt buộc trong lượt kiểm tra minh họa. |
| Phạm vi số phút | Không gồm thời gian sửa lỗi, chờ thành viên hoặc viết bổ sung. | Không gồm thời gian sửa lỗi, chờ thành viên hoặc viết bổ sung. | Không gồm thời gian tạo và duy trì checklist từ đầu assignment. |
| Insight minh họa | Có đủ file chưa đồng nghĩa đủ nội dung; cần chỉ rõ yêu cầu nằm ở đâu. | Mục có chữ vẫn có thể chưa đáp ứng rubric, cần người đọc đánh giá. | Checklist có mapping rõ có thể đã đủ cho một số nhóm; cần kiểm tra phương án đơn giản trước. |

**Ví dụ tổng hợp nếu thu được dữ liệu thật tương tự:**

- Hai tình huống chưa có mapping yêu cầu → vị trí nội dung mất 25–30 phút; tình huống đã có mapping mất 10 phút. Đây chỉ là sự khác nhau được đặt trong kịch bản, chưa chứng minh checklist gây ra mức giảm thời gian đó.
- Bước đối chiếu nội dung chiếm 15/30, 13/25 và 5/10 phút trong ba tình huống, nên là ứng viên bottleneck cần đo thực tế. Không cộng thời gian sửa bài vào thời gian review.
- Tín hiệu phản bác minh họa: TH3 review nhanh với cách làm hiện có. Vì vậy không thể kết luận mọi nhóm đều cần công cụ mới hoặc đều mất khoảng 30 phút.
- Giả định #1 chỉ được hỗ trợ nếu người ngoài nhóm thật sự kể lại hành vi tương tự TH1–TH2; #2 cần đổi từ một mốc 30 phút sang thời gian theo từng trường hợp; #3 cần log từng bước. #4–#6 vẫn cần kiểm tra riêng, không được xác nhận chỉ từ ba kịch bản.

**Candidate điều chỉnh tham khảo theo kịch bản:** Khi hoàn thiện bài lab GitHub theo nhóm, người phụ trách review ở nhóm chưa có bảng đối chiếu yêu cầu với vị trí nội dung phải dò qua nhiều tài liệu và file để phát hiện mục còn thiếu hoặc chưa đáp ứng rubric, làm lượt rà soát kéo dài. Phạm vi ưu tiên là công đối chiếu trước khi nộp; tách khỏi việc chờ bàn giao và sửa nội dung.

**Bước kiểm tra tiếp theo trong ví dụ:** cho người review thử checklist có các cột yêu cầu, nguồn, file/mục, trạng thái và người xác nhận; ghi cả thời gian tạo checklist lẫn thời gian review, số mục bỏ sót và cảnh báo nhầm. So sánh với cách làm hiện tại trên bài có mức độ tương đương trước khi đặt target hoặc chọn mức can thiệp.

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Checklist Markdown trong GitHub Issue | [GitHub Docs — About tasklists](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/about-tasklists) | Chia yêu cầu thành các việc và đánh dấu hoàn tất khi review. | Checkbox Markdown giúp theo dõi trạng thái. | Người review vẫn phải chuyển yêu cầu thành checklist và tự xác nhận nội dung; tích ô không chứng minh bài đạt rubric. | Tận dụng checklist có sẵn trong SUBMISSION.md, thêm vị trí file/mục và người kiểm tra. |
| Markdownlint (Ruby, lệnh mdl) | [Repository chính thức](https://github.com/markdownlint/markdownlint) | Rà soát quy tắc trình bày Markdown trong file/thư mục; báo lỗi kèm dòng. | Có rule và cấu hình style để kiểm tra nhất quán. | Phạm vi là style Markdown; không xác nhận đủ deliverable hoặc lập luận đạt rubric. | Tách lỗi định dạng khỏi đánh giá chất lượng nội dung, chỉ bật rule phù hợp bài lab. |
| Lychee | [Repository chính thức](https://github.com/lycheeverse/lychee) | Kiểm tra liên kết trong Markdown/HTML và hỗ trợ rà soát link trước khi nộp. | Có CLI và cách tích hợp GitHub Actions. | Link truy cập được chưa chắc trỏ đúng tài liệu cần nộp; cần người xác nhận ngữ cảnh và quyền xem của người chấm. | Dùng kiểm tra link như một phần của lượt review; giữ bước mở và đối chiếu nội dung đích. |

**Kiểm tra nguồn:** đã mở và đọc 3 nguồn chính thức trên ngày 09/11/2026. GitHub Docs phân biệt checkbox Markdown với tính năng tasklist blocks đã ngừng; đề xuất ở đây dùng checkbox Markdown thông thường. Các khoảng trống và bài học là nhận định của nhóm từ phạm vi công cụ, chưa phải kết quả pilot. Chưa cài/chạy các công cụ trên repository và chưa có số liệu chứng minh tiết kiệm thời gian.

**Kết luận research:** đã có cách theo dõi checklist, kiểm tra style và kiểm tra link. Khoảng cần kiểm chứng tiếp là công đối chiếu yêu cầu với vị trí nội dung và việc người review vẫn bỏ sót dù đã có checklist. Research hỗ trợ giả định #4 về tính khả thi, chưa xác nhận #1–#3 về nhu cầu và bottleneck.

**Việc còn thiếu để chốt CP4:** thực hiện 2–3 phỏng vấn ngoài nhóm (hoặc survey 5–10 người), điền dữ liệu thật kèm thời điểm/cách hỏi, ghi tín hiệu phản bác từ người dùng và cập nhật lại assumption map cùng candidate theo kết quả.

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text
HIỆN TẠI — 5 bước, khoảng 30 phút, 5/5 bước thủ công

[1 Mở và đọc rubric, submission guide: 5']
-> [2 Dò từng tên file/thư mục trong repo: 5']
-> [3 Đọc và đối chiếu nội dung với rubric: 15'] <- BOTTLENECK
-> [4 Click test từng link/hình ảnh: 3']
-> [5 Review lần cuối và commit/nộp bài: 2']
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Người phụ trách review | Rubric, submission guide, README | Hiểu rõ checklist và mục tiêu rà soát | 5 phút / lần nộp | Phải mở nhiều tab hoặc màn hình song song |
| 2 | Người phụ trách review | Cấu trúc file/folder trong repo hiện tại | Danh sách file/folder thiếu hoặc sai tên | 5 phút / lần nộp | Dò bằng mắt thủ công đối chiếu với template |
| 3 | Người phụ trách review | Nội dung file Markdown và file code | Danh sách mục còn thiếu hoặc chưa đạt rubic | 15 phút / lần nộp | Đọc hiểu cả nội dung thành viên khác để đánh giá mức độ đạt yêu cầu |
| 4 | Người phụ trách review | File Markdown có link/hình ảnh | Danh sách link chết, ảnh lỗi hiển thị | 3 phút / lần nộp | Rất dễ bị sót nếu bài dài |
| 5 | Người phụ trách review | Báo cáo lỗi / repo đã sửa | Bài hoàn thiện được push và nộp lên hệ thống | 2 phút / lần nộp | Chốt repo cuối cùng và báo cho cả nhóm |

**Bottleneck chính:**

Bước 3 - Đọc và đối chiếu nội dung từng mục với Rubric (15 phút). Đây là khâu tốn não và tốn thời gian nhất vì người review phải đối chiếu chéo liên tục giữa nhiều tài liệu (Rubric vs bài làm thực tế), dễ sinh ra mệt mỏi và bỏ sót lỗi nếu bài quá dài.

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text
TƯƠNG LAI — 5 bước, khoảng 15 phút, 3/5 bước thủ công

[1 Chạy script kiểm tra cấu trúc file và test link chết: 1'] <- RULE (script)
-> [2 AI đối chiếu nội dung file với Rubric để xuất report: 1'] <- AI
-> [3 SV đọc report, đối chiếu và sửa lại nội dung file: 10'] <- CON NGƯỜI (bottleneck kiểm soát)
-> [4 Script tự động quét lại lần cuối: 1'] <- RULE
-> [5 Sinh viên tự commit và nộp bài: 2'] <- CON NGƯỜI
```

**Boundary:** AI chỉ quét và xuất file report cảnh báo lỗi/thiếu sót. KHÔNG được tự động sinh nội dung bổ sung vào bài, KHÔNG tự sửa code, KHÔNG tự động push hay trigger việc nộp bài.

**Phương án quay về:** Script bị lỗi môi trường hoặc AI báo lỗi sai (hallucinate ra các mục không có trong Rubric) -> Thành viên nhóm bỏ qua tool, tự mở Rubric ra dò tay thủ công như quy trình cũ.

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | 5 | 5 | Chuyển dịch tính chất: từ tự đi "tìm lỗi" thủ công sang "kiểm duyệt và sửa lỗi" từ report tự động |
| Tổng thời gian | 30 phút | khoảng 15 phút | Giảm 50% thời gian. Target chính là duy trì dưới 15 phút/bài |
| Số bước thủ công | 5/5 | 3/5 | Con người vẫn nắm vai trò quyết định trong việc sửa lỗi và nộp bài |
| Bottleneck chính | Đối chiếu nội dung với rubric | Đọc report & sửa lỗi | Chấp nhận bottleneck ở việc sửa lỗi vì đây là điểm kiểm soát chất lượng bắt buộc của con người |
| Rủi ro mới phát sinh | Không có | AI báo sai (bịa lỗi hoặc sót lỗi) | Sẽ xử lý bằng cách lập prompt kèm boundary chặt, yêu cầu con người luôn review chéo report của AI trước khi làm theo |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Người phụ trách review nộp bài lab GitHub trong nhóm |
| **Quy trình** | Mỗi lần trước khi nộp bài, người review phải mở rubric, submission guide và repo; dò tên file/folder, đối chiếu định dạng và nội dung với từng tiêu chí, test link/hình ảnh, rồi chốt và commit/nộp |
| **Bottleneck** | Bước đọc và đối chiếu nội dung từng mục với rubric chiếm khoảng 15 phút / lần nộp; đây là thao tác thủ công, dễ mệt và dễ bỏ sót khi bài dài |
| **Impact** | Mỗi lần review mất 30 phút, làm chậm tiến độ hoàn thiện bài, gây căng thẳng nhóm, và tăng xác suất thiếu file/thiếu mục/đường dẫn sai trước deadline |
| **Success Metric** (baseline → target, cách đo) | Baseline: 30 phút / lần nộp; Target: dưới 15 phút / lần nộp sau khi dùng checklist + AI báo lệch chuẩn. Cách đo: bấm giờ 3 lần review giả định hoặc thực tế, so sánh tổng thời gian và số lỗi còn sót sau khi nộp |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | AI không được tự động sửa file, tự động push hoặc nộp bài. AI chỉ được quét cấu trúc, tìm link lỗi và tạo report cảnh báo. Khi AI phát hiện bất thường, người review phải mở tài liệu gốc và xác nhận lại trước khi chỉnh nội dung hoặc nộp |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

- AI gợi ý: "Bạn đang mô tả một quy trình review nhiều tệp hơn là một pain điểm người dùng rõ ràng" -> nhóm đồng ý, vì cần thêm rõ bản chất pain là đối chiếu nội dung với rubric chứ không chỉ là “check repo”.
- AI gợi ý: "Tốn thời gian 30 phút chưa đủ để khẳng định pain phổ biến, cần có bằng chứng từ người dùng hoặc log thời gian thực" -> nhóm đồng ý và đã ghi lại cần kiểm chứng thêm trong CP4.
- AI gợi ý: "Không nên để AI tự tạo report rồi người dùng tin tưởng hoàn toàn" -> nhóm đồng ý, vì boundary cần quy rõ người review kiểm tra lại trước khi thực hiện.

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
