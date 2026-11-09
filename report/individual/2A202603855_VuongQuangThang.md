
# Báo cáo cá nhân - 2A202603855_VuongQuangThang

## 1. Thông tin học viên

- Họ tên: Vương Quang Thắng
- MSSV: 2A202603855
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: DULU
- Link repo nhóm: https://github.com/LongNhat2kruoi/L3B-DAY02-DULU-DiscoveryProblemFraming/tree/main

## 2. Scan problem (CP1)

| # | Lăng kính | Job Story | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi sự kiện sắp diễn ra, tôi muốn đăng bài truyền thông lên nhiều hội nhóm sinh viên khác nhau, để đảm bảo độ phủ sóng và thu hút người tham gia. | Thành viên ban Truyền thông, Trưởng ban | Tốn 45-60 phút mỗi tối để copy-paste, căn chỉnh lại format text và hashtag cho phù hợp với luật của từng nhóm (khoảng 15-20 groups khác nhau). |
| 2 | Cần đọc, tổng hợp nhiều thông tin | Khi đóng form đăng ký sự kiện workshop, tôi muốn gom nhóm các kỳ vọng và câu hỏi của người tham gia, để điều chỉnh kịch bản MC và bài post recap sau sự kiện cho sát insight. | Ban Truyền thông, Ban Nội dung, MC | Tốn khoảng 1.5 - 2 tiếng đọc thủ công và phân loại 150-200 form đăng ký sau mỗi đợt mở link. |
| 3 | Tốn thời gian | Khi có một bài thông báo gốc (core content), tôi muốn chuyển đổi nhanh thành các phiên bản độ dài khác nhau cho bài đăng Facebook, caption Instagram và email gửi khách mời, để kịp tiến độ đăng bài mỗi ngày. | Thành viên ban Truyền thông (Content writer) | Mất 40-50 phút/bài để cắt gọt, thay đổi giọng văn và định dạng cho phù hợp với từng nền tảng; công việc lặp lại 2-3 lần/tuần trong giai đoạn chạy nước rút. |
| 4 | Pain từ người khác | Khi người tham gia nhắn tin hỏi về địa điểm, lịch trình hoặc cách check-in trên fanpage, tôi muốn phản hồi nhanh chóng và chính xác thông tin từ ban tổ chức, để họ không đánh giá thấp độ chuyên nghiệp của sự kiện. | Người trực page (Ban Truyền thông), Người tham gia | Mất 1-2 tiếng mỗi ngày trực page trong tuần cao điểm, phải gõ đi gõ lại cùng một câu trả lời (ví dụ: vé gửi xe, giờ mở cửa) cho 30-40 người hỏi trùng nhau. |
| 5 | Lặp lại / Tốn thời gian | Khi lên kế hoạch (content calendar) cho một chiến dịch truyền thông mới, tôi muốn thống kê lại hiệu quả (lượt reach, tương tác) của các bài đăng từ chuỗi sự kiện trước, để chọn đúng khung giờ và loại nội dung hiệu quả nhất. | Trưởng ban Truyền thông | Phải dò lại lịch sử fanpage, lôi số liệu từng bài vào Google Sheets mất khoảng 1.5 tiếng mỗi đầu chiến dịch. |
| 6 | Cần đọc, tổng hợp nhiều thông tin | Khi nhận được phản hồi (feedback) dài từ khán giả sau sự kiện, tôi muốn tổng hợp xem mọi người thích hay không thích hoạt động nào nhất, để viết báo cáo nghiệm thu truyền thông nhanh chóng. | Trưởng ban Truyền thông, Trưởng ban Tổ chức | Phải đọc lại hàng chục bình luận và form feedback, thường mất trọn một buổi tối (khoảng 3 tiếng) để ra được báo cáo tổng kết. |

---

## 3. Top 3 Problem Cards + Quy trình nháp (CP2)

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Phân loại form đăng ký (#2) | Quy trình cực kỳ rõ ràng, bottleneck gom nhóm tốn nhiều thời gian nhất, dễ kiểm chứng. | Insight thế nào là "đủ sâu" để chốt kịch bản truyền thông? |
| 2 | Đóng gói bài viết đa kênh (#3) | Đau đớn thật (pain) cho content writer, lặp lại nhiều lần, có baseline đo thời gian rõ. | Làm sao đo được chất lượng bài viết rút gọn (độ hấp dẫn)? |
| 3 | Seeding group sinh viên (#1) | Tốn sức (copy/paste/sửa text), có thể so sánh rõ 4 mức độ (Rule vs Workflow vs Agent). | Group admin có thể đổi luật bất ngờ khiến rule hoặc prompt bị hỏng. |

### Problem Card #1 — Phân loại form đăng ký sự kiện

| Trường | Nội dung |
|---|---|
| Job Story | Khi đóng form đăng ký sự kiện, tôi muốn gom nhóm các kỳ vọng và câu hỏi của người tham gia, để điều chỉnh kịch bản MC và bài post recap sau sự kiện cho sát insight. |
| Actor | Trưởng ban / Thành viên ban Truyền thông. |
| Thời điểm / bối cảnh | Ngay sau khi đóng link form đăng ký sự kiện. |
| Quy trình hiện tại | 1. Xuất dữ liệu từ Google Forms sang Sheets (1') · 2. Đọc lướt tổng quan các cột text dài (10') · 3. Đọc kỹ từng form và gắn tag chủ đề/câu hỏi thủ công (90') · 4. Đếm tag và tổng hợp (15') · 5. Viết báo cáo insight (15') |
| Bottleneck | Bước 3: Đọc và gắn tag thủ công cho 150-200 form mất 90 phút. |
| Impact | Tốn hơn 2 tiếng mỗi lần tổng hợp, báo cáo thường xuyên gửi trễ khiến team nội dung không kịp phản ứng. |
| Success metric | Tổng thời gian từ 131 phút xuống dưới 30 phút. Tỷ lệ tag sai phải sửa lại dưới 10%. |
| Phương án không dùng AI | Dùng add-on tạo Word Cloud (đám mây từ khóa) trên Sheets để bắt keyword chính, bỏ qua việc hiểu ngữ cảnh câu hỏi dài. |

**Quy trình nháp #1:**
```text
HIỆN TẠI — 131 phút
[1 Xuất Sheets: 1'] → [2 Đọc lướt: 10'] → [3 Đọc và gắn tag từng dòng: 90'] ← BOTTLENECK
→ [4 Tổng hợp đếm tag: 15'] → [5 Viết báo cáo insight: 15'] 
```

### Problem Card #2 — Chuyển đổi bài gốc (Repurpose Content) đa kênh

| Trường | Nội dung |
|---|---|
| Job Story | Khi có một bài thông báo gốc, tôi muốn chuyển đổi nhanh thành phiên bản cho Facebook, Instagram và Email, để kịp tiến độ đăng bài mỗi ngày. |
| Actor | Content Writer / Ban Truyền thông. |
| Thời điểm / bối cảnh | Giai đoạn truyền thông nước rút, cần đăng bài phủ trên nhiều nền tảng mỗi ngày. |
| Quy trình hiện tại | 1. Đọc bài gốc (3') · 2. Tạo Docs mới (1') · 3. Cắt gọt, đổi giọng văn và định dạng cho từng nền tảng (30') · 4. Tìm kiếm emoji/hashtag phù hợp (5') · 5. Chốt và gửi duyệt (1') |
| Bottleneck | Bước 3: Viết lại và đổi giọng văn cho 3 nền tảng khác nhau mất 30 phút. |
| Impact | Mất khoảng 40 phút cho mỗi bài gốc, lặp lại 2-3 lần/tuần, gây kiệt sức và trễ content calendar. |
| Success metric | Giảm thời gian tái chế 1 bài content đa kênh từ 40 phút xuống dưới 10 phút. Không phát sinh phàn nàn từ người duyệt bài. |
| Phương án không dùng AI | Viết một bộ template khung (điền vào chỗ trống) cho từng nền tảng. |

**Quy trình nháp #2:**
```text
HIỆN TẠI — 40 phút
[1 Đọc bài gốc: 3'] → [2 Mở Docs: 1'] → [3 Viết lại và đổi tone cho 3 kênh: 30'] ← BOTTLENECK
→ [4 Thêm emoji/hashtag: 5'] → [5 Gửi duyệt: 1']
```

### Problem Card #3 — Tạo biến thể bài đăng Seeding Group

| Trường | Nội dung |
|---|---|
| Job Story | Khi sự kiện sắp diễn ra, tôi muốn đăng bài truyền thông lên nhiều hội nhóm sinh viên khác nhau, để đảm bảo độ phủ sóng và thu hút người tham gia. |
| Actor | Thành viên ban Truyền thông (Seeder). |
| Thời điểm / bối cảnh | Khung giờ vàng buổi tối, cần đăng lên 15-20 group. |
| Quy trình hiện tại | 1. Mở danh sách group và bài chuẩn (2') · 2. Xem luật đăng bài group A (2') · 3. Sửa title/lời chào bài chuẩn cho hợp group A (5') · 4. Đăng bài (1') · 5. Lặp lại bước 2, 3, 4 cho 14 group còn lại (khoảng 70') |
| Bottleneck | Bước 3 và 5: Phải suy nghĩ và sửa tay nội dung cho phù hợp văn hóa từng group liên tục nhiều lần (mất hơn 70 phút). |
| Impact | Tốn gần trọn 1 buổi tối (90 phút) để seeding xong, người đăng hay bị nản, đăng sai luật bị ban nick. |
| Success metric | Rút ngắn thời gian chuẩn bị và đăng 15 group từ 90 phút xuống dưới 20 phút. Số lượng bài bị admin từ chối dưới 2 bài. |
| Phương án không dùng AI | Copy đúng 1 nội dung spam đi tất cả các group (chấp nhận rủi ro bị admin xóa bài). |

**Quy trình nháp #3:**
```text
HIỆN TẠI — 80-90 phút
[1 Lấy bài chuẩn: 2'] → [2 Đọc luật group A: 2'] → [3 Sửa bài cho khớp luật group A: 5'] ← BOTTLENECK
→ [4 Bấm đăng: 1'] → [5 Lặp lại cho 14 group tiếp theo: 70'] ← BOTTLENECK LẶP
```

### Nhật ký AI phản biện 

| Thẻ bài được phản biện | Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|---|
| **#1: Phân loại form** | AI có thể không hiểu các thuật ngữ chuyên ngành hoặc slang (từ lóng) của sinh viên trong form, dẫn đến tag sai. | Đồng ý | Bổ sung phương án kiểm duyệt vào quy trình tương lai (boundary): AI chỉ gán tag nháp, con người bắt buộc duyệt qua bảng tag. |
| **#2: Đóng gói bài viết** | Bài content do AI sinh ra thường có văn phong khuôn mẫu, đọc giống robot, làm giảm tương tác tự nhiên. | Đồng ý một phần | Chấp nhận AI chỉ viết "nháp", đổi mục tiêu từ "AI tự đăng" sang "AI sinh draft 3 kênh, người viết thổi hồn và gửi duyệt". |
| **#3: Seeding group** | Đề xuất dùng "Agent AI tự động đăng bài lên group" là rất khó khả thi (Feasibility) vì Facebook có cơ chế block bot và thay đổi giao diện liên tục. | Đồng ý hoàn toàn | Ghi rõ giới hạn: Chỉ dùng AI để tự sinh 15 phiên bản text (biến thể) sẵn trong Google Docs. Việc đi copy-paste và bấm đăng vẫn do con người làm. |


report/individual/MSSV_HoTen.md

## 4. Tôi đã tham gia phần nào (CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / Bằng chứng |
|---|---|---|
| Pitch Problem Card | Pitch 3 thẻ bài liên quan đến Truyền thông sự kiện (Seeding group, Đóng gói đa kênh, Phân loại form đăng ký). | Thẻ bài "Phân loại form đăng ký" lọt vào top 3 candidate cuối cùng của nhóm. |
| Gom nhóm (Cluster) & Chấm điểm | Cùng nhóm phân tích 12 candidate để gom thành 3 cụm chính; tham gia chấm điểm và rút gọn shortlist. | Bảng Cluster và bảng chấm điểm trong `group_report.md` (mục 2.2 và 2.4). |
| Quy trình nhóm (CP5) | Trực tiếp hỗ trợ vẽ sơ đồ luồng công việc hiện tại và tương lai cho bài toán "Rà soát repository trước khi nộp bài". | Sơ đồ quy trình Before/After trong `group_report.md` (mục 4.1 và 4.2). |
| Viết Problem Statement v0/v1 (CP5, CP6) | Phụ trách viết Success Metric (đo thời gian và điểm format) và thiết lập Boundary (chặn rủi ro AI làm hộ bài). | Mục 5 và Mục 7 trong `group_report.md`. |
| Nhận phản biện | Bị chất vấn: "Tốn 30 phút review đã đủ đau để làm tool chưa, hay chỉ do nhóm làm việc lề mề?" | Nhận ra cần tách rõ thời gian dò lỗi nội dung (bottleneck thật) với thời gian chờ đợi thành viên khác nộp bài. |

---

## 5. Dùng AI (CP7)

| Checkpoint | Dùng AI để làm gì? | AI giúp ích ở đâu? | Sai/hời hợt ở đâu? | Tôi đã sửa gì? |
|---|---|---|---|---|
| CP1 (Scan) | Gợi ý thêm các bài toán theo góc độ của ban Truyền thông. | Nhắc nhở thêm về vấn đề thống kê số liệu tương tác sau chiến dịch. | Gợi ý "Dùng AI tự viết content đăng bài". Đây là một solution, không phải problem, và không có dấu hiệu đo lường. | Bỏ qua ý tưởng này, tự viết lại các bài toán theo đúng chuẩn Job Story không nhắc đến công cụ. |
| CP2 (Thẻ bài) | Đóng vai PM hoài nghi để phản biện 3 thẻ bài nháp. | Chỉ ra rủi ro feasibility khi muốn AI tự động seeding group Facebook. | Gợi ý dùng AI để phân loại form nhưng không nhắc đến rủi ro ngôn ngữ GenZ/Slang. | Bổ sung thêm Boundary: AI chỉ gán tag nháp, có mục "Khác" để con người duyệt lại từ ngữ lạ. |
| CP5, CP6 (Quyết định) | Phản biện Problem Statement v0 của bài rà soát repository. | Giúp nhận ra rằng thời gian không phải thước đo duy nhất, cần đo cả chất lượng rà soát. | Đề xuất giao quyền cho AI (Automate) tự sửa luôn Markdownlint cho nhanh. | Bác bỏ vì vi phạm quy định học thuật. Viết lại Boundary yêu cầu con người duyệt từng lỗi (Augment). |

---

## 6. Reflection cá nhân (CP7)

### 6.1. Bài toán ban đầu của tôi đã tiến hóa thế nào sau khi trao đổi nhóm?
Ban đầu, tôi rất tâm đắc với các thẻ bài mảng truyền thông sự kiện (đặc biệt là phân loại form đăng ký). Tuy nhiên, khi ghép vào nhóm, chúng tôi nhận thấy bài toán "Rà soát repository trước deadline nộp lab" là nỗi đau chung trực tiếp và rõ ràng nhất mà cả 4 thành viên đều vừa trải qua. Tôi đã phải bỏ qua ý tưởng cá nhân để hội tụ cùng nhóm, chuyển trọng tâm từ "xử lý phản hồi khách hàng" sang "đối chiếu nội dung học thuật với Rubric".

### 6.2. Tôi đã thay đổi quyết định gì sau khi nghe AI hoặc bạn học phản biện?
Khi xây dựng quy trình tương lai cho bài rà soát repo (CP5), ban đầu tôi định để AI tự động sửa luôn các lỗi format nhỏ (như sửa heading, sửa link ảnh) để tiết kiệm thêm thời gian. Tuy nhiên, sau khi nghe phản biện về rủi ro liêm chính học thuật và nguy cơ AI "ảo giác" sửa sai nội dung báo cáo gốc, tôi đã quyết định đổi mức can thiệp thành Workflow nghiêm ngặt: AI chỉ đóng vai trò "kiểm toán viên" (sinh report lỗi), còn sinh viên phải tự tay sửa file. Điều này khiến target thời gian không giảm quá sâu (vẫn tốn khoảng 15 phút) nhưng đổi lại là sự an toàn tuyệt đối.

### 6.3. Nếu làm lại, tôi sẽ thay đổi điều gì trong cách tiếp cận của mình?
Nếu được làm lại bước CP4 (Kiểm chứng), tôi sẽ chủ động ra ngoài phỏng vấn ít nhất 3 nhóm khác ngay lập tức thay vì chỉ dựa vào dữ liệu tự báo cáo (self-report) nội bộ của nhóm. Việc chỉ phỏng vấn giả lập khiến chúng tôi thiếu đi những "tín hiệu phản bác" thực tế từ người dùng (ví dụ: có thể nhiều nhóm đã giải quyết xong bài toán này chỉ bằng việc dùng Github Projects rất hiệu quả mà không cần AI). Tôi nhận ra rằng bằng chứng về hành vi đã xảy ra mới là tiếng nói quyết định sống còn của một dự án.