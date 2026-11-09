# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Nguyễn Mạnh Hùng
- MSSV: 2A202603852
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: DULU
- Link repo nhóm: https://github.com/LongNhat2kruoi/L3B-DAY02-DULU-DiscoveryProblemFraming/tree/main

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 |Tốn thời gian & Cần tổng hợp thông tin | Khi so sánh các gói vay trả góp 8 năm cho dòng xe VinFast VF5 từ nhiều ngân hàng khác nhau, tôi muốn xem lịch trả nợ gốc và lãi chi tiết từng tháng ngay lập tức, để biết chính xác dòng tiền mình cần chuẩn bị mà không phải tự kẻ bảng Excel ngồi tính thủ công hoặc đợi sale gửi file phản hồi mất nửa ngày. | Người mua |Mất 1-2 tiếng tự tính toán; dễ tính sai lãi suất thả nổi; tỷ lệ khách hỏi lại sale về con số hàng tháng rất cao. |
| 2 | Tốn thời gian & Cần tổng hợp thông tin |Hàng tháng, tôi muốn phân loại hàng ngàn comment review app VinFast thành các nhóm lỗi chính (kết nối xe chậm, lỗi hiển thị trạm sạc, lỗi thanh toán), để đưa vào báo cáo cho team Dev mà không phải ngồi đọc và dán thủ công mất 4-5 tiếng đồng hồ. | Product Team / CSKH | Mất nửa ngày làm việc của 1 nhân viên; dữ liệu bị sót hoặc phân loại sai do mệt mỏi khi đọc quá nhiều text. |
| 3 | Lặp lại & Pain từ người khác|Khi có khách hàng bước vào showroom hỏi mua xe, tôi muốn có ngay con số so sánh chi phí thuê pin và mua đứt dựa trên chính xác số km đi lại dự kiến của họ, để chốt sale nhanh hơn thay vì mỗi lần lại mất 10-15 phút bấm máy tính và giải thích lại chính sách từ đầu. | Sales showroom | Lặp lại 5-10 lần/ngày với mỗi khách mới; khách hàng hay hoang mang vì không tự nhẩm được chi phí dài hạn.|
| 4 | Lặp lại & Pain từ người khác| Khi khách hàng đặt lịch lái thử qua nhiều kênh, tôi muốn biết ngay xe test drive nào đang trống ở khung giờ đó, để xác nhận lịch ngay lập tức chứ không xếp trùng giờ khiến khách đến nơi phải ngồi đợi 30 phút rồi bực bội bỏ về. |Lễ tân/Điều phối showroom |Tỷ lệ khách complain vì chờ đợi cao (pain từ người khác); check lịch qua lại giữa sổ ghi tay và file chung mất 5 phút/lần gọi. |
| 5 |Cần đọc tài liệu dài & Độ phức tạp cao |Khi cắm máy đọc lỗi và nhận về mã code hệ thống ADAS, tôi muốn biết ngay lỗi này thuộc về phần cứng hay do xung đột của bản cập nhật phần mềm mới nhất, để đưa ra phương án sửa đổi bo mạch hoặc chạy lại phần mềm thay vì mất 45 phút tra cứu lại cuốn manual dày hàng trăm trang | Kỹ thuật viên |Xe nằm chờ ở xưởng lâu; thời gian chẩn đoán (thường chiếm 30-40% tổng thời gian sửa) bị kéo dài. |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- AI gợi ý thêm cho tôi về "Xử lý cuộc gọi báo lỗi sạc" nhưng tôi đã bỏ vì tỷ lệ lỗi sạc rất thấp, và khi lỗi thì có thể đổi ngay sang trụ bên cạnh và không mất thời gian phản ánh lên tổng đài

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | So sánh gói vay trả góp cho VF5 giữa các ngân hàng | Actor rõ (khách hàng / sales showroom), quy trình hiện tại dễ mô tả, bottleneck cụ thể ở bước tính toán và đối chiếu lịch trả nợ, impact đo được và xảy ra lặp lại trong từng buổi tư vấn | Cần kiểm chứng khách hàng thực sự muốn so sánh nhiều ngân hàng hay chỉ cần xem số tổng và chênh lệch, và tần suất có đủ lớn để thành vấn đề nhóm cần giải |
| 2 | Phân loại hàng ngàn comment review app VinFast theo lỗi chính | Quy trình rõ, tốn thời gian lớn, nhiều người bị ảnh hưởng (Product/CSKH), bottleneck ở bước đọc và gán nhãn thủ công, dễ đo thời gian và mức độ sai sót | Cần kiểm chứng whether phản hồi bị bỏ sót/nhầm nhóm có ảnh hưởng thực tế lên quyết định phát triển không, và phạm vi có quá rộng không |
| 3 | Chẩn đoán lỗi ADAS / tra cứu manual kỹ thuật | Actor rõ (kỹ thuật viên xưởng), time loss rõ ràng, bottleneck ở tra cứu manual và đối chiếu lỗi, thừa điều kiện để so sánh no AI, rule, workflow | Chỉ nên tập trung vào một nhóm lỗi cụ thể hoặc một phần chẩn đoán; nếu quá rộng sẽ khó kiểm chứng và giữ phạm vi vừa sức lab |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi tôi đang cân nhắc mua xe VinFast VF5 và so sánh nhiều gói vay trả góp từ các ngân hàng, tôi muốn xem ngay lịch trả nợ gốc và lãi chi tiết từng tháng, để biết mình cần chuẩn bị bao nhiêu dòng tiền và ra quyết định mua đúng lúc mà không phải tự tính bằng Excel hoặc chờ sale gửi file trả lời. |
| Actor | Khách hàng mua xe / nhân viên sales showroom hỗ trợ khách so sánh gói vay |
| Thời điểm / bối cảnh | Trước khi ký hợp đồng mua xe, trong các buổi tư vấn hoặc thương lượng với khách hàng, khi khách hỏi so sánh 2-4 gói vay khác nhau |
| Quy trình hiện tại (3–7 bước) | 1. Thu thập các gói vay từ ngân hàng / sale gửi file · 2. Ghi lãi suất, thời hạn, phí phát sinh · 3. Tính số tiền trả hàng tháng theo phương pháp gốc/lãi · 4. Đối chiếu số tiền còn nợ và nguồn vốn của khách · 5. Giải thích về dòng tiền trong 8 năm · 6. Chỉnh sửa lại nếu khách thay kỳ vọng km/đợt trả trước · 7. Gửi kết quả hoặc chốt quyết định |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3–4: tính toán và đối chiếu lịch trả nợ theo từng tháng; mất khoảng 15–20 phút cho 1 gói so với 3 ngân hàng, nếu cần giải thích lại cho khách thì có thể kéo dài lên 30–40 phút |
| Impact (nếu không giải thì sao) | Mỗi khách phải tự tính hoặc chờ sales gửi file, dễ sai số; sale lặp lại giải thích nhiều lần; khách mất thời gian, dễ chán nản và rời đi; doanh số đề xuất có thể bị giảm do quyết định bị kéo dài |
| Success metric (baseline → target) | 15–20 phút/lần → dưới 5 phút/lần; giảm số lần tính lại do sai số; tăng tốc độ chốt sale và giảm câu hỏi lặp lại của khách |
| Phương án không dùng AI | Sử dụng template Excel cố định, công thức chuẩn của từng ngân hàng, checklist các trường cần so sánh; giúp rút gọn thao tác nhập liệu nhưng không giải quyết phần phân tích và giải thích ý nghĩa tài chính cho khách |
| Giả thuyết về AI (nếu có) | AI đọc gói vay từ nhiều ngân hàng, tự tạo bảng khấu hao theo tháng và gợi ý câu giải thích ngắn gọn về “khách cần dự phòng bao nhiêu tiền hàng tháng” trước khi sale chốt |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 15–20 phút/lần

[1 Thu thập gói vay: 3'] → [2 Ghi lãi suất/điều kiện: 3']
→ [3 Tính lịch trả nợ gốc + lãi: 8–10'] ← BOTTLENECK
→ [4 Đối chiếu dòng tiền khách: 4–5']
→ [5 Giải thích cho khách + cập nhật: 5–10']
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi hàng tháng tôi phải đọc và tổng hợp hàng ngàn comment review trên app VinFast, tôi muốn phân loại chúng thành các chủ đề lỗi chính như kết nối xe chậm, lỗi hiển thị trạm sạc hoặc lỗi thanh toán, để báo cáo nhanh cho đội Dev và CSKH mà không phải ngồi đọc và dán nhãn thủ công mất 4–5 tiếng đồng hồ. |
| Actor | Product team / bộ phận CSKH / người phụ trách chăm sóc khách hàng sau bán hàng |
| Thời điểm / bối cảnh | Cuối tháng, trước buổi review sprint hoặc khi có số liệu phản hồi tăng đột biến từ app khách hàng |
| Quy trình hiện tại (3–7 bước) | 1. Export dữ liệu review từ app / form phản hồi · 2. Lọc comment trùng hoặc không liên quan · 3. Đọc từng comment để hiểu nội dung · 4. Gán nhãn chủ đề lỗi hoặc vấn đề chính · 5. Đếm số lượng theo nhóm · 6. Tạo báo cáo tổng hợp cho team · 7. Gửi cho Dev/CSKH để tham khảo |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3–4: đọc từng comment và phân loại thủ công; mất khoảng 4–5 giờ cho một đợt tổng hợp, và dễ bị sót hoặc nhầm nhóm vì lượng text lớn |
| Impact (nếu không giải thì sao) | Team mất thời gian đánh giá backlog, báo cáo phản hồi bị chậm, lỗi quan trọng có thể bị bỏ sót, khiến ưu tiên xử lý không đúng và khách hàng tiếp tục gặp vấn đề tương tự |
| Success metric (baseline → target) | 4–5 giờ/đợt → dưới 1–2 giờ/đợt; giảm sai sót trong phân loại; tăng tốc độ phản hồi cho team Dev |
| Phương án không dùng AI | Dùng template Excel/Google Sheets, danh sách keyword cố định, và quy trình gán nhãn theo từng nhóm lỗi; vẫn cần người đọc từng comment, nên thời gian vẫn cao |
| Giả thuyết về AI (nếu có) | AI tự phân loại comment theo nhóm lỗi và tóm tắt xu hướng sai lệch trong từng mốc thời gian, rồi giao cho người review xác nhận cuối cùng |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 4–5 giờ/đợt

[1 Export feedback: 20'] → [2 Lọc trùng: 15']
→ [3 Đọc từng comment: 150–180'] ← BOTTLENECK
→ [4 Gán nhãn chủ đề: 90–120']
→ [5 Thống kê + báo cáo: 30–45']
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi kỹ thuật viên cắm máy đọc lỗi và nhận về mã lỗi hệ thống ADAS, tôi muốn biết ngay lỗi này thuộc về phần cứng hay do xung đột của bản cập nhật phần mềm mới nhất, để chọn phương án sửa phù hợp mà không phải tra cứu manual hàng trăm trang và chờ xe ở xưởng quá lâu. |
| Actor | Kỹ thuật viên sửa xe / đội kỹ thuật xưởng / bộ phận chẩn đoán hệ thống ADAS |
| Thời điểm / bối cảnh | Khi xe vào xưởng để kiểm tra lỗi hoặc sau khi cập nhật phần mềm mới, cần chẩn đoán nguyên nhân trong vòng đầu tiên của ca sửa |
| Quy trình hiện tại (3–7 bước) | 1. Đọc mã lỗi từ máy chẩn đoán · 2. Mở manual hoặc tài liệu kỹ thuật liên quan · 3. Đối chiếu với phiên bản phần mềm hiện tại và lịch sử cập nhật · 4. Kiểm tra phần cứng hoặc bộ phận liên quan · 5. Chạy thử lại hoặc kiểm tra theo trình tự khắc phục · 6. Xác định nguyên nhân chính và ghi biên bản · 7. Bàn giao cho đội sửa |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2–3: tra cứu manual và đối chiếu với dữ liệu bản cập nhật; thường mất 30–40 phút cho mỗi mã lỗi, và có thể kéo dài hơn nếu không biết lỗi thuộc về phần cứng hay phần mềm |
| Impact (nếu không giải thì sao) | Xe phải chờ lâu ở xưởng, nhân sự đang làm các công việc khác bị gián đoạn, độ trễ sửa chữa tăng, gây mất hiệu suất và giảm khả năng xử lý xe trong ngày |
| Success metric (baseline → target) | 30–40 phút/lần → dưới 10–15 phút/lần; giảm thời gian xe chờ và tăng số lỗi được chẩn đoán đúng ở lần đầu |
| Phương án không dùng AI | Checklist gỡ rối theo từng mã lỗi, tra cứu trong manual nội bộ, dùng lịch sử sửa lỗi cũ để đối chiếu; giúp tổ chức dữ liệu nhưng vẫn cần người đọc và suy luận nhiều |
| Giả thuyết về AI (nếu có) | AI so sánh mã lỗi, phiên bản phần mềm và lịch sử sửa lỗi tương tự để đề xuất nguyên nhân khả dĩ và bước kiểm tra tiếp theo, giúp kỹ thuật viên tập trung vào đúng hướng trong vài phút đầu |
| Cảm nhận nhanh | Rule / Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 30–40 phút/lần

[1 Đọc mã lỗi: 5'] → [2 Mở manual: 10']
→ [3 So sánh với bản cập nhật + lịch sử lỗi: 15–20'] ← BOTTLENECK
→ [4 Kiểm tra phần cứng: 10–15']
→ [5 Chốt nguyên nhân + hướng sửa: 5–10']
```

### Card muốn pitch nhất

- Card số: 1
- Vì sao: vấn đề có actor rõ, quy trình hiện tại dễ mô tả, bottleneck cụ thể và có thể đo bằng thời gian, impact trực tiếp lên khách hàng và doanh số, đồng thời dễ đối chiếu giữa No AI / Rule / Workflow
- Câu hỏi muốn nhóm phản biện: "Khách hàng có thực sự sẵn sàng so sánh nhiều gói vay hay chỉ cần xem 1–2 con số chính?" và "Nếu không dùng AI, cách đơn giản nhất để giảm nửa thời gian là gì?"

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Bottleneck cần cụ thể hơn và có số phút | Đồng ý | Thêm bước 3–4 tính toán + đối chiếu lịch trả nợ, ước tính 15–20 phút/lần |
| Metric chưa đủ mạnh nếu chỉ là cảm giác | Đồng ý | Bổ sung baseline → target rõ, so sánh 15–20 phút/lần xuống dưới 5 phút/lần |
| Có nguy cơ vượt quá phạm vi sang “hệ thống AI quyết định tài chính” | Đồng ý | Giữ ý tưởng ở mức hỗ trợ giải thích và so sánh, không tự quyết định mua hay không |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | | | | |
| CP2 Problem Card | | | | |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
