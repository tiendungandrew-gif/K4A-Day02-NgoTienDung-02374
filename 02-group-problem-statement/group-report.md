# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên        | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
| --- | ---------------- | ----------- | ---------------------------------------------------------------- |
| 1   | Lương Khánh Toàn | 2A202602836 | Người pitch candidate được chọn (VinWonders)                     |
| 2   | Lương Quang Huy  | 2A202602698 | Workflow + research                                              |
| 3   | Ngô Tiến Dũng    | 2A202602374 | Workflow + research                                              |
| 4   | Đặng Quốc Cường  | 2A202602466 | Workflow + research                                              |
| 5   | Nguyễn Đức Thắng | 2A202602605 | Workflow + research + writer                                     |

**Candidate problem nhóm chọn (1 câu):**

Vào giờ cao điểm tại VinWonders, du khách không biết thời gian chờ của từng trò chơi khi còn ở xa nên đi tới nơi mới thấy hàng dài và chôn chân 30-45 phút, trong khi nhân viên điều phối phải vừa vận hành vừa trả lời ước lượng cảm tính và các khu vực lân cận lại vắng khách.

---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| #   | Người đưa ra | Candidate problem                                                                                      | Người gặp vấn đề                                                               | Điểm nghẽn                                                                                                                                  | Cảm nhận nhanh của nhóm |
| --- | ------------ | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------- |
| 1   | Thắng        | Gom code review/feedback rải rác (PR + Discord) trước khi merge                                        | PM nhóm đồ án                                                                  | Gom feedback từ 2 kênh thành 1 list, 3-4 comment bị sót/lần                                                                                 | 9/10                    |
| 2   | Thắng        | Tìm lại quyết định/lý do thảo luận cũ của nhóm                                                         | Cả nhóm                                                                        | Search keyword Discord không ra vì quyết định lẫn trong chat dài                                                                            | 9/10                    |
| 3   | Thắng        | Tóm tắt/so sánh nhiều nguồn tài liệu tham khảo cho đồ án                                               | PM + member research                                                           | So sánh các nguồn nói khác nhau về cùng một vấn đề                                                                                          | 9/10                    |
| 4   | Toàn         | VinWonders — dự báo luồng khách & quản lý hàng chờ thông minh (vé ảo / virtual queue)                  | Du khách (nhất là gia đình có trẻ nhỏ/người già), nhân viên điều phối trò chơi | Khách không biết thời gian chờ từ xa nên chôn chân 30-45 phút giờ cao điểm; nhân viên vừa vận hành vừa ước lượng cảm tính khi khách hỏi dồn | **10/10**               |
| 5   | Toàn         | Vinhomes — trợ lý cư dân ảo hỗ trợ thủ tục hành chính (thi công nội thất, vé xe tháng, đổi thẻ cư dân) | Cư dân, ban quản lý tòa nhà                                                    | Bước cư dân tự đọc quy định dài + điền form và BQL kiểm tra tính hợp lệ: mất 1-2 ngày làm việc; 35% hồ sơ bị trả lại do thiếu thông tin     | 9/10                    |
| 6   | Toàn         | Xanh SM — tự động đối soát ODO & % pin cuối ca từ ảnh chụp taplo                                       | Tài xế (chờ giao ca), nhân viên vận hành đối soát                              | Nhân viên mở từng ảnh kiểm tra chéo số nhập tay: 5-7 phút/xe × hàng trăm xe/ngày; sai sót nhập liệu 4.5%                                    | 9/10                    |
| 7   | Huy          | Cảm biến báo cháy quá nhạy gây báo động giả tại chung cư/KTX (khói nấu ăn, thắp hương, bụi mịn)        | Bảo vệ trực PCCC, toàn bộ cư dân/sinh viên trong tòa                           | Bảo vệ chạy thang bộ xác minh thủ công 5-7 phút/lần, 3-6 lần/tuần; cư dân "nhờn còi"                                                        | 9/10                    |
| 8   | Huy          | Camera an ninh (motion detection) báo động giả về điện thoại ban đêm do mèo chạy, rèm bay, đèn xe      | Người thuê trọ, chủ cửa hàng nhỏ, người trực kho                               | 15-20 notification/đêm lúc 1-3h sáng, mở app xem video 2-3 phút; tắt thông báo → rủi ro mất trộm thật                                       | 9/10                    |
| 9   | Huy          | Cổng kiểm soát xe (LPR/thẻ từ) lỗi và trễ nhịp giờ cao điểm 7h30 do camera lóa nắng, thẻ ướt           | Hàng trăm sinh viên/nhân viên, bảo vệ bốt trực                                 | Mỗi lượt quét lỗi mất 15-20 giây gõ tay biển số; ùn tắc 50-100m, 10-15 người trễ giờ/sáng                                                   | 9/10                    |
| 10  | Dũng         | Đọc, phân loại thủ công và gán nhãn phản ánh cư dân từ App VinHomes Resident vào 18 danh mục nghiệp vụ | Nhân viên trực CSKH, AI PM, kỹ thuật viên BQL phân khu                         | 350-450 feedback/tuần; nhân viên trực mất 2.5 giờ/ngày (bấm giờ 3 ngày: 140', 165', 150')                                                   | 9/10                    |
| 11  | Dũng         | Tổng hợp số liệu vận hành tuần của các giải pháp AI/IoT từ nhiều dashboard rời rạc để làm báo cáo      | AI PM, Trưởng bộ phận Vận hành công nghệ, GĐ Khối Vận hành                     | Mỗi sáng thứ Hai mất 100-120 phút export từ 3 hệ thống (Grafana, Jira, Portal bãi xe) + viết narrative 15 slide                             | 9/10                    |
| 12  | Dũng         | Nhân viên soát vé hầm xe đối soát thủ công khi hệ thống LPR không nhận diện được biển số               | Nhân viên soát vé, KTV vận hành bãi đỗ, cư dân đi xe                           | 25-35 sự cố/ngày/hầm xe; mỗi ca kẹt 3-5 phút đối chiếu ảnh, ùn 15-20 xe khung 7h30-8h15                                                     | 9/10                    |
| 13  | Cường        | Phát hiện người chưa đội mũ bảo hộ: người phụ trách phải tự xem camera hoặc đi kiểm tra từng khu vực   | Người phụ trách an toàn, người quản lý khu vực, người làm việc                 | Chưa có baseline — dự kiến bấm giờ 3 ca (thời gian xem camera + số ca phát hiện được)                                                       | 9/10                    |
| 14  | Cường        | Báo tin tình huống nguy hiểm qua chat thường thiếu vị trí/thời điểm nên phải hỏi lại                   | Người phụ trách an toàn, người quản lý khu vực, người gửi tin                  | Chưa có baseline — dự kiến xem 10 báo cáo: số báo thiếu thông tin + thời gian hỏi bổ sung                                                   | 9/10                    |
| 15  | Cường        | Làm báo cáo an toàn cuối tuần: gom checklist, ảnh, ghi chú từ nhiều nơi                                | Người phụ trách an toàn, quản lý                                               | Chưa có baseline — dự kiến bấm giờ 2 lần làm báo cáo + đếm số nguồn phải mở                                                                 | 9/10                    |

### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster                                                        | Candidates included                                                                                                                                                       | Pattern chung                                                                                                     | Ghi chú                                                                                                          |
| -------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| A — Lọc cảnh báo từ camera/cảm biến: thật hay giả?             | #7 báo cháy giả, #8 camera motion giả, #13 mũ bảo hộ                                                                                                                      | Thiết bị đã bắn tín hiệu nhưng tỷ lệ báo giả cao, con người phải đi xác minh từng lần rồi dần "nhờn cảnh báo"     | Cụm đông nhất và có cùng rủi ro: giảm báo giả quá tay thì bỏ sót ca thật                                         |
| B — Đọc/đối soát dữ liệu bằng thị giác tại cổng và giao ca     | #6 ODO/pin taplo, #9 cổng LPR lỗi, #12 hầm xe LPR fail                                                                                                                    | Máy đã đọc được phần lớn, nhưng ca lỗi (mờ, lóa, ướt) đẩy ngược về người và gây ùn tắc tại chỗ                    | Bài toán OCR/VLM khá rõ; giá trị nằm ở xử lý phần đuôi ca lỗi                                                    |
| C — Gom thông tin rời rạc thành việc cần làm hoặc báo cáo      | #1 gom code review, #2 quyết định cũ, #3 so sánh nguồn, #5 thủ tục hành chính, #10 phân loại phản ánh, #11 báo cáo tuần, #14 báo tin thiếu thông tin, #15 báo cáo an toàn | Thông tin nằm ở nhiều kênh/định dạng, người làm phải tự đọc, phân loại rồi viết lại cho người khác dùng           | Cụm nhiều bài nhất; đa số fix được một phần bằng rule (form bắt buộc, một kênh duy nhất, template)               |
| D — Dự báo nhu cầu & điều phối luồng người theo thời gian thực | #4 VinWonders hàng chờ                                                                                                                                                    | Không phải xử lý thông tin đã có, mà là dự đoán trạng thái sắp tới rồi điều phối người trước khi tắc nghẽn xảy ra | Chỉ có 1 bài, nhưng cũng vì vậy mà nó là bài duy nhất bắt nhóm phải nghĩ về dự báo + điều phối thay vì phân loại |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate                                   | Vì sao vào shortlist (2-3 ý)                                                                                                                                                                                                    | Rủi ro / điều chưa rõ                                                                                                                       |
| ------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| #4 VinWonders — dự báo luồng khách & vé ảo  | Impact rộng nhất (hàng nghìn du khách/ngày, ảnh hưởng trực tiếp trải nghiệm và doanh thu); workflow 5 bước vẽ được rõ; là bài duy nhất so sánh được đầy đủ Rule (bảng giờ chờ nhập tay) / Workflow (dự báo + điều phối) / Agent | Nhóm không có quyền truy cập camera, dữ liệu vé hay nhân sự VinWonders; con số 30-45 phút là ước lượng từ trải nghiệm cá nhân, chưa bấm giờ |
| #10 Phân loại phản ánh cư dân VinHomes      | Bằng chứng mạnh nhất: 350-450 feedback/tuần, đã bấm giờ 3 ngày (140', 165', 150'); Dũng là người trực tiếp phụ trách nên hiểu domain sâu                                                                                        | Cư dân viết cụt hoặc một phản ánh chứa nhiều vấn đề đan xen; dữ liệu thật thuộc hệ thống nội bộ, khó đưa ra khỏi công ty                    |
| #1 Gom code review feedback trước khi merge | Actor ngồi ngay trong nhóm, làm 2 lần/tuần nên workflow đọc được từng bước; có baseline bấm giờ 60 phút và metric kép (thời gian + số comment sót); dữ liệu nằm trên GitHub của chính nhóm                                      | Baseline mới từ 1 người (n=1); rule "mọi feedback vào PR" có thể đã giải phần lớn vấn đề                                                    |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate                     | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
| ----------------------------- | -------: | ----------: | ---------------: | -------------: | ------------: | -----------------: | ---------------: | ---: |
| #4 VinWonders — hàng chờ      |        4 |           4 |                2 |              4 |             2 |                  5 |                3 |   24 |
| #10 Phân loại phản ánh cư dân |        5 |           5 |                5 |              5 |             3 |                  4 |                5 |   32 |
| #1 Gom code review feedback   |        5 |           5 |                4 |              5 |             5 |                  5 |                5 |   34 |

Giải thích các điểm đáng chú ý (ép nhóm nói rõ vì sao cho 5 / cho 3):

- VinWonders chỉ được **2 điểm "Pain có evidence"**: con số chờ 30-45 phút là ước lượng từ trải nghiệm đi chơi của Toàn, nhóm chưa bấm giờ lần nào và chưa hỏi du khách thật.
- VinWonders cũng chỉ được **2 điểm "Làm trong lab"**: nhóm không có quyền truy cập camera, dữ liệu bán vé hay nhân sự điều phối của VinWonders, nên không thể chạy thử trong buổi lab.
- Ngược lại VinWonders được **5 điểm "So sánh R/W/A được"** vì đây là bài duy nhất có đủ ba mức rõ ràng: bảng giờ chờ nhập tay (Rule), dự báo + điều phối (Workflow), và một agent điều phối toàn công viên (Agent) để loại bỏ có lý do.
- #1 và #10 được điểm cao hơn chủ yếu nhờ "Pain có evidence" và "Làm trong lab", vì actor nằm ngay trong nhóm và dữ liệu sẵn có.

**Candidate nhóm chọn (1 bài duy nhất):**

```text
#4 — VinWonders: dự báo thời gian chờ theo thời gian thực và điều phối luồng khách
bằng vé ảo tại các trò chơi đông khách.
```

**Vì sao chọn (4-5 câu):**

```text
Nhóm chọn VinWonders dù bài này KHÔNG có điểm tổng cao nhất, và ghi rõ ở đây là một
lựa chọn có đánh đổi chứ không phải kết quả của bảng điểm.
Lý do thứ nhất là độ lớn của tác động: một trò chơi đông khách ảnh hưởng tới hàng
nghìn du khách mỗi ngày, trong khi hai bài còn lại tối ưu công việc của vài người.
Lý do thứ hai là giá trị học tập: đây là bài duy nhất trong 15 candidate không phải
dạng "phân loại thông tin đã có" mà là "dự báo trạng thái sắp tới rồi điều phối
người", nên buộc nhóm phải phân biệt rõ Rule, Workflow và Agent thay vì mặc định
chọn Workflow.
Lý do thứ ba là boundary rất sạch và dễ lập luận: AI chỉ ước lượng thời gian chờ và
gợi ý phân luồng, còn quyền cho trò chơi chạy hay dừng vì lý do an toàn/thời tiết
vẫn hoàn toàn thuộc về kỹ sư vận hành.
Đổi lại, nhóm chấp nhận rằng bài này yếu nhất về bằng chứng và khả năng thử trong
lab — và chính điều đó quyết định kết luận cuối ở Phase 6 là Not Yet chứ không Go.
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
#10 Phân loại phản ánh cư dân VinHomes: đây là bài có bằng chứng tốt nhất và Dũng
hiểu domain sâu nhất, nhưng dữ liệu phản ánh cư dân là dữ liệu nội bộ có thông tin
cá nhân, nhóm không thể đưa ra ngoài để thử trong lab. Bài này cũng khá gần với
mẫu "AI phân loại văn bản" quen thuộc nên ít buộc nhóm phải tranh luận về mức giải
pháp.

#1 Gom code review feedback: điểm cao nhất vì actor ngồi ngay trong nhóm, nhưng
impact chỉ gói trong một nhóm đồ án 5 người. Ngoài ra nhóm thấy khả năng cao là
rule "mọi feedback phải nằm trong PR comment" đã giải được phần lớn vấn đề, nên
phần AI còn lại hơi mỏng để làm bài chính.

Cụm A (báo cháy giả, camera báo giả, mũ bảo hộ): đúng pain và rất đáng làm, nhưng cả
ba đều là bài toán an toàn tính mạng, nơi chi phí của một ca bỏ sót là rất lớn. Nhóm
thấy chưa đủ dữ liệu và chưa đủ thời gian trong lab để lập luận nghiêm túc về ngưỡng
đánh đổi giữa báo giả và bỏ sót.

Cụm B (LPR, ODO/taplo): bài toán OCR/VLM khá rõ ràng về kỹ thuật, nhưng phần quyết
định nằm ở hạ tầng và độ trễ (<2 giây để mở barrier) hơn là ở thiết kế workflow, nên
ít chỗ để nhóm thực hành phần Problem Statement.
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
Bất đồng lớn nhất: bảng điểm ở 3.4 cho VinWonders thấp nhất (24/35) nhưng nhóm lại
chọn bài này.

Ý kiến phản đối: chọn một bài mà nhóm không có dữ liệu, không có actor và không thử
được trong lab là đi ngược nguyên tắc "problem first, evidence first"; hai bài kia
có số đo thật và làm được ngay.

Ý kiến ủng hộ: tác động và giá trị học tập của bài dự báo + điều phối lớn hơn hẳn;
nếu chọn bài dễ đo thì nhóm sẽ lặp lại đúng một mẫu AI phân loại văn bản đã quá quen.

Cách chốt: nhóm giữ VinWonders làm bài phân tích, nhưng ràng buộc hai điều —
(1) không được kết luận Go nếu chưa có baseline đo thật, và
(2) phải thiết kế được một cách validate khả thi với nguồn lực sinh viên.
Cả hai ràng buộc này được phản ánh trực tiếp ở Phase 4 và ở quyết định cuối.
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

> Vì nhóm không tiếp cận được nhân sự VinWonders, ba nguồn khả thi với sinh viên là: (a) hỏi bạn bè/người quen đã đi VinWonders hoặc công viên giải trí trong 6 tháng qua; (b) đọc review công khai trên Google Maps/mạng xã hội về thời gian xếp hàng; (c) lấy dữ liệu thời gian chờ công khai của các công viên lớn qua Queue-Times API (xem 4.2) để biết phân bố thời gian chờ giờ cao điểm thực tế trông như thế nào.
>
> Câu hỏi cho interview/survey:
>
> 1. Lần gần nhất bạn đi công viên giải trí là khi nào, bạn chờ trò chơi lâu nhất khoảng bao lâu?
> 2. Bạn biết thời gian chờ đó **trước khi** đi tới trò chơi hay chỉ biết khi đã đến nơi?
> 3. Đã bao giờ bạn xếp hàng rồi bỏ giữa chừng chưa? Vì sao?
> 4. Nếu app báo "trò chơi này chờ 40 phút, trò chơi kia chờ 10 phút", bạn có đổi lịch không?
> 5. Bạn có tin con số app đưa ra không, và sai bao nhiêu phút thì bạn thấy khó chịu?

| Nguồn                                                     |                                                                                                                                       Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | Tín hiệu phản bác                                                                                                                                                                                                                                                                                                | Nhóm sửa problem thế nào                                                                                                                                                                                                                                                                                                               |
| --------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------: | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Dữ liệu công khai — Queue-Times API** (đã làm, số thật) | 69 attraction: Tokyo Disneyland (31 trò đang mở) + Hong Kong Disneyland (38 trò đang mở), lát cắt lúc `2026-09-12T05:41Z` = 14:41 giờ Tokyo, thứ Bảy | **Tải lệch rất mạnh giữa các trò trong cùng một thời điểm.** Tokyo Disneyland: thấp nhất 0', cao nhất **100'** (_Enchanted Tale of Beauty and the Beast_ và _The Happy Ride with Baymax_), median 15', trung bình 25,5'. Cùng lúc đó: 11/31 trò chờ ≥30' **nhưng 13/31 trò chỉ chờ ≤10'**. Hong Kong Disneyland cùng thời điểm: 0–60', trung bình 26' (cao nhất _Toy Soldier Parachute Drop_ 50', _Meet LinaBell_ 60'). → Chênh lệch giữa trò đông nhất và trò vắng nhất lên tới **6–7 lần**, tức luôn tồn tại lựa chọn vắng khách ngay bên cạnh điểm nóng. | (1) **Baseline 30-45' của nhóm không phải mức phổ biến** — median thật chỉ 15', và chỉ ~1/3 số trò chạm ngưỡng 30'. (2) Cả hai công viên này **đã công bố wait time công khai** (chính vì vậy API mới có dữ liệu) — tức phần "khách không biết trước phải chờ bao lâu" đã được giải bằng **Rule**, không cần AI. | (1) Hạ phạm vi baseline: chỉ nói "30-45' **tại nhóm trò hot giờ cao điểm**", không nói cho toàn công viên. (2) Đổi trọng tâm problem: không phải "giảm thời gian chờ" (AI không tạo thêm công suất) mà là **"làm khách thấy được lựa chọn 10' đang có ngay lúc đó"**. (3) Xác nhận lớp Rule phải đi trước — khớp với kết luận Phase 6. |
| Interview _(chưa thu — công cụ đã sẵn ở dưới)_            |                                                                               Mục tiêu 3 người đã đi VinWonders/công viên giải trí trong 6 tháng qua | [ĐIỀN QUOTE NGUYÊN VĂN sau khi hỏi — không viết diễn giải thay quote]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | [ĐIỀN]                                                                                                                                                                                                                                                                                                           | [ĐIỀN]                                                                                                                                                                                                                                                                                                                                 |
| Survey / poll trong lớp _(chưa thu)_                      |                                                                                                                                 Mục tiêu 10-15 người | [ĐIỀN]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | [ĐIỀN]                                                                                                                                                                                                                                                                                                           | [ĐIỀN]                                                                                                                                                                                                                                                                                                                                 |

> Cách kiểm lại số ở hàng 1 (ai cũng chạy được, không cần key):
> `https://queue-times.com/parks/274/queue_times.json` (Tokyo Disneyland) và `https://queue-times.com/parks/31/queue_times.json` (Hong Kong Disneyland). Dữ liệu cập nhật mỗi 5 phút nên chạy lại sẽ ra lát cắt khác — đây là số tại đúng thời điểm ghi trong bảng. Điều kiện sử dụng yêu cầu ghi _Powered by Queue-Times.com_.

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Tại cùng một thời điểm trong giờ cao điểm, thời gian chờ giữa các trò trong cùng một
công viên chênh nhau 6-7 lần (0-100 phút, median 15 phút). Nghĩa là ngay cạnh mỗi
điểm nóng luôn có một trò vắng — pain KHÔNG phải "công viên không đủ chỗ" mà là
"khách không nhìn thấy lựa chọn vắng đang có sẵn". Đây là bài toán THÔNG TIN và
PHÂN LUỒNG, không phải bài toán công suất.

Hệ quả trực tiếp làm nhóm sửa problem:
Cả Tokyo và Hong Kong Disneyland đều đã công bố wait time công khai bằng lớp Rule —
và chính điều đó tạo ra bộ dữ liệu nhóm vừa dùng. Vậy phần lớn giá trị đến từ việc
CÔNG BỐ con số, không phải từ việc DỰ BÁO nó. Phần AI chỉ còn một chỗ hẹp để chứng
minh mình: con số công bố phải chính xác tới mức khách dám đổi lịch cả buổi.

CÒN LÀ GIẢ THUYẾT, CHƯA KIỂM (chờ interview/survey):
Khách khó chịu vì "chờ lâu" hay vì "không biết trước sẽ chờ bao lâu"? Và sai bao
nhiêu phút thì khách mất niềm tin vào con số? Hai câu này quyết định mức Rule đã đủ
hay chưa, nên phải hỏi người thật trước khi kết luận.
```

**Công cụ thu thập cho 2 hàng còn thiếu** (dùng đúng 5 câu ở phần dẫn trên, ghi lại theo mẫu này):

| #   | Người trả lời (tên/vai) | Đi công viên nào, khi nào | Chờ lâu nhất bao lâu (phút) | Biết trước hay tới nơi mới biết? | Đã bỏ hàng giữa chừng chưa? Vì sao | Sẽ đổi lịch nếu app báo 40' vs 10'? | Sai bao nhiêu phút thì khó chịu? |
| --- | ----------------------- | ------------------------- | --------------------------: | -------------------------------- | ---------------------------------- | ----------------------------------- | -------------------------------: |
| 1   |                         |                           |                             |                                  |                                    |                                     |                                  |
| 2   |                         |                           |                             |                                  |                                    |                                     |                                  |
| 3   |                         |                           |                             |                                  |                                    |                                     |                                  |

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case                                                                | Link                                                            | Họ giải quyết bước nào?                                                                                                             | Điểm mạnh                                                                                   | Khoảng trống / rủi ro                                                                                                                | Bài học cho nhóm                                                                                                            |
| ---------------------------------------------------------------------------------- | --------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------- |
| Disney Virtual Queue                                                               | https://disneyworld.disney.go.com/guest-services/virtual-queue/ | Bước xếp hàng vật lý: khách đăng ký qua app và nhận khung giờ quay lại thay vì đứng chờ                                             | Đã vận hành ở quy mô rất lớn; khách được giải phóng khỏi hàng chờ                           | Disney nói rõ virtual queue chỉ bật cho một số trải nghiệm và theo từng thời điểm, không phải bật cho mọi trò chơi                   | Vé ảo là công cụ điều phối có chọn lọc, không phải thứ áp cho toàn công viên                                                |
| Disney Lightning Lane                                                              | https://disneyworld.disney.go.com/lightning-lane-passes/        | Bước xếp hàng: bán quyền vào làn chờ ngắn hơn                                                                                       | Giải pháp thuần vận hành/thương mại, không cần AI                                           | Chỉ dịch chuyển hàng chờ chứ không giảm tổng thời gian chờ; khách không trả tiền có thể chờ lâu hơn                                  | Có phương án phi-AI thật sự tồn tại — nhóm bắt buộc phải so sánh với nó, và phải cẩn thận với công bằng giữa các nhóm khách |
| Queue-Times.com API                                                                | https://queue-times.com/en-US/pages/api                         | Bước thu thập và công bố thời gian chờ: cung cấp wait time trực tiếp và lịch sử cho hơn 80 công viên, cập nhật mỗi 5 phút, miễn phí | Cho nhóm dữ liệu thật để dựng và kiểm mô hình dự báo mà không cần quyền truy cập VinWonders | Là dữ liệu công viên nước ngoài, hành vi khách và quy mô khác VinWonders; điều kiện sử dụng yêu cầu ghi "Powered by Queue-Times.com" | Đây là chìa khóa để nhóm validate phần dự báo trước khi xin dữ liệu thật — thay đổi hẳn kế hoạch ở Phase 6                  |
| Universal Orlando Virtual Line (hướng dẫn bên thứ ba, không phải trang chính thức) | https://orlandoinformer.com/universal/virtual-lines/            | Cùng pattern vé ảo theo khung giờ, bật/tắt theo nhu cầu từng ngày                                                                   | Cho thấy pattern này phổ biến chứ không phải đặc thù một hãng                               | Nguồn bên thứ ba nên thông tin có thể lệch so với vận hành thực tế                                                                   | Trước khi trích số từ nguồn này phải kiểm lại trên trang chính thức của Universal                                           |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
Các công viên lớn giải bài toán này bằng hai lớp tách biệt: một lớp THÔNG TIN (công
bố thời gian chờ) và một lớp ĐIỀU PHỐI (vé ảo, làn ưu tiên) — và lớp điều phối chủ
yếu là rule/thương mại chứ không phải AI.
Không nên build một agent tự điều phối toàn công viên; phần đáng làm bằng AI chỉ là
ước lượng thời gian chờ cho chính xác hơn con số nhân viên ước lượng bằng mắt.
Phát hiện quan trọng nhất: Queue-Times cung cấp dữ liệu wait time thật và miễn phí
cho hơn 80 công viên, nên nhóm có thể kiểm giả thuyết "dự báo đạt sai số dưới 5
phút" ngay từ bây giờ, trước khi cần bất kỳ quyền truy cập nào từ VinWonders.
```

> Lưu ý: không dùng số liệu AI đưa nếu không verify được link chính thức. Ghi rõ giả định chưa chắc.
>
> Giả định chưa chắc của nhóm: (1) con số chờ 30-45 phút là ước lượng cá nhân, chưa bấm giờ tại VinWonders; (2) các mục tiêu "tăng CSAT 25%" và "tăng 15% doanh thu F&B" trong bản pitch ban đầu chưa có nguồn nào kiểm chứng — nhóm đưa xuống thành giả thuyết, không dùng làm success metric; (3) chưa biết VinWonders hiện đã có camera đếm người hay chưa.

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

```text
CURRENT STATE — 5 bước, 30-45 phút chờ vật lý/trò chơi vào giờ cao điểm

[1 Khách chọn trò chơi và đi bộ tới: 5-10' - du khách]
   (không có thông tin thời gian chờ khi còn ở xa)
→ [2 Tới chân trò chơi mới nhìn thấy hàng, ước lượng bằng mắt: 1-2' - du khách]
→ [3 Khách hỏi dồn nhân viên "bao lâu nữa tới lượt": 10-20 giây/lượt - ride operator]
   (nhân viên vừa vận hành vừa trả lời ước lượng cảm tính)
→ [4 Xếp hàng vật lý: 30-45' giờ cao điểm - du khách]   <-- bottleneck
→ [5 Chơi xong, lặp lại từ bước 1 cho trò tiếp theo]

Handoff yếu: thông tin về độ dài hàng chỉ tồn tại trong đầu nhân viên tại chỗ và
trong mắt người đang đứng xếp hàng; không chảy ngược ra cho khách đang ở xa quyết
định, cũng không chảy lên cho người điều phối toàn công viên cân bằng tải.
```

| Bước | Actor                          | Input                                  | Output                         | Thời gian / tần suất          | Ghi chú (handoff? bottleneck?)                                                   |
| ---- | ------------------------------ | -------------------------------------- | ------------------------------ | ----------------------------- | -------------------------------------------------------------------------------- |
| 1    | Du khách                       | Bản đồ, app (không có wait time từ xa) | Quyết định đi tới trò chơi nào | 5-10' đi bộ, nhiều lần/ngày   | Quyết định trong tình trạng mù thông tin — **nguyên nhân gốc**                   |
| 2    | Du khách                       | Hàng chờ nhìn thấy trước mắt           | Quyết định xếp hàng hay bỏ đi  | 1-2'                          | "Tiến thoái lưỡng nan": đã đi bộ tới nơi nên tiếc, bỏ thì phí công               |
| 3    | Du khách → nhân viên điều phối | Câu hỏi của khách                      | Con số ước lượng cảm tính      | 10-20 giây/lượt, lặp liên tục | Handoff xấu: nhân viên phải chia sự chú ý giữa vận hành an toàn và trả lời khách |
| 4    | Du khách                       | —                                      | Được lên trò chơi              | 30-45' giờ cao điểm           | **Bottleneck.** Khách chôn chân dưới nắng/mưa, bỏ lỡ show và giờ ăn              |
| 5    | Du khách                       | —                                      | Quay lại bước 1                | Lặp 4-6 lần/ngày              | Khu vực lân cận vắng khách trong khi điểm nóng quá tải                           |
| 6    | —                              |                                        |                                |                               |                                                                                  |
| 7    | —                              |                                        |                                |                               |                                                                                  |

**Bottleneck chính (2-3 câu):**

```text
Thời gian mất nhiều nhất nằm ở bước 4 (xếp hàng vật lý 30-45 phút), nhưng nguyên
nhân gốc nằm ở bước 1: khách phải chọn trò chơi khi chưa biết trò nào đang đông.
Nếu chỉ tấn công bước 4 (mở thêm làn, tăng công suất) thì tốn hạ tầng; nếu đưa được
thông tin thời gian chờ ra trước bước 1 thì khách tự phân luồng và tải giữa các khu
vực cân bằng hơn.
Bước 3 không phải bottleneck về thời gian nhưng là điểm rủi ro an toàn: nhân viên bị
phân tán khỏi việc vận hành trò chơi.
```

### 5.2. Future workflow bản nhóm

Phải nhìn ra 5 thứ: bước nào máy (Rule), bước nào AI, bước nào người, boundary ở đâu, fallback khi AI sai.

```text
FUTURE STATE — mục tiêu chờ vật lý dưới 10-12 phút tại trò chơi áp dụng vé ảo

[1 Đếm người trong hàng bằng camera (ẩn danh) + lấy dữ liệu vé, lịch show, thời tiết:
   liên tục - máy/rule]
→ [2 AI dự báo thời gian chờ động cho từng trò chơi: cập nhật mỗi 5' - AI]
→ [3 Rule hiển thị: đẩy wait time lên app + màn hình LED tại ngã rẽ chính;
   nếu wait vượt ngưỡng thì mở vé ảo và gợi ý trò chơi vắng hơn: tức thì - rule]
→ [4 Nhân viên điều phối xác nhận, ghi đè hoặc tắt hiển thị khi có sự cố/thời tiết:
   khi cần - người]  <-- human boundary
→ [5 Khách quay lại theo khung giờ vé ảo, chờ vật lý dưới 10-12']

Boundary:
- AI chỉ ước lượng thời gian chờ và gợi ý phân luồng.
- AI KHÔNG quyết định cho trò chơi chạy hay dừng (an toàn cơ học, thời tiết là quyền
  của kỹ sư vận hành), KHÔNG từ chối khách, KHÔNG nhận diện khuôn mặt — camera chỉ
  đếm số người một cách ẩn danh.

Fallback:
- Nếu camera lỗi hoặc sai số dự báo vượt ngưỡng 2 chu kỳ liên tiếp → app hiện "đang
  cập nhật" và quay về cách cũ: nhân viên nhập thời gian chờ bằng tay mỗi 15 phút.
- Nếu hệ thống vé ảo trục trặc → đóng vé ảo, mọi khách quay lại xếp hàng thường,
  không ai bị mất lượt.

Bottleneck mới:
Bước 4 — thông lượng thật của trò chơi (bao nhiêu khách/giờ) không đổi. AI chỉ phân
phối lại thời gian chờ chứ không tạo thêm chỗ, nên phải nói thẳng điều này để không
hứa quá.
```

**Before/after impact:**

| Metric                                    |                                               Trước |                                                                                             Sau kỳ vọng | Cách đo                                                                  |
| ----------------------------------------- | --------------------------------------------------: | ------------------------------------------------------------------------------------------------------: | ------------------------------------------------------------------------ |
| Thời gian chờ vật lý tại trò chơi áp dụng |                30-45 phút (ước lượng, chưa bấm giờ) |                                                                                         Dưới 10-12 phút | Bấm giờ mẫu 30 khách/ngày trong 3 ngày cao điểm, trước và sau            |
| Khách biết thời gian chờ trước khi đi tới |                                               Không |                                                                               Có, trên app + LED ngã rẽ | Khảo sát 30 khách: "bạn biết trước khi đi tới hay chỉ biết khi đến nơi?" |
| Sai số dự báo thời gian chờ (MAE)         | Ước lượng cảm tính của nhân viên, chưa ai đo sai số |                                                                                             Dưới 5 phút | So con số hiển thị với thời gian chờ thật bấm giờ được                   |
| Số lượt khách hỏi nhân viên "bao lâu nữa" |                                   Liên tục trong ca |                                                                                             Giảm rõ rệt | Nhân viên đếm tay trong 2 ca trước và 2 ca sau                           |
| Risk mới                                  |                                            Không có | Khách tin con số sai rồi bỏ lỡ show; camera đếm người gây lo ngại riêng tư; vé ảo tạo cảm giác bất công | Đếm số khiếu nại liên quan đến sai giờ và vé ảo                          |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field              | Nội dung                                                                                                                                                                          |
| ------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Actor**          | Du khách VinWonders vào giờ cao điểm, đặc biệt nhóm đi cùng trẻ nhỏ và người già. Actor thứ hai là nhân viên điều phối tại trò chơi, người phải trả lời khách trong lúc vận hành. |
| **Workflow**       | Khách chọn trò chơi và đi bộ tới, đến nơi mới thấy hàng, hỏi nhân viên thời gian chờ, xếp hàng 30-45 phút, rồi lặp lại cho trò tiếp theo.                                         |
| **Bottleneck**     | Thời gian mất nhiều nhất ở bước xếp hàng, nhưng nguyên nhân gốc là khách phải chọn trò chơi khi chưa biết trò nào đang đông, nên không thể tự phân luồng.                         |
| **Impact**         | Khách chôn chân 30-45 phút dưới nắng mưa, bỏ lỡ show và giờ ăn; các khu lân cận vắng khách trong khi điểm nóng quá tải; nhân viên bị phân tán khỏi việc vận hành an toàn.         |
| **Success Metric** | Giảm thời gian chờ vật lý tại trò chơi áp dụng từ 30-45 phút xuống dưới 10-12 phút, và sai số dự báo thời gian chờ dưới 5 phút.                                                   |
| **Boundary**       | Làm: ước lượng thời gian chờ, hiển thị cho khách, gợi ý phân luồng và cấp vé ảo. Không làm: quyết định dừng/chạy trò chơi, từ chối khách, nhận diện khuôn mặt.                    |

**Câu hỏi AI phản biện v0 (nếu có):**

- Field nào mơ hồ: (1) "Impact" đang mô tả cảm giác chứ chưa có số nào được nhóm tự đo; (2) "Success Metric" lấy mốc 30-45 phút làm baseline trong khi baseline đó chỉ là ước lượng cá nhân; (3) "Bottleneck" chưa nói rõ AI có làm tăng thông lượng trò chơi không — nếu không thì hứa "giảm còn 10-12 phút" cho mọi khách là hứa sai.
- Tôi sửa gì: ở v1 ghi thẳng baseline là ước lượng chưa kiểm chứng và phải đo lại trước khi dùng; tách rõ metric chính (sai số dự báo — thứ AI thực sự chịu trách nhiệm) với metric kết quả (thời gian chờ — phụ thuộc cả vận hành); và bổ sung một câu nói rõ hệ thống phân phối lại thời gian chờ chứ không tạo thêm công suất.

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [x] Thấp (có đúng/sai rõ) / [ ] Cao (nhiều cách trả lời vẫn OK) — Vì sao: dự báo thời gian chờ có đáp án đúng kiểm được. Chờ 12 phút hay 40 phút là sự thật đo bằng đồng hồ, nên mọi con số AI đưa ra đều đối chiếu được với thực tế.
- Độ phức tạp: [x] Cao (3+ bước/nguồn, phụ thuộc nhau) / [ ] Thấp (1-2 bước) — Vì sao: cần ít nhất 4 nguồn (camera đếm người, dữ liệu vé, lịch show, thời tiết) và các bước phụ thuộc nhau — phải đếm được người mới dự báo được, dự báo xong mới quyết định có mở vé ảo hay không.

**Bài toán nhóm nằm ở ô nào:**

```text
Độ phức tạp cao + độ mơ hồ thấp → ô "Workflow điều phối nhiều bước rõ ràng, chưa
chắc cần Agent".
```

**Vì sao (2-3 câu):**

```text
Thứ tự các bước là cố định và biết trước: đếm người → dự báo → hiển thị/cấp vé ảo →
người xác nhận. Không có bước nào AI phải tự chọn xem làm gì tiếp theo.
Vì độ mơ hồ thấp nên mỗi lần dự báo đều chấm điểm được bằng thời gian chờ thật, tức
là hệ thống có vòng phản hồi rõ ràng — đây là dấu hiệu của một Workflow đo được chứ
không phải một Agent cần tự xoay xở.
```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức          | Phương án cho bài toán nhóm                                                                                                                                | Khi nào đủ                                                                                                                 | Rủi ro                                                                                                                     | Chọn? (Dùng cho bước nào?)                                                                             |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ |
| **Rule**     | Nhân viên nhập thời gian chờ bằng tay mỗi 15 phút, hiển thị lên app và màn hình LED tại ngã rẽ; vé ảo mở theo khung giờ cố định đã định trước              | Đủ nếu pain thật chỉ là "khách không biết trước phải chờ bao lâu", và mật độ khách không biến động quá nhanh trong 15 phút | Số liệu trễ và vẫn là ước lượng bằng mắt; tốn thêm việc cho nhân viên đang bận vận hành                                    | **Có — làm lớp nền bắt buộc.** Đây cũng là phương án phải thử trước để biết AI còn thêm được bao nhiêu |
| **Workflow** | Camera đếm người ẩn danh + dữ liệu vé/lịch show/thời tiết → mô hình dự báo thời gian chờ → rule hiển thị và mở vé ảo → nhân viên điều phối xác nhận/ghi đè | Hợp khi cần cập nhật liên tục nhiều trò chơi cùng lúc và cần đủ chính xác để khách dám tin mà đổi lịch                     | Dự báo sai làm khách bỏ lỡ show rồi mất niềm tin vào app; camera gây lo ngại riêng tư; phụ thuộc hạ tầng                   | **Chọn**                                                                                               |
| **Agent**    | Agent tự theo dõi toàn công viên, tự đổi giờ show, tự cấp và thu hồi vé ảo, tự nhắn tin điều hướng từng khách                                              | Chỉ cần nếu hệ thống phải tự lập kế hoạch lại nhiều ràng buộc đan xen theo thời gian thực và tự chọn công cụ               | Chạm vào vận hành và an toàn của cả công viên; một quyết định sai lan ra hàng nghìn khách; rất khó giải thích khi có sự cố | **Chưa chọn**                                                                                          |

**5 câu hỏi chốt (trả lời câu đầy đủ):**

1. **Rule có giải được 70-80% case không?** Rất có thể, và nhóm chưa chứng minh được là không. Nếu pain thật đúng là "không biết trước phải chờ bao lâu" thì chỉ cần hiển thị con số nhân viên nhập tay là khách đã tự phân luồng được. Phần AI chỉ thêm giá trị khi con số cần chính xác tới mức khách dám đổi lịch cả buổi, và khi số trò chơi nhiều tới mức nhập tay không xuể.
2. **Các bước có đi thẳng một đường không hay phải rẽ nhánh?** Đi thẳng một đường: đếm người → dự báo → hiển thị → nhân viên xác nhận. Nhánh duy nhất là "wait time có vượt ngưỡng mở vé ảo không", mà đó là một rule ngưỡng đơn giản do con người đặt, không phải AI tự quyết.
3. **Có thật sự cần Agent tự lập kế hoạch + gọi tool không?** Không. Các bước và nguồn dữ liệu đều cố định và biết trước. Cho agent quyền tự đổi lịch show hay tự điều hướng khách là mở rộng phạm vi sang vận hành và an toàn, trong khi giá trị tăng thêm chưa được chứng minh.
4. **Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu?** Khách phát hiện đầu tiên và phát hiện rất nhanh — app báo 10 phút mà chờ 40 phút thì họ biết ngay, nhưng lúc đó thiệt hại đã xảy ra. Vì vậy hệ thống phải tự giám sát sai số bằng cách đối chiếu dự báo với thời gian chờ thật liên tục, và nhân viên điều phối có quyền ghi đè hoặc tắt hiển thị ngay tại chỗ.
5. **Có hạ được từ Agent → Workflow → Rule không?** Có, và đường hạ cấp rất sạch: bỏ mô hình dự báo thì vẫn còn camera đếm người cho con số thô; bỏ luôn camera thì quay về nhân viên nhập tay mỗi 15 phút — tức là quay về đúng mức Rule mà vẫn giữ được phần lớn giá trị thông tin cho khách.

**Mức chọn:**

```text
Workflow (đặt trên nền một lớp Rule bắt buộc phải có trước).
```

**Vì sao chọn (3-4 câu):**

```text
Bài toán cần gộp 4 nguồn dữ liệu và cập nhật liên tục cho nhiều trò chơi cùng lúc,
nên một mình rule nhập tay khó theo kịp khi công viên đông.
Phần AI được giao đúng một việc hẹp và đo được: ước lượng thời gian chờ chính xác
hơn con số nhân viên đoán bằng mắt, với mục tiêu sai số dưới 5 phút.
Toàn bộ phần điều phối (khi nào mở vé ảo, ngưỡng bao nhiêu) vẫn là rule do con người
đặt, nên hành vi hệ thống giải thích được và kiểm soát được.
Quan trọng nhất: nếu bỏ AI đi thì hệ thống vẫn chạy được ở mức thấp hơn, nên nhóm
không đặt cược toàn bộ trải nghiệm khách vào chất lượng mô hình.
```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text
Nhóm KHÔNG loại bỏ mức Rule — ngược lại, rule là lớp nền và là thứ phải triển khai
trước.
Lý do không dừng hẳn ở Rule: con số nhập tay mỗi 15 phút vừa trễ vừa là ước lượng
bằng mắt, mà bài toán này chỉ có giá trị khi khách tin con số đủ để đổi lịch cả
buổi chơi; sai 20 phút một lần là khách mất niềm tin luôn.
Tuy nhiên nhóm thừa nhận đây mới là lập luận, chưa phải bằng chứng — và chính vì
chưa đo được nên quyết định cuối là Not Yet.
```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field                                                                          | Nội dung                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| ------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Actor**                                                                      | Du khách VinWonders vào giờ cao điểm (đặc biệt nhóm có trẻ nhỏ, người già) — người phải chọn đi trò chơi nào mà không có thông tin. Actor thứ hai: nhân viên điều phối tại trò chơi, người đang phải vừa vận hành vừa trả lời khách.                                                                                                                                                                                                                                                                      |
| **Workflow**                                                                   | Khách chọn trò chơi và đi bộ tới (không biết wait time) → tới nơi mới thấy hàng → hỏi nhân viên → xếp hàng 30-45 phút → lặp lại cho trò tiếp theo.                                                                                                                                                                                                                                                                                                                                                        |
| **Bottleneck**                                                                 | Thời gian mất nhiều nhất ở bước xếp hàng vật lý, nhưng nguyên nhân gốc ở bước chọn trò chơi: thông tin về độ dài hàng chỉ tồn tại tại chỗ, không chảy ra cho khách đang ở xa.                                                                                                                                                                                                                                                                                                                             |
| **Impact**                                                                     | Khách chờ 30-45 phút dưới nắng mưa và bỏ lỡ show/giờ ăn; điểm nóng quá tải trong khi khu lân cận vắng; nhân viên bị phân tán khỏi vận hành an toàn. **Lưu ý: con số 30-45 phút là ước lượng cá nhân chưa bấm giờ — phải đo lại trước khi dùng làm baseline.**                                                                                                                                                                                                                                             |
| **Success Metric**                                                             | Metric chính (phần AI chịu trách nhiệm): sai số dự báo thời gian chờ MAE dưới 5 phút, đo bằng cách đối chiếu con số hiển thị với thời gian chờ thật bấm giờ trên mẫu 30 khách/ngày trong 3 ngày cao điểm. Metric kết quả (phụ thuộc cả vận hành): thời gian chờ vật lý tại trò chơi áp dụng giảm xuống dưới 10-12 phút, và tỷ lệ khách biết wait time **trước khi** đi tới tăng từ ~0% lên trên 70%.                                                                                                      |
| **Boundary** (làm / không làm)                                                 | Làm: đếm người ẩn danh, dự báo thời gian chờ, hiển thị lên app/LED, gợi ý phân luồng, mở vé ảo theo ngưỡng do con người đặt. Không làm: quyết định dừng/chạy trò chơi, từ chối khách, nhận diện khuôn mặt hay lưu ảnh cá nhân, tự đổi lịch show. **Không hứa tăng công suất** — hệ thống phân phối lại thời gian chờ chứ không tạo thêm chỗ.                                                                                                                                                              |
| **AI intervention point** (can thiệp sau bước nào, trước bước nào)             | Sau khi camera và hệ thống vé đã cho ra số người đang chờ; trước bước rule hiển thị và trước khi nhân viên điều phối xác nhận. AI không đứng ở khâu thu dữ liệu thô và không đứng ở khâu ra quyết định vận hành.                                                                                                                                                                                                                                                                                          |
| **Mức chọn** (Rule / Workflow / Agent + 1 câu vì sao)                          | Workflow trên nền Rule: các bước tuyến tính và biết trước, AI chỉ đảm nhiệm một việc hẹp có ground truth (ước lượng thời gian chờ), còn ngưỡng điều phối vẫn do con người đặt.                                                                                                                                                                                                                                                                                                                            |
| **Rủi ro & người thật kiểm tra** (rủi ro lớn nhất + ai kiểm tra bằng cách nào) | Rủi ro lớn nhất là **dự báo thấp hơn thực tế**: app báo 10 phút, khách bỏ show để tới xếp hàng rồi chờ 40 phút — mất niềm tin một lần là khách không dùng app nữa. Cách chặn: hệ thống liên tục đối chiếu dự báo với thời gian chờ thật và tự tắt hiển thị khi MAE vượt ngưỡng; nhân viên điều phối có quyền ghi đè hoặc tắt ngay tại chỗ; hiển thị dạng khoảng ("30-40 phút") thay vì một con số tuyệt đối. Rủi ro thứ hai là riêng tư: chỉ đếm người ẩn danh, không nhận diện khuôn mặt, không lưu ảnh. |

### 6.3. Final decision

| Câu hỏi                               | Yes / Not Yet / No | Ghi chú (câu đầy đủ)                                                                                                                                                                       |
| ------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Actor + workflow rõ chưa?             | Yes                | Actor và 5 bước workflow rõ, dù nhóm quan sát từ vị trí du khách chứ không phải từ bên trong bộ phận vận hành.                                                                             |
| Baseline + metric đo được chưa?       | **Not Yet**        | Metric đã định nghĩa rõ và đo được về nguyên tắc, nhưng baseline 30-45 phút mới là ước lượng cá nhân; nhóm chưa bấm giờ lần nào tại VinWonders.                                            |
| Data/input đủ dùng chưa?              | **Not Yet**        | Nhóm không có quyền truy cập camera, dữ liệu bán vé hay lịch show của VinWonders. Điểm sáng: dữ liệu wait time công khai của hơn 80 công viên qua Queue-Times API đủ để kiểm phần dự báo.  |
| AI sai, hậu quả chấp nhận được không? | Yes (có điều kiện) | Không ảnh hưởng an toàn tính mạng vì AI không chạm vào vận hành trò chơi. Nhưng dự báo thấp hơn thực tế làm khách mất niềm tin, nên bắt buộc phải có cơ chế tự tắt khi sai số vượt ngưỡng. |
| Có người review/owner không?          | **Not Yet**        | Trong thiết kế thì nhân viên điều phối là người xác nhận và ghi đè, nhưng nhóm chưa trao đổi được với bất kỳ nhân sự vận hành thật nào để biết họ có nhận việc này không.                  |
| Có cách non-AI đơn giản hơn không?    | Yes                | Bảng thời gian chờ do nhân viên nhập tay mỗi 15 phút + biển chỉ dẫn tại ngã rẽ — rẻ hơn nhiều và chưa được thử.                                                                            |

**Decision:**

```text
Not Yet — chưa triển khai tại VinWonders. Trước hết làm hai việc song song: (1) đo
baseline thật, (2) kiểm giả thuyết dự báo trên dữ liệu công khai.
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text
Bốn trong sáu câu hỏi ở bảng trên là Not Yet, và cả bốn đều rơi vào cùng một gốc:
nhóm chưa có số thật và chưa tiếp cận được người vận hành.
Nếu kết luận Go lúc này thì nhóm đang cam kết một mục tiêu ("giảm còn 10-12 phút")
dựa trên một baseline mà chính nhóm thừa nhận là ước lượng — đúng kiểu sai lầm mà
bài lab đang cảnh báo.
Research còn cho thấy một phương án phi-AI rẻ hơn nhiều (bảng giờ chờ nhập tay) chưa
hề được thử, nên chưa thể khẳng định phần AI là cần thiết.
Ngược lại, Queue-Times cho dữ liệu wait time thật và miễn phí, nên nhóm hoàn toàn có
thể kiểm giả thuyết "dự báo đạt MAE dưới 5 phút" ngay mà không cần xin phép ai —
đây là lý do quyết định là Not Yet chứ không phải No-Go.
```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text
Pilot này chỉ chạy SAU KHI có baseline thật và được cấp quyền dữ liệu:

Phạm vi: đúng 1 trò chơi đông khách, trong 3 ngày cao điểm.
- Giai đoạn 1 (chỉ Rule): nhân viên nhập thời gian chờ mỗi 15 phút, hiển thị lên app
  và một màn hình tại ngã rẽ chính. Không có AI.
- Giai đoạn 2 (thêm dự báo): chỉ làm nếu giai đoạn 1 chưa đạt, khi đó mới đưa mô hình
  dự báo vào thay con số nhập tay.

3 số phải đo mỗi ngày:
1. Thời gian chờ thật (bấm giờ mẫu 30 khách/ngày).
2. Sai số giữa con số hiển thị và thời gian chờ thật (MAE).
3. Tỷ lệ khách biết thời gian chờ trước khi đi tới trò chơi (khảo sát 30 khách).
```

**Nếu Not Yet — cần validate gì trước:**

```text
Đây là nhánh nhóm đang chọn. Bốn việc phải làm trước, xếp theo thứ tự dễ làm trước:

1. Kiểm giả thuyết dự báo trên dữ liệu công khai: lấy wait time lịch sử của vài trò
   chơi đông khách qua Queue-Times API, thử dự báo và xem có đạt MAE dưới 5 phút
   không. Việc này làm được ngay, không cần xin phép ai. Nếu không đạt thì toàn bộ
   phần AI sụp và nhóm quay về mức Rule.
2. Đo baseline thật: bấm giờ thời gian chờ tại một công viên tiếp cận được, hoặc
   khảo sát 10-15 người đã đi VinWonders trong 6 tháng qua, để thay con số ước lượng
   30-45 phút bằng số có nguồn.
3. Kiểm giả thuyết pain: hỏi khách xem họ khó chịu vì "chờ lâu" hay vì "không biết
   trước phải chờ bao lâu". Nếu là vế sau thì mức Rule có thể đã đủ.
4. Hỏi một người làm vận hành công viên xem họ có sẵn sàng nhận vai trò xác nhận và
   ghi đè hay không — nếu không có người này thì boundary trong thiết kế chỉ là lý
   thuyết.
```

**Nếu No-Go — làm gì thay AI:**

```text
Triển khai lớp Rule và dừng ở đó: nhân viên nhập thời gian chờ mỗi 15 phút, hiển thị
trên app và màn hình LED tại các ngã rẽ chính, cộng với vé ảo theo khung giờ cố định
cho một vài trò chơi đông nhất.
Phần lớn giá trị cho khách (biết trước phải chờ bao lâu để tự phân luồng) đến từ lớp
này chứ không phải từ mô hình dự báo.
```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text
- Nếu bước validate số 1 cho thấy dự báo không đạt MAE dưới 5 phút trên dữ liệu công
  khai → dừng phần AI, chỉ làm lớp Rule.
- Nếu bước validate số 3 cho thấy khách hài lòng với con số nhập tay → dừng ở Rule,
  không cần dự báo.
- Khi đã chạy thật: MAE vượt ngưỡng 2 chu kỳ liên tiếp → tự động ẩn con số dự báo,
  quay về hiển thị do nhân viên nhập tay.
- Nếu xuất hiện khiếu nại về riêng tư liên quan tới camera → dừng thu hình, chuyển
  sang đếm người bằng cảm biến không ghi hình hoặc đếm tay.
```

---

### Self-check nộp phần 02 (nhóm)

- [x] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score) — 15 candidates → 4 cluster → shortlist 3 → score → chọn 1, có ghi cả bất đồng
- [x] Có validation (quote thật) + research (link kiểm được)
- [x] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [x] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [x] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do
