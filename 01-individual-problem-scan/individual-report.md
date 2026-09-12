# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Ngô Tiến Dũng
- Mã học viên: 2A202602374
- Vai trò / bối cảnh : AI Product Manager - Khối Vận hành & Đô thị Thông minh VinHomes
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
  - Tiếp nhận, rà soát và phân loại các phản ánh, khiếu nại, feedback của cư dân từ các kênh (App VinHomes Resident, hotline CSKH, ban quản lý khu đô thị - BQL, nhóm cộng đồng cư dân).
  - Khảo sát thực địa, đặc tả yêu cầu sản phẩm (PRD, User Stories, Acceptance Criteria) cho các giải pháp chuyển đổi số và ứng dụng AI (Smart City, Smart Living).
  - Theo dõi, đo lường các chỉ số vận hành và độ chính xác của các mô hình AI đang chạy thực tế (nhận diện biển số hầm xe LPR, camera giám sát an ninh thông minh, chatbot chăm sóc cư dân).
  - Phối hợp liên phòng ban (Ban Quản lý khu đô thị, Đội Vận hành - Kỹ thuật, Trung tâm Chăm sóc khách hàng CSKH, đội ngũ Kỹ sư AI/Dev) để phân tích lỗi, cải tiến quy trình và nghiệm thu tính năng mới.
  - Tổng hợp báo cáo tuần/tháng về chất lượng dịch vụ vận hành số, phân tích nguyên nhân gốc rễ (Root Cause) các sự cố công nghệ và đề xuất kế hoạch tối ưu trải nghiệm cư dân cho Ban Lãnh đạo.

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| #   | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được                                                                                                                                                            | Ai chịu ảnh hưởng?                                                                  | Dấu hiệu thật (số + bằng chứng)                                                                                                                                                                                                                                                  |
| --- | ---------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | Lặp lại                                                                      | Đọc, phân loại thủ công và gán nhãn hàng trăm phản ánh của cư dân từ App VinHomes Resident sang đúng nhóm nghiệp vụ và BQL phân khu                                              | Nhân viên trực CSKH tiếp nhận, AI Product Manager, Kỹ thuật viên BQL phân khu       | 350-450 feedback/tuần/khu đô thị lớn (Ocean Park, Smart City). Nhân viên trực mất trung bình 2.5 giờ/ngày (bấm giờ 3 ngày liên tiếp: 140', 165', 150') chỉ để đọc text, xem ảnh, phân loại vào 18 danh mục và gán ticket thủ công.                                               |
| 2   | Tốn thời gian                                                                | Rà soát và trích xuất dữ liệu video camera an ninh khi phát sinh sự cố (va quẹt xe hầm đỗ, rơi đồ ban công, thất lạc tài sản khu vực công cộng)                                  | Đội An ninh khu đô thị, Ban Quản lý, Cư dân có yêu cầu hỗ trợ                       | Trung bình 8-12 yêu cầu tra cứu/tuần/phân khu. Nhân viên an ninh mất 45-75 phút/lần ngồi tua lại video từ 4-6 góc camera giám sát; cư dân phải chờ tại phòng an ninh tối thiểu 60-90 phút mới có kết quả bước đầu.                                                               |
| 3   | AI có thể tốt hơn                                                            | Chatbot chăm sóc cư dân trên App VinHomes trả lời theo kịch bản cứng (rule-based), không hiểu được ngôn ngữ tự nhiên viết tắt, tiếng lóng hoặc câu hỏi có nhiều ý                | Cư dân VinHomes, Đội ngũ tổng đài viên CSKH trực ca                                 | Log tháng 8/2026: 1.850 lượt chat/tuần, tỷ lệ bấm "Chuyển gặp tổng đài viên" (escalation rate) lên đến 64%, khiến thời gian chờ tổng đài giờ cao điểm (19h-21h) tăng từ 45 giây lên 4 phút 15 giây; cư dân đánh giá CSAT chatbot chỉ 2.3/5 sao.                                  |
| 4   | Pain từ người khác                                                           | Nhân viên soát vé hầm xe phải đối soát thủ công và giải trình khi hệ thống nhận diện biển số (LPR) không nhận diện được xe ra/vào (biển số mờ, bụi bẩn, ngược sáng)              | Nhân viên soát vé bãi xe, Kỹ thuật viên vận hành bãi đỗ, Cư dân đi ô tô/xe máy      | 25-35 sự cố/ngày/hầm xe tại khu Smart City. Mỗi ca kẹt mất 3-5 phút nhân viên phải mở ảnh lịch sử quét thẻ đối chiếu thủ công với ảnh camera, gây ùn tắc kéo dài 15-20 xe vào khung giờ cao điểm sáng 7h30 - 8h15.                                                               |
| 5   | Lặp lại                                                                      | Tổng hợp số liệu vận hành hàng tuần của các giải pháp AI/IoT (tỷ lệ mở barrier tự động, uptime camera an ninh, số sự cố kỹ thuật) từ nhiều dashboard rời rạc để làm báo cáo tuần | AI Product Manager, Trưởng bộ phận Vận hành công nghệ, Giám đốc Khối Vận hành       | Lặp lại mỗi sáng thứ Hai: mất 100-120 phút export dữ liệu từ 3 hệ thống (Grafana IoT, Jira Service Management, Portal Quản lý bãi xe), nhập thủ công vào Excel và viết tóm tắt narrative 15 slide PowerPoint.                                                                    |
| 6   | Tốn thời gian                                                                | Soạn thảo PRD và kịch bản kiểm thử (Test Cases) chi tiết cho các tính năng AI thị giác máy tính phát hiện hành vi bất thường (đỗ xe sai vị trí, xả rác bừa bãi, trèo rào)        | AI Product Manager, Đội ngũ Kỹ sư AI R&D, Đội kiểm thử QA/QC                        | Mất 6-8 giờ cho mỗi bản tài liệu PRD; thường phải trải qua 2-3 vòng review (kéo dài 4-5 ngày làm việc) do thường xuyên bỏ sót các edge-case ngoại cảnh (thời tiết mưa giông, ban đêm thiếu sáng, góc khuất tán cây).                                                             |
| 7   | Pain từ người khác                                                           | Phê duyệt hồ sơ đăng ký thi công nội thất và đăng ký vận chuyển đồ vào căn hộ của cư dân bị chậm trễ do đối chiếu thủ công nhiều giấy tờ                                         | Cư dân mới nhận nhà, Nhà thầu thi công nội thất, Bộ phận Lễ tân & Kỹ thuật BQL      | 30-50 hồ sơ đăng ký/ngày/phân khu. Thời gian xử lý trung bình 24-48 giờ vì BQL phải mở từng file đính kèm (bản vẽ, CMND/CCCD thợ, danh mục vật tư) đối chiếu checklist quy chế bằng mắt. Khiếu nại về đăng ký thi công chiếm 22% tổng phản ánh tuần.                             |
| 8   | AI có thể tốt hơn                                                            | Tra cứu sổ tay cư dân, quy chế quản lý tòa nhà và các văn bản quy định nội bộ khi nhân viên BQL mới tiếp nhận câu hỏi của cư dân tại quầy lễ tân                                 | Nhân viên Lễ tân/CSKH mới (dưới 3 tháng kinh nghiệm), Cư dân hỏi trực tiếp tại sảnh | Bộ tài liệu quy chế tòa nhà và sổ tay cư dân dài hơn 180 trang PDF phân tán trong 5 file văn bản. Nhân viên mới mất 5-10 phút tra cứu cho 1 câu hỏi về "quy định nuôi thú cưng" hoặc "quy chuẩn kích thước biển hiệu kinh doanh tầng 1", cư dân phải đứng chờ sốt ruột.          |
| 9   | Lặp lại                                                                      | Phân tích nguyên nhân gốc rễ (Root Cause Analysis) và gom nhóm các ý kiến đánh giá tiêu cực (CSAT dưới 3 sao) sau khi cư dân sử dụng dịch vụ tiện ích khu đô thị                 | AI Product Manager, Trưởng phòng Trải nghiệm khách hàng (CX), Ban Quản lý           | Định kỳ 1 lần/tháng, nhận về khoảng 1.200 - 1.500 ý kiến đánh giá dạng text tự do. PM và chuyên viên CX mất 14-16 giờ đọc từng dòng, gán nhãn thủ công trên Google Sheets (thái độ nhân viên, vệ sinh, app lag, tiện ích quá tải) để làm slide báo cáo.                          |
| 10  | Pain từ người khác                                                           | Nhân viên trực trung tâm điều hành an ninh (SOC) bị quá tải vì hàng trăm cảnh báo giả (False Positive) từ hệ thống camera AI cảnh báo xâm nhập ảo và cảm biến khói               | Nhân viên an ninh trực màn hình SOC, Kỹ sư vận hành IoT                             | Trung bình 70-90 cảnh báo xâm nhập ảo/ngày trên màn hình SOC; 82% là cảnh báo giả do cành cây đung đưa trước gió hoặc côn trùng/mưa hắt vào camera. Gây hiện tượng "alert fatigue" (chai lỳ cảnh báo), dẫn đến nhân viên lơ là và xử lý chậm 20 phút khi có sự cố trèo rào thật. |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**

- Prompt đã hỏi: "Tôi là AI Product Manager tại Vinhomes, phụ trách các giải pháp công nghệ vận hành đô thị thông minh và tiếp nhận phản ánh cư dân. Công việc gồm rà soát ticket feedback, viết PRD cho tính năng AI, theo dõi metric hệ thống LPR bãi xe/camera AI, và làm báo cáo tuần. Hãy gợi ý thêm các candidate problems theo 4 lăng kính: Lặp lại, Tốn thời gian, AI có thể tốt hơn, Pain từ người khác. Yêu cầu mỗi ý phải có actor cụ thể, dấu hiệu định lượng (thời gian, số lần, ticket) trong bối cảnh thực tế khu đô thị lớn."
- Ý dùng được: Bổ sung góc nhìn về tình trạng quá tải cảnh báo giả (alert fatigue) của nhân viên an ninh SOC (Problem #10) và việc tra cứu quy chế quản lý tòa nhà phân tán cho nhân viên lễ tân mới (Problem #8).
- Ý bỏ vì không phải pain thật: Ý tưởng "AI tự động dự báo biến động giá căn hộ thứ cấp cho cư dân" (bỏ vì đây là bài toán đầu tư bất động sản, không thuộc phạm vi vận hành dịch vụ khu đô thị của AI Product VinHomes) và "AI tự động chấm công bảo vệ bằng nhận diện khuôn mặt liên tục" (bỏ vì thiết bị camera hiện tại không hỗ trợ tracking liên tục, vi phạm quyền riêng tư và vấp phải sự phản đối gay gắt của nhân sự vận hành).

**Self-check Phase 1:**

- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể (Đã điền 10 dòng chi tiết có số liệu đo lường thực tế)
- [x] Dùng ít nhất 3/4 lăng kính (Đã dùng đủ cả 4 lăng kính: Lặp lại, Tốn thời gian, AI có thể tốt hơn, Pain từ người khác)
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian" (Mọi dòng đều có số phút, số ca/ngày, tỷ lệ % và hậu quả rõ ràng)

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan)                                                                                                                      | Vì sao chọn (2-3 ý)                                                                                                                                                                                                                                                                                                                                       | Điều còn chưa chắc                                                                                                                                                                  |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1    | Đọc, phân loại thủ công và gán nhãn hàng trăm phản ánh của cư dân từ App VinHomes Resident sang đúng nhóm nghiệp vụ và BQL phân khu (Problem #1) | 1. Trực tiếp khớp với vai trò hằng tuần của AI Product VinHomes ("tiếp nhận feedback và đưa ra giải pháp").<br>2. Tần suất lặp lại cao hàng ngày (350-450 feedback/tuần), bottleneck rất nét ở bước đọc hiểu & gắn tag 18 danh mục.<br>3. Input text/ảnh có sẵn trên hệ thống CRM, đo lường được ngay thời gian giảm từ 150 phút/ngày xuống 20 phút/ngày. | Độ chính xác khi cư dân viết ngắn cụt lủn chỉ đính kèm ảnh, hoặc câu văn phản ánh nhiều vấn đề đan xen (vừa chê thang máy vừa mắng bảo vệ).                                         |
| 2    | Tổng hợp số liệu vận hành hàng tuần của các giải pháp AI/IoT từ nhiều dashboard rời rạc để làm báo cáo tuần (Problem #5)                         | 1. Chu kỳ cố định thứ Hai hằng tuần, tốn 100-120 phút của PM và Ops Lead.<br>2. Bottleneck rõ ở bước tổng hợp các metrics rời rạc và viết tóm tắt (narrative) phân tích biến động.<br>3. Dễ áp dụng mô hình Workflow kết hợp LLM để sinh draft báo cáo theo cấu trúc mẫu sẵn có.                                                                          | Các dashboard dữ liệu (Grafana, Jira, Bãi xe) có sẵn API chuẩn hóa để auto-pull hay vẫn cần trích xuất file CSV trung gian; chất lượng narrative có đủ sâu để lãnh đạo duyệt không. |
| 3    | Nhân viên soát vé hầm xe phải đối soát thủ công và giải trình khi hệ thống nhận diện biển số (LPR) không nhận diện được xe ra/vào (Problem #4)   | 1. Pain point ảnh hưởng trực tiếp đến trải nghiệm cư dân tại thực địa (gây ùn tắc hầm xe giờ cao điểm).<br>2. Bottleneck xác định ở bước nhân viên mở từng ảnh tra cứu đối soát thẻ vào - ra.<br>3. Có thể dùng mô hình thị giác máy tính / VLM để đọc lại các biển số mờ hoặc gợi ý ứng viên biển số gần đúng nhất.                                      | Yêu cầu độ trễ cực thấp (< 2 giây) để kịp mở barrier; chi phí hạ tầng edge/cloud và tỷ lệ sai sót khi biển số bị cố tình che lấp hoặc dính bùn đất nặng.                            |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Phân loại & Định tuyến Thông minh Phản Ánh Cư Dân VinHomes Resident

```text
Problem 1 câu:
Nhân viên CSKH và AI Product mỗi ngày mất 2.5 giờ đọc và phân loại thủ công 350-450 phản ánh của cư dân từ App VinHomes Resident sang 18 nhóm dịch vụ, khiến ticket bị trễ từ 2-4 giờ trước khi đến được bộ phận xử lý kỹ thuật/vận hành.

Actor:
Chuyên viên trực tiếp nhận CSKH / Quản trị viên hệ thống tiếp nhận phản ánh cư dân VinHomes.

Thời điểm / bối cảnh:
Diễn ra liên tục mỗi ngày từ 7h30 đến 21h30 trên hệ thống Cổng tiếp nhận cư dân (VinHomes Resident Portal) và CRM Vận hành.

Current workflow 3-7 bước:
1. Nhận thông tin phản ánh mới từ App cư dân (gồm text mô tả, hình ảnh đính kèm, định danh căn hộ/phân khu).
2. Đọc nội dung phản ánh và mở xem ảnh chụp hiện trường đính kèm.
3. Đối chiếu và chọn danh mục nghiệp vụ phù hợp trong bảng 18 danh mục (Vệ sinh, An ninh, Cơ điện, Cảnh quan, Thang máy, Tiện ích...).
4. Đánh giá mức độ ưu tiên/khẩn cấp (P1: Khẩn cấp như ngập nước/mùi gas/kẹt thang; P2: Cần xử lý trong ngày; P3: Góp ý thông thường) và chọn bộ phận xử lý (BQL Tòa nhà, Kỹ thuật, Nhà thầu, CSKH).
5. Nhấn chuyển tiếp (Dispatch/Route) ticket đến phân ban chịu trách nhiệm tại khu đô thị.

Bottleneck:
Bước 3 & 4 (Đọc hiểu ngữ cảnh text + ảnh và chọn danh mục + phân loại mức độ khẩn cấp): tốn khoảng 80-90 phút/ngày, nhân viên dễ mệt mỏi dẫn đến phân loại nhầm danh mục (tỷ lệ gán sai ~14%), làm ticket bị trả ngược qua lại giữa các phòng ban.

Impact:
- Tốn 150 phút/ngày (2.5 giờ) của nhân viên tiếp nhận.
- Cư dân phải chờ trung bình 180 phút mới nhận được xác nhận tiếp nhận ticket.
- Ticket bị phân loại sai làm kéo dài thời gian xử lý sự cố thêm 12-24 giờ, gây bức xúc trên các nhóm cư dân.

Success metric:
- Giảm tổng thời gian tiếp nhận và phân loại từ 150 phút/ngày xuống dưới 20 phút/ngày (giảm 86%).
- Nâng tỷ lệ phân loại chính xác danh mục nghiệp vụ từ 86% lên >= 93%.
- Rút ngắn thời gian từ lúc cư dân gửi đến khi ticket được route tới đúng đội phụ trách từ 180 phút xuống dưới 15 phút.

Non-AI alternative:
- Bắt cư dân tự chọn dropdown 18 danh mục khi gửi phản ánh: Cư dân thường chọn đại danh mục đầu tiên ("Khác" hoặc "Góp ý chung") để gửi cho nhanh, tỷ lệ sai danh mục thực tế lên tới 40%.
- Dùng bộ lọc từ khóa tĩnh (Rule-based Keyword Matching): Dễ sai sót nghiêm trọng do tiếng Việt phong phú, viết tắt ("kẹt bồn cầu" bị match nhầm sang "vệ sinh hành lang").

AI hypothesis:
Sử dụng LLM kết hợp trích xuất thông tin (Text Classification & Named Entity Recognition) để tự động đọc hiểu text phản ánh, gán đúng 1 trong 18 danh mục, chấm mức độ khẩn cấp (P1/P2/P3), và sinh bản tóm tắt ngắn cho kỹ thuật viên. Nếu độ tin cậy (Confidence Score) >= 90%, tự động route ticket; nếu < 90%, đẩy sang màn hình Human Review để nhân viên CSKH chỉ cần 1 cú click duyệt.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 150 phút/ngày (cho ~70 ticket/ngày)

[1 Tiếp nhận ticket từ App: 15']
→ [2 Đọc text & xem ảnh: 40']
→ [3 Tra cứu & gán danh mục (18 tags): 50']  <-- bottleneck
→ [4 Đánh giá mức độ P1-P3 & chọn đội xử lý: 30']
→ [5 Route ticket sang BQL: 15']

FUTURE STATE — 20 phút/ngày

[1 Webhook nhận ticket từ App: 0.1']
→ [2 LLM phân loại danh mục, gán độ khẩn cấp & sinh tóm tắt: 0.5']
→ [3 Rule kiểm tra Confidence Score:
     - Nếu Score >= 90% (khoảng 80% ca): Tự động route ticket (2')
     - Nếu Score < 90% hoặc P1 khẩn cấp: Đẩy hàng đợi CSKH Review & click duyệt (15')]  <-- human boundary
→ [4 Dispatch ticket sang BQL tòa nhà: 2']

Fallback: nếu AI API timeout hoặc gặp lỗi parsing, hệ thống tự động gắn tag "Cần xử lý thủ công" và chuyển về hàng đợi thường của nhân viên CSKH như quy trình cũ, tuyệt đối không làm mất mát ticket.
```

---

#### Problem Card #2 — Tự Động Hóa Dự Thảo Báo Cáo Tuần Vận Hành Hệ Thống Smart City

```text
Problem 1 câu:
Mỗi sáng thứ Hai, AI Product Manager và Chuyên viên Vận hành mất 110 phút trích xuất dữ liệu từ 3 hệ thống rời rạc để tính toán chỉ số và viết bản tóm tắt phân tích (narrative) cho báo cáo vận hành tuần gửi Giám đốc Khối.

Actor:
AI Product Manager và Lead Vận hành hệ thống đô thị thông minh.

Thời điểm / bối cảnh:
Từ 8h00 đến 10h00 sáng thứ Hai hằng tuần, trước cuộc họp giao ban ban lãnh đạo Khối Vận hành lúc 10h30.

Current workflow 3-7 bước:
1. Đăng nhập vào 3 hệ thống (Grafana IoT, Jira Service Management, Portal Quản lý bãi đỗ xe) để export 3 file dữ liệu dạng CSV/Excel.
2. Mở file Excel tổng, copy-paste số liệu và chạy công thức tính các chỉ số tuần (tỷ lệ mở barrier tự động, số ca lỗi LPR, uptime camera an ninh, số ticket quá hạn SLA).
3. Đọc số liệu so sánh với tuần trước (WoW) để phát hiện các phân khu có chỉ số bất thường.
4. Viết phần nhận xét, phân tích nguyên nhân và đề xuất hành động khắc phục (narrative) vào slide PowerPoint báo cáo.
5. Format lại layout bảng biểu, kiểm tra số liệu lần cuối và gửi email đính kèm file cho Giám đốc Khối.

Bottleneck:
Bước 4 (Viết narrative phân tích nguyên nhân và đề xuất hành động từ số liệu thô): mất khoảng 45 phút, thường gặp tình trạng bí từ, diễn đạt khô khan hoặc bỏ sót góc nhìn vận hành thực tế.

Impact:
- Tốn 110 phút/tuần của PM và Ops Lead (tương đương gần 1/2 ngày làm việc đầu tuần).
- Thường xuyên sát giờ họp mới xong báo cáo, không kịp chuẩn bị kỹ nội dung giải trình cho các vấn đề phát sinh.

Success metric:
- Giảm tổng thời gian làm báo cáo từ 110 phút xuống dưới 25 phút.
- Thời gian viết narrative giảm từ 45 phút xuống 10 phút (PM chỉ cần đọc và chỉnh sửa bản draft do AI tạo ra).
- Đảm bảo 100% số liệu tính toán chính xác tuyệt đối, không có sai lệch so với nguồn dữ liệu gốc.

Non-AI alternative:
- Thiết lập dashboard Looker Studio / Power BI tự động liên kết dữ liệu: Giải quyết rất tốt việc hiển thị số liệu và biểu đồ tự động, nhưng KHÔNG viết được đoạn văn nhận xét phân tích (narrative) nguyên nhân và đề xuất hành động theo ngữ cảnh tuần.

AI hypothesis:
Kết hợp Script/Rule tự động kéo số liệu từ API/database vào bảng template cố định, sau đó truyền prompt kèm số liệu WoW vào LLM để tự động sinh 3 đoạn văn narrative: (1) Điểm nổi bật trong tuần, (2) Các vấn đề/rủi ro bất thường cần lưu ý, (3) Hành động ưu tiên trong tuần tới. PM đóng vai trò reviewer hiệu đính trước khi xuất slide.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 110 phút

[1 Export CSV từ 3 nguồn: 15']
→ [2 Ghép Excel & tính công thức: 25']
→ [3 Đọc số liệu & tìm điểm bất thường: 15']
→ [4 Viết narrative nhận xét & đề xuất: 45']  <-- bottleneck
→ [5 Format slide & gửi email: 10']

FUTURE STATE — 25 phút

[1 Script tự động query dữ liệu từ DB/API vào JSON/Sheets: 2']
→ [2 Rule tính toán chênh lệch WoW tự động: 1']
→ [3 LLM đọc số liệu & draft 3 đoạn narrative theo cấu trúc mẫu: 2']
→ [4 PM review, kiểm tra đối chiếu & chỉnh sửa narrative: 18']  <-- human boundary
→ [5 Xuất slide và gửi báo cáo: 2']

Fallback: Nếu LLM sinh nội dung chung chung hoặc không bám sát nghiệp vụ, PM sử dụng template câu hỏi checklist có sẵn để tự viết lại narrative như cũ dựa trên bảng số liệu đã được tự động tính toán.
```

---

#### Problem Card #3 — Trợ Lý Đối Soát Biển Số & Hỗ Trợ Khắc Phục Sự Cố Barie Hầm Đỗ Xe

```text
Problem 1 câu:
Nhân viên soát vé hầm xe mất 3-5 phút đối soát thủ công ảnh lịch sử mỗi khi camera LPR không nhận diện được biển số phương tiện lúc xe ra, gây ùn tắc kéo dài 15-20 phương tiện trong khung giờ cao điểm sáng tại các khu đô thị lớn.

Actor:
Nhân viên soát vé bãi đỗ xe thuộc BQL khu đô thị, Cư dân và khách điều khiển phương tiện ra/vào hầm.

Thời điểm / bối cảnh:
Khung giờ cao điểm sáng (7h00 - 8h30) và chiều (17h30 - 19h00) tại các cửa hầm đỗ xe tòa nhà Vinhomes.

Current workflow 3-7 bước:
1. Xe đến làn ra, quét thẻ cư dân nhưng camera không đọc được biển số (do biển mờ, dính bùn, góc nghiêng hoặc ngược sáng), barie không tự động mở.
2. Màn hình của nhân viên soát vé báo lỗi "Không khớp biển số vào/ra".
3. Nhân viên phải mở module tra cứu lịch sử, nhập thủ công mã số thẻ hoặc ước lượng giờ xe vào để tìm ảnh lúc xe vào.
4. Nhân viên nhìn bằng mắt thường để so sánh ảnh xe lúc vào và ảnh thực tế lúc ra (màu xe, dòng xe, biển số thực tế).
5. Sau khi xác nhận đúng, nhân viên gõ phím override mở barie bằng tay và ghi chú lý do mở cưỡng bức vào sổ nhật ký ca trực.

Bottleneck:
Bước 3 & 4 (Tra cứu thủ công và đối soát bằng mắt giữa 2 ảnh vào - ra): mất 2-3 phút/ca, nhân viên thao tác lúng túng dưới áp lực tiếng còi xe inh ỏi của dòng xe ùn ứ phía sau.

Impact:
- 25-35 ca kẹt/ngày/hầm xe. Vào giờ cao điểm, chỉ cần 1 ca kẹt 3 phút là hầm xe bị ùn ứ 15-20 phương tiện.
- Cư dân ức chế, thường xuyên khiếu nại về chất lượng dịch vụ vận hành bãi xe thông minh.
- Nhân viên soát vé áp lực cao, dễ xảy ra sai sót cho xe ra nhầm mà không kiểm soát được vé.

Success metric:
- Giảm thời gian xử lý một ca không nhận diện được biển số từ 180-240 giây xuống dưới 20 giây.
- Giảm 80% tình trạng ùn tắc kéo dài tại các làn xe giờ cao điểm do lỗi LPR.
- Tỷ lệ đối soát đúng phương tiện đạt 99.5%, tránh thất thoát tài sản hoặc xe lạ ra vào bất hợp pháp.

Non-AI alternative:
- Lắp thêm đèn chiếu sáng và góc camera thứ hai: Cải thiện được một phần chất lượng ảnh nhưng không giải quyết được các trường hợp biển số cong vênh, dính bùn bẩn hoặc xe dán decal.
- Nhân viên bấm nút mở barrier ngay mà không đối soát: Tốc độ rất nhanh nhưng vi phạm nghiêm trọng quy chuẩn an ninh bãi xe, nguy cơ mất trộm phương tiện của cư dân.

AI hypothesis:
Ứng dụng mô hình AI Vision / VLM nhẹ chạy tại local server bãi xe để nhận diện đặc trưng phụ của phương tiện (hãng xe, màu sơn, đặc điểm nhận dạng nổi bật) kết hợp thuật toán so khớp biển số mờ (Fuzzy String Matching). Khi xảy ra lỗi đọc biển số, hệ thống tự động tìm và hiển thị ngay lập tức 3 ảnh xe vào có xác suất khớp cao nhất trong vòng 1 giây; nhân viên chỉ mất 3 giây nhìn màn hình và bấm 1 nút xác nhận.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 180 - 240 giây/ca sự cố

[1 Quét thẻ, LPR fail, barie khóa: 5s]
→ [2 Màn hình báo lỗi không khớp biển số: 5s]
→ [3 Nhân viên gõ mã thẻ/tìm kiếm lịch sử vào: 90s]  <-- bottleneck
→ [4 So sánh bằng mắt 2 ảnh vào - ra: 60s]
→ [5 Gõ ghi chú & bấm override mở barrier: 20s]

FUTURE STATE — 15 - 20 giây/ca sự cố

[1 Quét thẻ, LPR fail: 2s]
→ [2 AI so khớp đặc trưng xe (màu xe, dòng xe, fuzzy OCR) tìm ngay Top 3 ảnh xe vào: 2s]
→ [3 Màn hình hiển thị ngay ảnh đề xuất khớp 95% kèm biển số gợi ý: 1s]
→ [4 Nhân viên nhìn lướt xác nhận & nhấn nút Chấp thuận: 5s]  <-- human boundary
→ [5 Hệ thống tự ghi log đối soát và mở barrier: 2s]

Fallback: Nếu AI không tìm thấy ảnh phù hợp (độ tin cậy < 60%), hệ thống tự động chuyển về giao diện tra cứu thủ công bằng mã thẻ như quy trình truyền thống.
```

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #1 — Phân loại & Định tuyến Thông minh Phản Ánh Cư Dân VinHomes Resident.
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
1. Đây là bài toán cốt lõi phản ánh đúng nhất vai trò công việc hàng ngày của tôi tại VinHomes ("tiếp nhận các vấn đề từ các kênh feedback và đưa ra giải pháp"), có tần suất xảy ra liên tục với 350-450 phản ánh/tuần.
2. Workflow phân loại hiện tại có điểm nghẽn cực kỳ rõ nét ở khâu đọc hiểu ngôn ngữ tự nhiên và gán 18 danh mục, làm lãng phí 2.5 giờ/ngày của đội ngũ trực và khiến cư dân phải chờ trung bình 3 tiếng mới được xử lý.
3. Giải pháp chuyển đổi sang Workflow có AI hỗ trợ có thể chứng minh hiệu quả định lượng ngay lập tức: giảm thời gian phân loại từ 150 phút xuống dưới 20 phút/ngày, nâng độ chính xác lên 93%, tạo ra tác động trực tiếp và rõ ràng lên chỉ số hài lòng của hàng chục nghìn cư dân khu đô thị.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Trong trường hợp cư dân gửi một phản ánh có chứa nhiều nội dung đan xen phức tạp (ví dụ: vừa phản ánh thang máy rung lắc nguy hiểm - khẩn cấp P1, vừa than phiền vệ sinh sảnh bẩn - bình thường P3), workflow của bạn xử lý phân tách ticket như thế nào để tuyệt đối không bị bỏ sót hoặc xử lý trễ rủi ro an toàn?
2. Tại sao lại chọn giải pháp Workflow dùng LLM thay vì chỉ cần một mô hình phân loại văn bản truyền thống (như fine-tuned PhoBERT) kết hợp bộ lọc Rule cứng, liệu chi phí API và độ trễ phản hồi của LLM có thực sự tối ưu trong môi trường vận hành thực tế?
```

**AI phản biện Card (nếu có):**

- Điểm yếu AI chỉ ra: Phản ánh của cư dân thường đi kèm hình ảnh chụp hiện trường (bãi rác, xe đỗ sai, vệt nước nứt tường...) và nội dung text viết rất ngắn kiểu "xem hình giúp tôi", nếu hệ thống chỉ dùng LLM đọc text đơn thuần sẽ bị mất ngữ cảnh và phân loại sai. Thứ hai, với các trường hợp khẩn cấp đe dọa an toàn tính mạng (cháy chập điện, kẹt thang máy), nếu để AI phân loại chậm hoặc gặp ảo giác (hallucination) thì hậu quả vận hành là cực kỳ nghiêm trọng.
- Tôi sửa gì:
  1. Bổ sung cơ chế xử lý đa phương thức (Multimodal VLM): nếu text ngắn dưới 10 từ nhưng có ảnh đính kèm, hệ thống sẽ gọi Vision-Language Model để phân tích nội dung bức ảnh trước khi phân loại danh mục.
  2. Bổ sung bộ lọc quy tắc cứng (Hard-rule Filter): thiết lập danh sách từ khóa khẩn cấp báo động đỏ (cháy, khói, nổ, rò rỉ khí gas, kẹt thang máy, đánh nhau) để ngắt luồng LLM và kích hoạt cảnh báo khẩn cấp tức thì (Alert SOC) cho đội an ninh trực chiến trong vòng 10 giây mà không cần chờ duyệt.

### Self-check nộp phần 01

- [x] Có 5+ problems + top 3 Cards đủ field (Đã hoàn thành 10 problems phong phú và 3 Cards chi tiết đầy đủ 100% các trường)
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback (Cả 3 Cards đều có Current State, Future State, số phút, Human Boundary và Fallback rõ ràng)
- [x] Đã chọn 1 card pitch + câu hỏi challenge (Đã chọn Card #1, viết lời pitch thuyết phục, chuẩn bị 2 câu hỏi challenge hóc búa và phản biện AI)
