# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Ngô Tiến Dũng
- Mã học viên: 2A202602374
- Nhóm: A - PNV (Thành viên: Lương Khánh Toàn, Lương Quang Huy, Ngô Tiến Dũng, Đặng Quốc Cường, Nguyễn Đức Thắng)
- Candidate problem nhóm chọn: VinWonders — Dự báo thời gian chờ theo thời gian thực và điều phối luồng du khách bằng vé ảo (Virtual Queue) tại các trò chơi đông khách giờ cao điểm.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động                  | Tôi đã làm gì? (việc cụ thể)                                                                                                                                                                                                                                            | Kết quả / ảnh hưởng tới nhóm                                                                                                                                                                        |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Scan cá nhân               | Scan 10 problem từ trải nghiệm thật làm AI Product tại VinHomes (phủ đủ 4 lăng kính: Lặp lại, Tốn thời gian, AI tốt hơn, Pain người khác), có số liệu bấm giờ và số ticket thực tế.                                                                                     | Cung cấp cho nhóm 3 candidate chất lượng cao (#10, #11, #12); trong đó bài #10 (Phân loại phản ánh cư dân) trở thành mốc chuẩn về bằng chứng thực nghiệm (evidence) để nhóm soi chiếu các bài khác. |
| Pitch Problem Card         | Pitch Problem Card #1 (Phân loại & định tuyến thông minh phản ánh cư dân VinHomes Resident) trong 2 phút: nêu rõ workflow 5 bước, bottleneck tốn 150'/ngày và metric rút ngắn xuống 20'/ngày.                                                                           | Bài pitch được nhóm chấm 9/10, lọt vào Shortlist top 3 bài xuất sắc nhất và đạt 32/35 điểm ở bảng đánh giá đồng thuận.                                                                              |
| Challenge bài của bạn khác | Challenge trực diện bài VinWonders của Toàn về việc con số chờ 30-45' chỉ là cảm tính cá nhân chưa bấm giờ; challenge bài gom code review của Thắng rằng chỉ cần Rule quy định "mọi feedback vào PR" là giải quyết xong mà chưa cần AI.                                 | Ép Toàn thừa nhận điểm yếu thiếu số liệu thật (nhóm hạ điểm Pain Evidence xuống 2/5), và giúp nhóm nhận ra phần AI trong bài code review quá mỏng.                                                  |
| Gom trùng / cluster        | Cùng nhóm phân loại 15 candidate thành 4 cụm; chỉ ra các bài của tôi và Thắng thuộc cụm C (Gom thông tin rời rạc), còn bài VinWonders là trường hợp duy nhất thuộc cụm D (Dự báo nhu cầu & điều phối luồng người).                                                      | Giúp nhóm phân biệt rõ giữa bài toán "xử lý dữ liệu văn bản đã có" với bài toán "dự báo trạng thái tương lai", mở rộng không gian tư duy giải pháp.                                                 |
| Chọn candidate problem     | Tranh luận gay gắt ở bước 3.4; chấp nhận lùi bài VinHomes của mình để ủng hộ chọn VinWonders vì giá trị học tập cao hơn, nhưng đặt 2 điều kiện ràng buộc: (1) không được kết luận Go nếu thiếu baseline đo thật, (2) phải tìm được cách validate khả thi với sinh viên. | Tạo sự đồng thuận tuyệt đối trong nhóm, xác lập nguyên tắc kỷ luật tư duy: không vội vã chọn Go chỉ vì đề tài có quy mô lớn.                                                                        |
| Validation / research      | Cùng Huy và Thắng tìm kiếm giải pháp tương tự; nghiên cứu sâu tài liệu Disney Virtual Queue, Lightning Lane và tìm ra nguồn dữ liệu mở cực kỳ giá trị từ Queue-Times.com API.                                                                                           | Mở ra lối thoát thực nghiệm cho nhóm: chứng minh có thể kiểm tra giả thuyết mô hình dự báo sai số dưới 5 phút trên dữ liệu công khai mà không cần dữ liệu nội bộ VinWonders.                        |
| Workflow nhóm              | Cùng vẽ workflow Before/After cho VinWonders; phát hiện điểm đứt gãy handoff thông tin ở Bước 1 và đề xuất đặt Human Boundary tại vị trí nhân viên vận hành xác nhận/ghi đè.                                                                                            | Thiết lập workflow chặt chẽ, phân định rõ lớp Rule (đếm người, mở vé ảo), lớp AI (dự báo wait time) và chốt chặn an toàn do con người kiểm soát.                                                    |
| Problem Statement          | Đóng góp trực tiếp vào bản chuyển đổi PS v0 sang v1: yêu cầu ghi rõ mốc 30-45 phút là ước lượng cần đo lại, và tách riêng metric của AI (MAE < 5 phút) khỏi metric kết quả vận hành (thời gian chờ < 12 phút).                                                          | Ngăn chặn việc nhóm "hứa quá" (over-promise) hoặc nhận vơ công lao tăng năng lực phục vụ trò chơi cho mô hình AI.                                                                                   |
| Rule / Workflow / Agent    | Đặt câu hỏi phản biện dựa trên ma trận phù hợp (độ phức tạp cao, độ mơ hồ thấp); lập luận bác bỏ đề xuất làm Agent tự động điều hướng khách vì nguy cơ rủi ro an toàn và khó giải thích khi lỗi.                                                                        | Nhóm thống nhất chọn mô hình Workflow đặt trên nền tảng Rule, tránh bẫy "làm Agent cho ngầu".                                                                                                       |
| Decision                   | Kiên quyết giữ vững lập trường chọn "Not Yet" dựa trên 4/6 tiêu chí đánh giá chưa đạt (chưa có baseline đo thật, chưa có quyền truy cập dữ liệu, chưa có owner vận hành xác nhận, chưa thử phương án Rule nhập tay).                                                    | Nhóm đưa ra quyết định "Not Yet" dũng cảm và thuyết phục nhất lớp, kèm lộ trình 4 bước kiểm chứng và cơ chế rollback cụ thể.                                                                        |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của tôi là việc kiên quyết kéo nhóm từ tâm lý háo hức muốn "Go" và làm "Agent toàn năng" về mức "Workflow" với quyết định "Not Yet", đồng thời thiết lập ranh giới an toàn nghiêm ngặt (Human Boundary) để AI tuyệt đối không can thiệp vào vận hành cơ học hay quyền dừng/chạy trò chơi của kỹ sư.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase                   | Tôi dùng AI để làm gì?                                                                          | AI hữu ích ở đâu?                                                                                                                                                                      | AI sai / hời hợt ở đâu?                                                                                                                                                                  | Tôi sửa gì bằng nhận định của mình?                                                                                                                                                                                    |
| ----------------------- | ----------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Scan                    | Hỏi AI gợi ý thêm góc nhìn bài toán theo 4 lăng kính cho vai trò AI Product VinHomes.           | Gợi ý được góc nhìn hay về tình trạng "alert fatigue" (quá tải cảnh báo giả) của nhân viên an ninh SOC và khó khăn tra cứu sổ tay quy chế 180 trang.                                   | Đưa ra các ý tưởng viển vông, sai nghiệp vụ như "AI dự báo giá căn hộ thứ cấp" (thuộc mảng đầu tư BĐS) hoặc "AI nhận diện khuôn mặt chấm công bảo vệ liên tục" (vi phạm quyền riêng tư). | Gạt bỏ toàn bộ ý tưởng viển vông; tự điền 100% số liệu đo lường thực tế (bấm giờ, số lượng ticket, tỷ lệ trễ) từ chính kinh nghiệm vận hành hàng ngày của tôi.                                                         |
| Problem Card            | Đóng vai skeptical PM để phản biện điểm yếu của Problem Card #1 (Phân loại phản ánh cư dân).    | Phát hiện lỗ hổng quan trọng: cư dân thường gửi ảnh kèm text rất ngắn kiểu "xem hình", nếu chỉ dùng LLM đọc text đơn thuần sẽ bị mất ngữ cảnh; cảnh báo rủi ro với ticket khẩn cấp P1. | Đề xuất giải pháp quá phức tạp: gợi ý làm một Agent tự động chat qua lại với cư dân để gặng hỏi thông tin trước khi phân loại.                                                           | Từ chối làm Agent chat gây phiền hà cho cư dân; thay vào đó bổ sung xử lý đa phương thức (Multimodal VLM đọc cả ảnh và chữ) và tạo Hard-rule ngắt luồng AI để báo động ngay khi có từ khóa cháy nổ/kẹt thang.          |
| Workflow                | Nhờ AI hỗ trợ cấu trúc lại các bước Before/After và rà soát các điểm lỗi rẽ nhánh.              | Giúp định dạng sơ đồ dòng chảy rõ ràng; nhắc nhở việc phải có nhánh xử lý khi camera hoặc kết nối mạng bị gián đoạn (fallback).                                                        | Tự ý thêm vào bước "AI tự động điều chỉnh tốc độ vòng quay trò chơi để giải tỏa hàng chờ" — một ý tưởng cực kỳ nguy hiểm về mặt an toàn cơ học.                                          | Xóa bỏ ngay lập tức bước can thiệp vận hành cơ học; xác lập ranh giới cứng: AI chỉ là công cụ tính toán thông tin hỗ trợ, quyền điều khiển trò chơi 100% thuộc về con người.                                           |
| Research                | Tìm kiếm các case study và công cụ quản lý hàng chờ thực tế trên thế giới.                      | Chỉ ra các case study lớn đã thành công như Disney Virtual Queue, Lightning Lane và Universal Orlando Virtual Line.                                                                    | Bịa số liệu không có căn cứ (nói rằng Disney giảm được 40% thời gian chờ mà không trích dẫn được nguồn chính thống).                                                                     | Tự vào trang chủ của Disney để đối chiếu quy định thật; tìm ra nguồn dữ liệu công khai từ Queue-Times.com API giúp nhóm có dữ liệu wait time thực tế của hơn 80 công viên để thử nghiệm.                               |
| Problem Statement       | Nhờ AI soi xem các trường trong Problem Statement v0 có bị mâu thuẫn hay hứa hẹn quá mức không. | Chỉ ra lỗi logic nghiêm trọng: nhóm đang lấy con số 30-45 phút chưa bấm giờ làm baseline nhưng lại cam kết giảm xuống 10-12 phút ở Success Metric.                                     | Viết lại phần Boundary rất chung chung theo kiểu khẩu hiệu tiếp thị, thiếu các điều kiện loại trừ kỹ thuật.                                                                              | Tự tay sửa lại PS v1: tách bạch metric của AI (sai số MAE < 5 phút) với metric vận hành (thời gian chờ); bổ sung tuyên bố "không hứa tăng công suất trò chơi".                                                         |
| Rule / Workflow / Agent | Hỏi AI các lý lẽ phản biện xem bài toán VinWonders có thực sự cần đến Agent hay không.          | Phân tích rõ các rủi ro lan truyền thảm họa khi Agent tự động ra quyết định sai trong một hệ thống điều phối hàng nghìn người.                                                         | AI vẫn có xu hướng "thích công nghệ cao", ban đầu vẫn khuyến khích nên dựng "Hệ thống Multi-Agent phối hợp tự động điều hướng khách".                                                    | Bác bỏ hoàn toàn gợi ý Multi-Agent; vận dụng ma trận "độ phức tạp cao, độ mơ hồ thấp" để bảo vệ quan điểm bài toán chỉ cần Workflow có kiểm soát đặt trên lớp Rule nền tảng.                                           |
| Decision                | Không dùng                                                                                      | (Không áp dụng)                                                                                                                                                                        | (Không áp dụng)                                                                                                                                                                          | Nhóm tự thảo luận nội bộ dựa trên 6 câu hỏi điều kiện. Tôi kiên quyết bảo vệ nhận định phải chốt "Not Yet" vì thiếu số đo thật và chưa tiếp cận được người vận hành, không để AI quyết định thay trách nhiệm của nhóm. |

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

```text
Quá trình làm việc cùng nhóm từ 15 candidate ban đầu đến Problem Statement cuối cùng đã mang lại cho tôi một bài học sâu sắc về tính kỷ luật trong tư duy sản phẩm: "Problem first, not AI first". Lúc đầu, khi Toàn pitch đề tài VinWonders, cả nhóm đều rất hào hứng vì bài toán có quy mô lớn, tác động đến hàng nghìn du khách và nghe rất hấp dẫn nếu làm một "Agent AI tự động điều phối toàn công viên". Tuy nhiên, từ góc nhìn của một người làm AI Product tại Vinhomes, tôi đã challenge thẳng thắn việc nhóm chưa hề có số liệu đo lường thực tế mà chỉ đang ước lượng cảm tính con số 30-45 phút chờ đợi. Bất đồng lớn nhất nổ ra khi chấm điểm: bài toán VinHomes của tôi có bằng chứng thực nghiệm rõ ràng nhất (đạt 32/35 điểm), trong khi VinWonders chỉ đạt 24/35 điểm nhưng nhóm vẫn nghiêng về chọn VinWonders. Tôi đã đồng ý thay đổi ý kiến và chấp nhận lùi bài của mình, bởi tôi nhận ra bài VinHomes chỉ là dạng phân loại văn bản quen thuộc, trong khi VinWonders là bài toán dự báo và điều phối có giá trị học tập vượt trội để phân biệt Rule, Workflow và Agent. Đổi lại, tôi đặt ra nguyên tắc thép cho nhóm: tuyệt đối không được chọn "Go" nếu chưa có dữ liệu kiểm chứng và phải kéo giải pháp từ Agent viển vông về một Workflow thực tế đặt trên nền tảng Rule. Dấu ấn lớn nhất của tôi trong bản báo cáo cuối chính là việc định hình ranh giới an toàn (Human Boundary) và tách bạch Success Metric giữa sai số mô hình (MAE < 5 phút) với kết quả vận hành, kiên quyết không để hệ thống "hứa quá" việc tăng công suất trò chơi. Điều thử thách nhất không phải là vẽ workflow, mà là dũng cảm đưa ra quyết định "Not Yet" khi 4/6 điều kiện tiên quyết chưa đạt, thay vì dễ dãi chọn "Go" để làm đẹp báo cáo. Nếu được làm lại từ đầu, tôi sẽ challenge nhóm sớm hơn ngay từ khâu research để bắt buộc cả nhóm phải đi phỏng vấn ít nhất 2-3 du khách thực tế thay vì mất nhiều thời gian tranh luận trên các giả định chủ quan.
```

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
