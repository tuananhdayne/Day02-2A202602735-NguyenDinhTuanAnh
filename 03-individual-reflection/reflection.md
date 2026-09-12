# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Nguyễn Đình Tuấn Anh
- Mã học viên: 2A202602735
- Nhóm: Nhóm AGI (Lớp K4B - Khóa AI VinUni)
- Candidate problem nhóm chọn: Tự động tổng hợp, phân loại mức độ ưu tiên và trích xuất Action Items / Deadline từ các thông báo phân tán đa kênh (Discord nhiều channel, Email và GitHub) cho học viên khóa AI VinUni.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tự quan sát và quét 5 vấn đề thật trong học tập khóa VinUni AI, dùng AI mở rộng góc nhìn thành 10 vấn đề có số liệu định lượng (phút, lần/tuần, bằng chứng). | Đạt đủ 10 dòng scan chất lượng theo 4 lăng kính, giành trọn điểm cá nhân và mang lại đề tài ứng viên sáng giá nhất cho nhóm. |
| Pitch Problem Card | Trình bày Card #1 về bài toán tổng hợp deadline khóa học VinUni AI trong đúng 2 phút với các mốc thời gian cụ thể (từ 45 phút giảm xuống 8 phút). | 100% thành viên trong nhóm đồng cảm ngay lập tức vì khóa học dồn dập thông tin và ai cũng đang chịu nỗi đau này; nhóm thống nhất chọn luôn đề tài. |
| Challenge bài của bạn khác | Đặt câu hỏi chất vấn đề tài "AI tự động review code đồ án" của bạn trong nhóm về ranh giới kiểm soát lỗi logic và nguy cơ hallucination. | Giúp nhóm nhận ra đề tài đó phạm vi quá rộng, độ mơ hồ cao và không thể kiểm chứng trọn vẹn trong phạm vi buổi lab. |
| Gom trùng / cluster | Nhận diện điểm chung và phân loại 12 candidate problems của 4 thành viên thành 4 cụm rõ ràng: Quản lý deadline, Tra cứu tài liệu, Hỗ trợ code và Giao tiếp nhóm. | Giúp buổi thảo luận nhóm có cấu trúc mạch lạc, nhanh chóng loại bỏ các ý tưởng trùng lặp mà không tốn nhiều thời gian tranh luận. |
| Chọn candidate problem | Phân tích ma trận 7 tiêu chí đánh giá, chỉ ra đề tài deadline khóa học VinUni AI có workflow rõ ràng nhất, dữ liệu text dễ trích xuất và đo lường được ngay. | Cả nhóm đạt được sự đồng thuận tuyệt đối sau 10 phút, không xảy ra xung đột nội bộ. |
| Validation / research | Trực tiếp hỏi nhanh 4 bạn học viên cùng lớp VinUni về tần suất check thông báo và tự tìm hiểu các giải pháp Make/Zapier. | Thu thập được các câu nói (quote) phản ánh đúng thực tế, chỉ ra khoảng trống mà các công cụ hiện tại chưa giải quyết được (tin nhắn chat Discord/Zalo). |
| Workflow nhóm | Bóc tách chi tiết quy trình hiện tại 6 bước (bấm giờ 45 phút) và thiết kế quy trình tương lai 4 bước, chỉ rõ bước nghẽn đọc chat Discord (15 phút). | Giúp nhóm định vị chính xác vị trí AI can thiệp (trích xuất JSON) và chốt chặn an toàn bắt buộc người dùng duyệt (Human boundary). |
| Problem Statement | Viết dự thảo v0 và cùng nhóm siết chặt thành v1, đưa ra các chỉ số định lượng cụ thể (giảm từ 45 phút xuống dưới 10 phút, tỷ lệ sót deadline = 0%). | Tạo nên bản Problem Statement chuẩn xác, nói rõ việc làm và việc dứt khoát không làm (không can thiệp vào tài khoản riêng tư). |
| Rule / Workflow / Agent | Phân tích bảng so sánh kỹ thuật, kiên quyết bảo vệ lựa chọn phương án "Workflow" (Rule regex + LLM extraction) thay vì chạy theo mô hình Agent tự trị. | Giữ cho nhóm "ở lại mặt đất", tránh được sự phức tạp không cần thiết, tiết kiệm chi phí token và loại bỏ nguy cơ AI tự ý chỉnh sửa lịch cá nhân. |
| Decision | Cùng nhóm bỏ phiếu quyết định GO kèm theo kế hoạch thử nghiệm pilot giới hạn trên 10 thông báo thật của kênh Discord môn học và các kênh còn lại. | Đưa ra quyết định dựa trên bằng chứng và sự thấu hiểu rủi ro, có phương án rollback rõ ràng nếu AI trích xuất sai lệch ngày giờ. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của tôi là việc mang bài toán deadline phân tán của chính khóa học VinUni AI ra thuyết phục cả nhóm bằng số liệu đo lường thực tế, đồng thời kiên quyết thiết lập ranh giới an toàn (Human boundary) bắt buộc học viên phải kiểm duyệt trước khi đồng bộ lịch, ngăn nhóm rơi vào cái bẫy "thích làm Agent tự trị cho ngầu".
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý thêm các góc nhìn vấn đề theo 4 lăng kính dựa trên bối cảnh học viên công nghệ. | Giúp mở rộng thêm các khía cạnh về lỗi setup thư viện bài lab và kiểm tra Rubric trước khi nộp bài. | AI gợi ý ý tưởng "xây dựng chatbot gia sư AI toàn năng hỗ trợ mọi môn học" rất sáo rỗng, viển vông và không có quy trình cụ thể. | Gạt bỏ ngay ý tưởng trợ lý toàn năng, thay bằng các vấn đề thực tế có thể bấm giờ từng phút trong đời sống sinh viên. |
| Problem Card | Đóng vai một skeptical PM để tìm ra các lỗ hổng logic trong Problem Card #1. | Chỉ ra nguy cơ quá tải nếu cố gắng tích hợp API của quá nhiều nền tảng chat đóng cùng một lúc. | AI gợi ý để Agent tự động gửi tin nhắn nhắc bài thay cho học viên và tự truy cập tài khoản riêng tư. | Từ chối gợi ý của AI vì vi phạm bảo mật; sửa boundary chỉ tập trung vào việc đọc thông báo công khai và xuất ra bảng xem trước cho người dùng. |
| Workflow | Gợi ý cách định dạng và biểu diễn sơ đồ Before/After bằng văn bản ASCII. | Giúp định dạng sơ đồ trực quan, nhìn rõ mạch nối giữa các bước làm việc. | AI vẽ luồng tự động hóa hoàn toàn: AI đọc xong tự động add thẳng sự kiện vào Google Calendar mà không cần người xem lại. | Bắt buộc chèn thêm bước "Học viên review bảng trích xuất 3 phút" (Human boundary) để kiểm tra chéo, phòng trường hợp AI bị ảo giác ngày tháng. |
| Research | Tìm kiếm các giải pháp và công cụ quản lý lịch học tương tự đã có trên thị trường. | Liệt kê nhanh các từ khóa công nghệ như iCal sync, Webhook, Zapier, Google Calendar API. | AI liệt kê một số extension lạ chưa được kiểm chứng độ an toàn và không giải thích được vì sao các tool này chưa giải quyết triệt để vấn đề ở Việt Nam. | Tự kiểm tra các kênh thông báo hiện có và thử nghiệm thực tế để phát hiện điểm mù của các công cụ hiện tại. |
| Problem Statement | Hỗ trợ chuẩn hóa văn phong và cách diễn đạt các mục trong Problem Statement v0. | Giúp câu chữ gọn gàng, súc tích và đúng cấu trúc đề mục của worksheet. | AI viết phần Success Metric rất chung chung và cảm tính: "giúp học viên học tập chủ động và giảm bớt căng thẳng". | Gạt bỏ văn phong cảm tính, ép về số liệu đo lường định lượng: "giảm tổng thời gian từ 45' xuống dưới 10'/tuần, tỷ lệ bỏ sót deadline = 0%". |
| Rule / Workflow / Agent | Hỏi phản biện về sự khác biệt giữa Workflow và Agent trong bài toán trích xuất dữ liệu. | Phân tích rõ sự khác nhau giữa việc chạy theo pipeline cố định và việc để mô hình tự quyết định gọi công cụ (tool-calling). | AI có xu hướng xúi làm Autonomous Agent đa tác vụ để giải quyết bài toán "thông minh hơn". | Giữ vững lập trường: bài toán này là luồng tuyến tính rõ ràng, chỉ cần Rule trích xuất + LLM parse ngữ cảnh là giải quyết 85% vấn đề; dùng Agent là overkill và tiềm ẩn rủi ro sai sót. |
| Decision | Không dùng AI. | Tự làm hoàn toàn. | AI không thể thấu hiểu được năng lực kỹ thuật thực tế của nhóm và mức độ chịu rủi ro của sinh viên khi bị trễ hạn nộp bài. | Cả nhóm tự thảo luận trực tiếp và bỏ phiếu quyết định Go pilot dựa trên số liệu khảo sát thực tế từ bạn bè cùng lớp. |

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
Quá trình làm việc nhóm trong buổi lab Day 02 đã mang lại cho tôi bài học sâu sắc nhất về tư duy "Problem-First" thay vì vội vàng đâm đầu vào công nghệ. Ngay từ đầu buổi thảo luận, khi tôi pitch bài toán "Tổng hợp thông báo và deadline phân tán của khóa học VinUni AI", cả nhóm đã lập tức đồng cảm và nhất trí lựa chọn vì chương trình học có cường độ rất cao, lượng thông tin dồn dập từ Teams cho tới Discord khiến ai cũng đang trong tình trạng ngợp và lo sợ trôi deadline. Tuy nhiên, nhóm tôi cũng từng suýt rơi vào cái bẫy solution-first khi có thành viên đề xuất xây dựng một AI Agent tự trị có khả năng tự động đăng nhập vào các tài khoản chat để gom tin nhắn và tự add vào lịch cá nhân cho ngầu. Dấu tay rõ nhất của tôi trong sản phẩm cuối cùng chính là việc kiên quyết kéo nhóm "về lại mặt đất", phân tích cho các bạn thấy rằng việc dùng Agent là quá rủi ro về mặt bảo mật quyền riêng tư và cực kỳ nguy hiểm nếu AI bị ảo giác ngày tháng dẫn đến sinh viên nộp bài muộn. Thay vào đó, tôi đề xuất giải pháp Workflow đơn giản hơn rất nhiều: chỉ dùng LLM để trích xuất cấu trúc dữ liệu từ văn bản thông báo, đồng thời bắt buộc phải có bước con người kiểm duyệt trước khi đồng bộ. Đối với tôi, phần khó khăn nhất khi hoàn thiện Problem Statement chính là xác định Boundary — việc dũng cảm nói "KHÔNG LÀM" những tính năng hào nhoáng nhưng tiềm ẩn rủi ro còn khó hơn rất nhiều so với việc vẽ thêm tính năng cho AI. Nếu được làm lại từ đầu, tôi sẽ challenge nhóm sớm hơn về việc tự phỏng vấn thêm nhiều bạn học viên khác trong lớp ngay từ Phase 1 để củng cố các số liệu định lượng về thời gian đọc tin nhắn chat. Buổi lab này thực sự giúp tôi hiểu rằng một giải pháp AI xuất sắc không phải là một mô hình phức tạp nhất, mà là một quy trình giải quyết đúng điểm nghẽn với chi phí thấp và ranh giới an toàn cho người dùng.
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
