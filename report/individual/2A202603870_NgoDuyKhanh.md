# Báo cáo cá nhân — 2A202603870_NgoDuyKhanh

## 1. Thông tin học viên

- Họ tên: Ngô Duy Khánh
- MSSV: 2A202603870
- Tên nhóm: DULU
- Link repo nhóm: https://github.com/LongNhat2kruoi/K5-L3B-DAY02-DULU-DiscoveryProblemFraming

## 2. Scan problem (CP1)

**Bản nháp để đối chiếu với trải nghiệm cá nhân.** Chủ đề là phối hợp làm bài tập nhóm và chuẩn bị bản nộp. Dòng #6 có dấu vết Git từ phiên làm bài này. Các dòng #1–#5 là tình huống đề xuất. Số lượng và số phút ở những dòng đó là số minh họa, cần thay bằng số của một lần thực tế.

| # | Lăng kính | Job Story | Ai chịu ảnh hưởng? | Dấu hiệu và nguồn có thể kiểm |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi đến lượt cập nhật tiến độ bài nhóm, tôi muốn biết đầu việc nào đã xong và việc nào đang chờ, để chốt đúng phần cần làm tiếp. | Người điều phối nhóm, thành viên đang chờ phần bàn giao | Minh họa: rà 8 đầu việc mất 20 phút/lượt. Kiểm bằng bảng phân công và số đầu việc phải hỏi lại trong lần cập nhật gần nhất. |
| 2 | Cần đọc, tổng hợp nhiều thông tin | Khi nhận góp ý cho bản nháp báo cáo từ cả nhóm chat và tài liệu, tôi muốn biết từng góp ý cần sửa ở đoạn nào, để phân công sửa một lượt và tránh bỏ sót. | Người tổng hợp báo cáo và người được giao sửa | Minh họa: xử lý 12 góp ý từ hai nguồn mất 36 phút/lượt. Kiểm bằng danh sách nhận xét của một vòng duyệt đã ẩn danh và thời gian gom góp ý. |
| 3 | Tốn thời gian | Khi các thành viên đã gửi xong phần của mình, tôi muốn ghép chúng thành một bản có cấu trúc và liên kết đúng, để kịp gửi cả nhóm kiểm tra trước hạn. | Thành viên phụ trách ghép báo cáo | Minh họa: ghép 3 phần vào một file Markdown mất 30 phút. Kiểm bằng lịch sử sửa file và số bảng, ảnh hoặc đường dẫn phải chỉnh lại. |
| 4 | Pain từ người khác | Khi nhận một đầu việc nhóm, tôi muốn biết mình cần bàn giao nội dung gì và ở đâu, để bắt đầu làm mà không phải đợi người giao việc giải thích thêm. | Thành viên mới nhận việc và người giao việc | Minh họa: phải hỏi lại hai lượt về định dạng và vị trí lưu. Kiểm bằng tin nhắn của một lần bàn giao thực tế, ghi vai trò và che tên người. |
| 5 | Cần đọc, tổng hợp nhiều thông tin | Khi chuẩn bị sửa báo cáo sau một buổi họp, tôi muốn tìm lại phương án nhóm đã chốt và lý do chọn, để tránh sửa theo một đề xuất đã bị loại. | Thành viên đang sửa báo cáo | Minh họa: tìm một quyết định trong tin nhắn và ghi chú họp mất 18 phút. Kiểm bằng mốc họp, tin nhắn chốt và thời gian tìm được đoạn cần dùng. |
| 6 | Tốn thời gian | Khi đưa bài cá nhân lên repo chung, tôi muốn xác định đúng nhánh và file sẽ được đưa lên, để đồng đội tìm được bản của tôi. | Thành viên nộp bài qua Git | Ở lượt push đầu tiên trong phiên làm bài, remote chỉ có nhánh `main`. Phải tạo thêm **1 nhánh cá nhân** để push commit `da4a4c6`, trong đó có **1 file báo cáo**. Chưa đo số phút thao tác của học viên. |

**Dùng AI ở CP1.** Codex gợi ý các tình huống theo bối cảnh bài tập nhóm, dựa trên cách bài của Vương Quang Thắng đi từ một vai trò quen thuộc đến các công việc cụ thể. Bản nháp bỏ tình huống nộp nhầm lên LMS vì chưa có dấu vết của một lượt nộp thật. Khánh cần tự chọn các ý khớp với trải nghiệm của mình và thay các số minh họa.

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Gom và phân loại góp ý cho báo cáo (#2) | Có đầu vào và đầu ra rõ. Có thể đếm góp ý bị bỏ sót, gộp nhầm hoặc giao sai mục. | Tốn thời gian vì góp ý nằm ở hai nơi hay vì nhiều góp ý không chỉ rõ đoạn cần sửa? |
| 2 | Ghép các phần thành bản Markdown chung (#3) | Có thể xác định phần nào chiếm nhiều phút và kiểm chất lượng bằng bản xem trước. | Thời gian chủ yếu nằm ở định dạng và liên kết hay ở việc chờ các phần hoàn tất? |
| 3 | Tìm lại quyết định nhóm đã chốt (#5) | Phạm vi gọn, có thể bấm giờ cho mỗi lần tìm và kiểm kết quả bằng tin nhắn chốt. | Nhóm có thường ghi rõ quyết định cuối cùng hay chỉ thảo luận rồi chuyển sang việc khác? |

**Số liệu CP2.** Ba quy trình dưới đây minh họa cách chia bước, tính tổng và đặt mục tiêu. Các mốc trước → sau là cặp giả định để thiết kế phép đo. Bước được đánh dấu là điểm nghi nghẽn cần kiểm bằng một lần thao tác thực tế.

### Problem Card #1 — Gom và phân loại góp ý cho báo cáo

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhận góp ý cho bản nháp báo cáo từ cả nhóm chat và tài liệu, tôi muốn biết từng góp ý cần sửa ở đoạn nào, để phân công sửa một lượt và tránh bỏ sót. |
| Actor | Thành viên phụ trách tổng hợp góp ý trước khi nhóm sửa báo cáo. |
| Thời điểm / bối cảnh | Sau vòng đọc bản nháp, khi đã có khoảng 12 góp ý ở hai nguồn. |
| Quy trình hiện tại cần xác nhận | Mở hai nguồn → chép góp ý vào một danh sách → đối chiếu từng góp ý với mục trong báo cáo → xử lý mục trùng hoặc chưa rõ → gửi danh sách để phân công. |
| Bottleneck | **Bước 3 — đối chiếu góp ý với đoạn cần sửa (18 phút minh họa).** Người tổng hợp phải mở lại bản nháp khi góp ý chỉ ghi “sửa chỗ này” hoặc nhắc một đoạn không có tiêu đề. |
| Impact | Một góp ý bị gắn sai mục có thể khiến thành viên sửa nhầm đoạn hoặc phải hỏi lại. Khi kiểm chứng, ghi số góp ý bị bỏ sót, gắn sai mục hoặc cần làm rõ. |
| Success metric | Kịch bản minh họa **36 → ≤ 22 phút cho một lượt 12 góp ý**. Bấm giờ từ lúc mở nguồn đầu tiên đến khi gửi danh sách. Đối chiếu 12 góp ý gốc với đầu ra. Mỗi góp ý phải có mục đích đến hoặc trạng thái “cần làm rõ”. |
| Phương án không dùng AI | Thống nhất nhận xét ngay cạnh đoạn cần sửa. Với góp ý trong chat, dùng mẫu gồm mục báo cáo, nội dung góp ý và link nguồn. |
| Giả thuyết về AI | Nếu góp ý vẫn đến từ hai nguồn, AI có thể đề xuất nhóm theo mục từ văn bản đã được phép chia sẻ. Người tổng hợp mở nguồn và quyết định góp ý nào thực sự trùng. |
| Cảm nhận nhanh | **No AI trước.** Thử chuẩn hóa cách để lại góp ý rồi đo lại thời gian đối chiếu. |

**Quy trình nháp #1**

```text
KỊCH BẢN MINH HỌA — 36 phút cho 12 góp ý
[1 Mở hai nguồn: 2'] → [2 Gom góp ý vào một bảng: 8']
→ [3 Đối chiếu với mục báo cáo: 18'] ← NGHI NGHẼN
→ [4 Xử lý trùng hoặc chưa rõ: 5'] → [5 Gửi danh sách: 3']
```

### Problem Card #2 — Ghép các phần thành bản Markdown chung

| Trường | Nội dung |
|---|---|
| Job Story | Khi các thành viên đã gửi xong phần của mình, tôi muốn ghép chúng thành một bản có cấu trúc và liên kết đúng, để kịp gửi cả nhóm kiểm tra trước hạn. |
| Actor | Thành viên phụ trách ghép báo cáo của nhóm. |
| Thời điểm / bối cảnh | Sau khi cả ba phần nguồn đã được gửi, trước lượt đọc duyệt chung. |
| Quy trình hiện tại cần xác nhận | Mở ba phần đã chốt → đưa nội dung vào đúng mục → chỉnh tiêu đề, bảng và đường dẫn → mở bản xem trước → gửi link để nhóm duyệt. |
| Bottleneck | **Bước 3 — chỉnh cấu trúc và đường dẫn (15 phút minh họa).** Ảnh hoặc tài liệu đi kèm có thể đổi vị trí khi đưa sang file chung. |
| Impact | Nhóm có thể mất thêm một lượt duyệt nếu thiếu mục hoặc có đường dẫn hỏng. Khi thử, ghi số lỗi bản xem trước phát hiện và số lần phải gửi lại. |
| Success metric | Kịch bản minh họa **30 → ≤ 18 phút/lượt ghép ba phần**. Bấm giờ từ khi mở ba phần đã chốt đến lúc gửi link. Bản đạt khi đủ ba phần và mọi ảnh, liên kết nội bộ đều mở được. |
| Phương án không dùng AI | Cho các thành viên viết theo cùng một mẫu Markdown, thống nhất vị trí lưu ảnh. Dùng bản xem trước và kiểm đường dẫn trước khi gửi. |
| Giả thuyết về AI | Chưa cần. Có thể kiểm phần bắt buộc và liên kết nội bộ bằng quy tắc xác định. |
| Cảm nhận nhanh | **Rule** cho bước dò liên kết và tiêu đề bắt buộc, sau khi nhóm thống nhất cấu trúc. |

**Quy trình nháp #2**

```text
KỊCH BẢN MINH HỌA — 30 phút cho 3 phần đã chốt
[1 Mở các phần: 3'] → [2 Đưa vào đúng mục: 5']
→ [3 Chỉnh tiêu đề, bảng và đường dẫn: 15'] ← NGHI NGHẼN
→ [4 Kiểm bản xem trước: 5'] → [5 Gửi link: 2']
```

### Problem Card #3 — Tìm lại quyết định nhóm đã chốt

| Trường | Nội dung |
|---|---|
| Job Story | Khi chuẩn bị sửa báo cáo sau một buổi họp, tôi muốn tìm lại phương án nhóm đã chốt và lý do chọn, để tránh sửa theo một đề xuất đã bị loại. |
| Actor | Thành viên được giao sửa một mục báo cáo sau họp. |
| Thời điểm / bối cảnh | Bắt đầu sửa một mục khi nhóm từng trao đổi nhiều phương án cho mục đó. |
| Quy trình hiện tại cần xác nhận | Xác định mục đang sửa → tìm từ khóa trong chat và ghi chú họp → đọc ngữ cảnh để phân biệt đề xuất và quyết định → lưu đoạn chốt cùng link nguồn. |
| Bottleneck | **Bước 3 — đọc ngữ cảnh và xác định quyết định cuối (9 phút minh họa).** Kết quả tìm kiếm có thể chứa cả các phương án đã bị loại. |
| Impact | Dùng nhầm phương án có thể dẫn đến sửa lại cùng một mục. Khi thử, ghi số lần chọn nhầm và số lượt phải hỏi lại nhóm. |
| Success metric | Kịch bản minh họa **18 → ≤ 8 phút/quyết định**. Bấm giờ từ lúc xác định mục đến lúc lưu được phương án đã chốt và link nguồn. Với trường hợp chưa có dấu vết chốt, ghi “cần xác nhận” và đếm riêng. |
| Phương án không dùng AI | Sau họp, lưu một dòng gồm mục, quyết định, lý do và link nguồn. Người sửa tra theo tên mục. |
| Giả thuyết về AI | Nếu cần tra nhiều cuộc họp cũ, AI có thể gợi ý đoạn liên quan từ ghi chú đã được phép chia sẻ. Người sửa đọc nguồn để xác nhận phương án cuối. |
| Cảm nhận nhanh | **No AI trước.** Thử ghi quyết định ngay sau họp để giảm việc truy lại sau đó. |

**Quy trình nháp #3**

```text
KỊCH BẢN MINH HỌA — 18 phút để tìm 1 quyết định
[1 Xác định mục: 2'] → [2 Tìm trong chat và ghi chú: 5']
→ [3 Đọc ngữ cảnh và xác định quyết định cuối: 9'] ← NGHI NGHẼN
→ [4 Lưu phương án và link nguồn: 2']
```

### Card muốn pitch nhất

- **Đề xuất Card #1.** Có thể lấy một vòng góp ý làm mẫu, đếm từng góp ý từ lúc gom đến lúc đưa vào danh sách sửa.
- **Câu hỏi muốn nhóm phản biện:** Trong vòng góp ý gần nhất, mất nhiều thời gian hơn ở bước tìm đủ góp ý hay ở bước xác định góp ý đó thuộc đoạn nào? Có thể chỉ ra một góp ý cụ thể không?

### Nhật ký AI phản biện

| Card | Điểm yếu AI chỉ ra | Đã sửa trong bản nháp |
|---|---|---|
| #1 — Gom góp ý | Đo nhanh hơn có thể che việc gộp nhầm hai góp ý khác nhau. | Thêm điều kiện truy được từng góp ý gốc và giữ trạng thái “cần làm rõ” cho trường hợp mơ hồ. |
| #2 — Ghép Markdown | Nếu tính thời gian chờ thành viên gửi bài thì phép đo không còn cho thấy chi phí của bước ghép. | Bắt đầu đo sau khi đã nhận đủ ba phần. Thêm kiểm tra ảnh và liên kết sau khi ghép. |
| #3 — Tìm quyết định | Lượt tìm không thể kết thúc bằng quyết định có nguồn nếu nhóm chưa từng ghi lại việc chốt. | Tách lượt chưa có dấu vết chốt và ghi “cần xác nhận” thay vì suy ra phương án cuối. |

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

> Nhật ký dưới đây chỉ ghi những thao tác có dấu vết trong phiên làm việc với Codex. Các hoạt động thảo luận, phỏng vấn và tự đánh giá cần Khánh tự bổ sung theo trải nghiệm thật.

| Hoạt động | Công việc có dấu vết / phần cần tự bổ sung | Kết quả / bằng chứng |
|---|---|---|
| Pitch Problem Card | Tự bổ sung card đã thực sự trình bày và phản hồi nhận được. | CP2 mới ghi Card #1 muốn pitch; chưa có biên bản pitch thực tế. |
| Phản biện / nhận phản biện | Tự ghi câu hỏi đã đặt, câu hỏi nhận được và điểm đã sửa. | Không suy từ câu hỏi đề xuất thành câu hỏi đã nói trong buổi nhóm. |
| Hội tụ và chọn candidate | Tự bổ sung vai trò trong thảo luận và việc xác nhận candidate. | [Báo cáo nhóm mục 2](../team/group_report.md) đang ghi lựa chọn sơ bộ. |
| CP4 — Chuẩn bị kiểm chứng | Yêu cầu Codex triển khai CP4 từ candidate CP3 và bổ sung kết quả tham khảo, sau đó bổ sung snapshot minh họa. | Báo cáo nhóm mục 3 có assumption map, bộ câu hỏi, snapshot TH1 và ba tình huống giả lập. Chưa có phỏng vấn thật. |
| CP4 — Research | Dùng Codex tra nguồn chính thức và tổng hợp ba cách xử lý liên quan. | Bảng research trong báo cáo nhóm mục 3.3, có link; chưa chạy thử công cụ. |
| Quản lý phiên bản | Yêu cầu Codex commit và push phần CP4 lên nhánh cá nhân. | Commit [6695378](https://github.com/LongNhat2kruoi/K5-L3B-DAY02-DULU-DiscoveryProblemFraming/commit/6695378), nhánh `ngo-duy-khanh`. |
| CP5–CP6 | Báo cáo nhóm hiện có quy trình, Problem Statement v0/v1 và phương án Workflow; chưa có bằng chứng để gán việc soạn các phần này cho Khánh. | Mục 4–8 báo cáo nhóm; quyết định được ghi là Go cho pilot nhỏ, chưa có kết quả pilot. |

## 5. Dùng AI

| Checkpoint | Dùng AI để làm gì? | AI hỗ trợ ở đâu? | Giới hạn / điểm cần sửa | Việc cá nhân cần tự xác nhận |
|---|---|---|---|---|
| CP1–CP2 | Gợi ý tình huống, tổ chức Problem Card và phản biện phép đo. | Tách bước, đề xuất metric và phương án không dùng AI như mô tả ở mục 2–3. | Nhiều số liệu là minh họa; chưa đại diện cho trải nghiệm thật. | Chọn lại các tình huống đã gặp và thay bằng bằng chứng thực tế. |
| CP4 — Research | Đọc yêu cầu CP4, xây assumption map, tìm tài liệu chính thức của GitHub tasklists, Markdownlint và Lychee. | Làm rõ bước mỗi cách xử lý hỗ trợ và khoảng cần người review. | Tài liệu công cụ không chứng minh pain phổ biến hoặc giúp tiết kiệm bao nhiêu phút; chưa có pilot. | Tự mở lại nguồn và kiểm tra nhận định trước khi chốt bài. |
| CP4 — Ví dụ tham khảo | Yêu cầu tạo ba tình huống và một snapshot để tham khảo cách viết. | Minh họa cách tách thời gian, ghi phản chứng và điều chỉnh candidate. | Toàn bộ dữ liệu TH1–TH3 là giả lập, không được dùng như phỏng vấn thật. | Thu thập và thay bằng dữ liệu ngoài nhóm, giữ rõ nguồn và phương pháp. |
| CP7 — Tổng hợp tham khảo | Nhờ AI tổng hợp nhật ký và bản nháp reflection từ repository. | Liên kết CP3–CP6, chỉ ra giới hạn bằng chứng và metric. | Đây là bản AI hỗ trợ, không chứng minh cảm nhận hoặc trải nghiệm cá nhân; chưa đáp ứng yêu cầu tự viết. | Tự xác nhận và viết lại theo trải nghiệm thật trước khi nộp. |

## 6. Reflection (CP7) — bản tổng hợp tham khảo

> Bản nháp do AI hỗ trợ tổng hợp theo yêu cầu, dựa trên nội dung repository và thao tác trong phiên làm bài. Khánh cần tự xác nhận, chỉnh lại nhận định và diễn đạt bằng trải nghiệm cá nhân trước khi nộp. Không có biên bản pitch/phản biện trực tiếp hoặc phỏng vấn thật để thuật lại; TH1–TH3 là giả lập. Phần này không thay thế yêu cầu tự viết reflection của môn học.

**6.1. Tôi học được gì từ top 3 problems của các bạn khác?**

Qua bảng tổng hợp CP3, có thể thấy các thành viên xuất phát từ những bối cảnh rất khác nhau như ô tô, truyền thông sự kiện và làm báo cáo nhóm. Điểm giúp so sánh các candidate là actor, bước nghẽn và bằng chứng, thay vì chỉ dựa vào chủ đề hấp dẫn. Candidate kiểm tra repository có quy trình gần với công việc của nhóm và mốc tự báo cáo khoảng 30 phút, còn candidate gom góp ý trong bản cá nhân vẫn dùng nhiều số liệu minh họa. Đây là nhận xét từ tài liệu, chưa phải trải nghiệm nghe pitch được ghi nhận.

**6.2. Nhóm có lúc nào bị solution-first không? Nhận ra và xử lý thế nào?**

Một điểm cần đề phòng trong bài là chuyển ngay từ việc review lâu sang đề xuất AI kiểm tra bài. Khi chưa biết thời gian chủ yếu nằm ở đọc yêu cầu, đối chiếu nội dung hay chờ thành viên, chọn công cụ sẽ quá sớm. Assumption map ở CP4 giúp tách các câu hỏi đó. Research còn cho thấy repository đã có checklist và có công cụ kiểm tra style, liên kết. Vì vậy, lý do cần thêm AI phải được kiểm tra bằng hiệu quả thực tế so với cách đơn giản hơn.

**6.3. Tôi có đổi ý sau khi bị phản biện không?**

Bản nháp CP2 có một thay đổi cụ thể sau phản biện của AI: ở candidate ghép Markdown, phép đo được giới hạn từ lúc đã nhận đủ các phần, tránh tính cả thời gian chờ thành viên. Ở candidate tìm quyết định, trường hợp không có dấu vết chốt được giữ là “cần xác nhận”, thay vì suy ra quyết định cuối. Hai sửa đổi này cho thấy metric và đầu ra phải có điều kiện rõ. Chưa có dữ liệu để kể một lần Khánh bị thành viên khác phản biện hoặc làm nhóm đổi ý; phần đó cần bổ sung từ buổi thảo luận thật.

**6.4. Kết quả kiểm chứng hoặc research có làm tôi bất ngờ không?**

Điểm đáng chú ý từ research là không cần bắt đầu bằng một hệ thống mới: checklist hỗ trợ theo dõi việc, Markdownlint kiểm tra style và Lychee kiểm tra liên kết. Tuy nhiên, các công cụ đó không đủ để chứng minh nội dung đáp ứng rubric. Ba tình huống TH1–TH3 giúp minh họa sự khác nhau giữa nhóm chưa có mapping yêu cầu với nhóm đã có checklist rõ, nhưng không chứng minh mức tiết kiệm thời gian. Cần giữ riêng tài liệu đã kiểm tra, tự báo cáo của thành viên và số liệu giả lập để tránh biến ví dụ thành bằng chứng.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Trong bản hiện tại, điểm khó cần làm rõ là baseline và phạm vi đo. Khoảng 30 phút là tự báo cáo cho toàn bộ lượt review; mốc 15 phút ở bước đối chiếu chưa có log đo riêng. Quy trình tương lai còn tính thời gian đọc cảnh báo và sửa nội dung, nên phải thống nhất cách tính trước và sau để so sánh công bằng. Mục tiêu dưới 15 phút cần đi kèm số lỗi bỏ sót và công xác nhận cảnh báo sai. Nếu chỉ giảm số phút nhưng bỏ qua lỗi bắt buộc, chưa thể kết luận giải pháp tốt hơn.

**6.6. Nếu làm lại, tôi sẽ đổi gì và phản biện nhóm mạnh hơn ở đâu?**

Hướng cải thiện cụ thể là thu thập dữ liệu người ngoài nhóm sớm hơn, ghi từng bước của một lượt review và thử checklist hiện có trước khi chọn Workflow. Điểm cần phản biện trong CP6 là dùng kịch bản CP4 để suy ra mong muốn của người dùng: dữ liệu giả lập chưa đủ chứng minh họ muốn AI hỗ trợ theo cách nào. Một giới hạn của đầu ra AI là có thể tạo bài trình bày đầy đủ nhưng thiếu bằng chứng cho kết luận. Lần rà soát tiếp theo cần kiểm tra từng claim và nguồn, thay vì chỉ xem các bảng đã được điền hay chưa.

**6.7. Hiểu bài: problem → quy trình → metric → boundary → mức can thiệp AI → quyết định.**

Candidate của nhóm là công rà soát repository trước khi nộp, đặc biệt ở việc đối chiếu nội dung với yêu cầu. Quy trình hiện tại đi từ đọc tài liệu, kiểm tra file, đối chiếu nội dung, kiểm tra liên kết đến chốt bài. Mốc khoảng 30 phút là tự báo cáo ban đầu; mục tiêu dưới 15 phút và thời gian từng bước cần được kiểm chứng bằng phép đo thực tế. Boundary đề xuất giữ AI ở vai trò cảnh báo, còn người review xác nhận và quyết định sửa, commit, nộp bài. CP6 chọn Workflow, dùng Rule cho kiểm tra xác định và AI hỗ trợ đối chiếu văn bản ở một bước. Quyết định được ghi là Go cho pilot một assignment, chưa phải kết luận hiệu quả đã được chứng minh. Nếu công xác nhận cảnh báo sai vượt 5 phút hoặc AI bỏ sót mục bắt buộc gây mất điểm, bản kế hoạch yêu cầu dừng và quay về checklist thủ công.

## 7. Tài liệu tham khảo

- [Worksheet CP1–CP2](../../docs/01-worksheet.md)
- [Rubric](../../RUBRIC.md)
- [Bài của Vương Quang Thắng, tham khảo bố cục CP1–CP2](2A202603855_VuongQuangThang.md)
