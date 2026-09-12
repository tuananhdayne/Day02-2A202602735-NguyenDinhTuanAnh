# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1   | Nguyễn Đình Tuấn Anh | 2A202602735 | Facilitator (Trưởng nhóm điều phối) & Workflow Architect      |
| 2   | Đỗ Minh Hoàng       | 2A202601142 | Researcher & Quick Validation Lead                            |
| 3   | Trần Mai Linh       | 2A202603518 | Scribe / Writer & Problem Statement Lead                      |
| 4   | Lê Quốc Huy         | 2A202602889 | Technical Evaluator (Rule / Workflow / Agent Comparison)      |

**Candidate problem nhóm chọn (1 câu):**

Tổng hợp thông báo & deadline học tập phân tán từ các kênh của khóa học VinUni AI (Canvas LMS, Microsoft Teams, Discord môn học, Outlook, Zalo nhóm).

---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Tuấn Anh | Tổng hợp thông báo & deadline phân tán khóa học VinUni AI | Học viên khóa học AI tại VinUni | Đọc quét các đoạn chat dài trên Discord/Zalo để nhặt deadline (mất 20-25 phút). | Rất thiết thực, ai trong nhóm cũng đang bị ngợp vì quá nhiều kênh. |
| 2 | Tuấn Anh | Quản lý, phân loại chi tiêu cá nhân từ 3 app ngân hàng | Sinh viên sống cùng gia đình, tự quản lý chi tiêu | Nhập liệu thủ công từng giao dịch nhỏ từ MBBank, Techcom, VCB (35 phút). | Nỗi đau thật nhưng mang tính cá nhân, ít liên quan đến bối cảnh khóa học. |
| 3 | Tuấn Anh | Thu thập, tóm tắt tin tức AI từ Facebook và TikTok | Học viên AI cần cập nhật kỹ thuật | Đọc thẩm định lọc bỏ video/bài viết giật tít 30s để tìm code thật (35 phút). | Hay nhưng tiêu chí "tin thực chiến" khó định lượng trong phạm vi lab. |
| 4 | Minh Hoàng | Tự động review code và kiểm tra chuẩn clean code đồ án | Thành viên nhóm làm đồ án lập trình | Đọc dò từng pull request và kiểm tra convention đặt tên hàm (45 phút). | Hấp dẫn nhưng phạm vi quá rộng, dễ bị ảo tưởng về khả năng bắt lỗi logic của AI. |
| 5 | Minh Hoàng | Tìm kiếm tài liệu bài lab bị phân tán trên Google Drive | Học viên khi làm bài tập lớn | Mò lại các thư mục Drive chia sẻ không có cấu trúc chuẩn (25 phút). | Có thể giải quyết bằng cách tổ chức lại thư mục Drive, chưa cần đến AI. |
| 6 | Minh Hoàng | Quản lý tiến độ task sprint trong nhóm làm đồ án | Trưởng nhóm đồ án môn học | Nhắn tin giục từng bạn cập nhật tiến độ vào Trello/Jira (30 phút). | Nỗi đau thật về quản lý nhóm nhưng khó ép các bạn phản hồi đúng hạn bằng AI. |
| 7 | Mai Linh | Tóm tắt slide bài giảng và tài liệu kỹ thuật tiếng Anh dài | Học viên trước buổi học lý thuyết | Đọc 60-80 trang slide tiếng Anh ngập tràn thuật ngữ (90 phút). | Rất phổ biến nhưng hiện tại sinh viên đã dùng sẵn ChatGPT/Claude để paste tài liệu. |
| 8 | Mai Linh | Tra cứu lời giải đáp thắc mắc cũ của TA trên Discord | Học viên khi làm lab gặp bug | Search keyword trên Discord bị trôi giữa hàng trăm tin nhắn chat (20 phút). | Điểm nghẽn rất thật, có thể tích hợp chung vào bài toán thông báo Discord. |
| 9 | Mai Linh | Đối chiếu tiêu chí chấm điểm (Rubric) với bài nộp | Học viên trước giờ bấm submit bài lab | Đọc dò từng tiêu chí PDF với notebook để tránh bị trừ điểm (35 phút). | Rõ ràng, đo lường được nhưng tần suất chỉ xảy ra 1-2 lần/tuần trước deadline. |
| 10 | Quốc Huy | Giải mã stack trace và debug lỗi thư viện CUDA/PyTorch | Học viên làm lab AI thực hành | Copy log lỗi dài 100 dòng tìm kiếm trên StackOverflow (40 phút). | Rất nhức nhối khi train model nhưng phụ thuộc nhiều vào phần cứng máy cá nhân. |
| 11 | Quốc Huy | Tự động ghi chép meeting notes và tóm tắt cuộc họp nhóm | Cả nhóm đồ án môn học | Ngồi nghe lại file ghi âm và gõ lại ai làm gì sau cuộc họp (30 phút). | Hiện đã có nhiều tool meeting có sẵn như Teams recap, Otter.ai. |
| 12 | Quốc Huy | Nhắc hẹn nộp bài tập tự động cho các thành viên trong nhóm | Trưởng nhóm đồ án | Canh giờ deadline để tag tên nhắc từng bạn nộp phần làm (15 phút). | Giải quyết được bằng bot nhắc hẹn đơn giản hoặc Google Calendar reminder. |

### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A. Quản lý thông báo, deadline và lập kế hoạch | #1 (Deadline VinUni), #6 (Tiến độ sprint), #12 (Nhắc deadline nhóm) | Gom thông tin và mốc thời gian từ nhiều nguồn để không bị trễ hạn nộp bài. | Cụm có tính cấp bách cao nhất, ảnh hưởng trực tiếp đến điểm số học tập của cả nhóm. |
| B. Khai phá, tra cứu tài liệu và tin tức | #3 (Tin tức AI), #5 (Tìm tài liệu Drive), #7 (Tóm tắt slide), #8 (Tra cứu TA Discord) | Đọc hiểu và trích xuất thông tin trọng tâm từ văn bản dài hoặc kho dữ liệu phân tán. | Các công cụ LLM hiện tại đã làm khá tốt ở mức prompt cơ bản. |
| C. Hỗ trợ lập trình, debug và review code | #4 (Review code đồ án), #10 (Debug CUDA/PyTorch) | Hỗ trợ các tác vụ kỹ thuật trong quá trình viết mã nguồn và làm bài lab. | Rủi ro kỹ thuật cao, phạm vi quá rộng để giải quyết trọn vẹn trong một buổi lab 4 tiếng. |
| D. Năng suất cá nhân và sinh hoạt | #2 (Chi tiêu ngân hàng), #9 (Check Rubric), #11 (Meeting notes) | Tự động hóa các tác vụ lặp lại trong đời sống và học tập cá nhân. | Mức độ ưu tiên thấp hơn các bài toán phục vụ trực tiếp khóa học hiện tại. |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| Candidate #1: Tổng hợp deadline phân tán khóa học VinUni AI | 1. Actor là chính các thành viên trong nhóm, workflow hiện tại diễn ra hàng tuần.<br>2. Bottleneck rất rõ: đọc quét tin nhắn Discord/Zalo tốn 20-25 phút.<br>3. Dữ liệu text thông báo có sẵn, impact giảm từ 45' xuống 8' đo lường được ngay. | Cách xử lý tin nhắn tự do có chứa viết tắt/teencode của TA và quy định bảo mật riêng tư. |
| Candidate #4: Review code đồ án tự động | 1. Đồ án môn học yêu cầu code chất lượng cao, review chéo mất nhiều thời gian.<br>2. AI có thế mạnh đọc hiểu code syntax và convention. | Rất khó để AI phát hiện lỗi logic nghiệp vụ chuyên sâu; nguy cơ tạo ra code giả (hallucination) gây lỗi runtime. |
| Candidate #10: Debug lỗi thư viện CUDA/PyTorch | 1. Lỗi môi trường xảy ra thường xuyên khi bắt đầu bài lab AI mới.<br>2. Tiết kiệm thời gian mò mẫm trên diễn đàn. | Lỗi phụ thuộc quá nhiều vào phiên bản driver GPU, OS của từng máy học viên; khó tạo ra giải pháp dùng chung ổn định. |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Candidate #1: Deadline phân tán VinUni AI | 5 | 5 | 5 | 5 | 5 | 5 | 5 | **35** |
| Candidate #4: Review code đồ án | 4 | 4 | 4 | 3 | 3 | 4 | 4 | **26** |
| Candidate #10: Debug lỗi CUDA/PyTorch | 4 | 3 | 5 | 4 | 3 | 4 | 5 | **28** |

*Giải thích điểm số Candidate #1:* Cho điểm 5 ở tất cả các cột vì: Actor là chính sinh viên trong lớp; workflow 6 bước bấm giờ rõ từng phút; pain có quote và bằng chứng thật; impact đo bằng phút giảm rõ ràng; hoàn toàn khả thi làm trong lab với dữ liệu text; so sánh rành mạch được giữa Rule, Workflow và Agent; cả 4 thành viên đều hiểu tường tận domain học tập này.

**Candidate nhóm chọn (1 bài duy nhất):**

```text
Candidate #1 — Tổng hợp thông báo & deadline học tập phân tán từ các kênh của khóa học VinUni AI (Canvas LMS, Microsoft Teams, Discord môn học, Outlook, Zalo nhóm).
```

**Vì sao chọn (4-5 câu):**

```text
Cả nhóm đạt được sự đồng thuận tuyệt đối khi chọn bài toán này vì đây là nỗi đau hiện hữu hàng ngày của toàn bộ học viên trong khóa học VinUni AI. Khóa học có cường độ rất nhanh, lượng thông tin dồn dập trải dài trên nhiều nền tảng khiến ai cũng mất gần 1 tiếng đầu tuần để rà soát và luôn sống trong nỗi lo bị sót bài quiz hay lab report. Quy trình hiện tại có thể bóc tách thành các bước với số phút bấm giờ cụ thể, trong đó bước nghẽn đọc quét tin nhắn chat là điểm AI có thể hỗ trợ trích xuất tốt nhất. Hơn nữa, bài toán có đầu vào là văn bản thông báo có sẵn, ranh giới can thiệp rõ ràng và cho phép so sánh rành mạch giữa No AI, Rule, Workflow và Agent mà không vượt quá phạm vi triển khai của buổi lab.
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
- Với bài toán Review code đồ án (#4): Nhóm không chọn vì ranh giới bài toán quá rộng, việc đánh giá chất lượng code phụ thuộc nhiều vào logic thuật toán của từng bài toán cụ thể; nếu AI gợi ý sai có thể phá vỡ cả luồng xử lý của bài lab, rủi ro cao hơn giá trị mang lại.
- Với bài toán Debug lỗi CUDA/PyTorch (#10): Nhóm không chọn vì môi trường phần cứng và phiên bản thư viện của mỗi máy học viên quá phân mảnh; việc xây dựng một giải pháp giải quyết lỗi cục bộ rất khó chuẩn hóa và không thể hoàn thành kiểm chứng trong khuôn khổ buổi lab.
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
Trong buổi thảo luận, bạn Quốc Huy và Minh Hoàng từng đề xuất xây dựng một AI Agent tự trị hoàn toàn: Agent sẽ tự động đăng nhập vào tài khoản cá nhân, cào tin nhắn Discord/Zalo và tự add sự kiện vào Google Calendar cho ngầu. Bạn Tuấn Anh đã phản biện kịch liệt: việc để AI truy cập tài khoản cá nhân tiềm ẩn rủi ro lộ lọt thông tin riêng tư nghiêm trọng, đồng thời nếu Agent bị ảo giác ngày tháng mà tự ý ghi đè vào lịch thì học viên sẽ bị trễ bài nộp và mất điểm môn học. Nhóm đi đến thống nhất (chốt): Hạ cấp kiến trúc từ Agent xuống Workflow an toàn — chỉ xử lý các văn bản thông báo mà học viên chủ động cung cấp, và bắt buộc phải có bước con người kiểm duyệt bảng xem trước (Human boundary) trước khi đồng bộ sang lịch.
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Interview | 3 học viên lớp VinUni AI | - "Tuần nào tao cũng phải mở 4-5 tab lướt mỏi tay, có đợt suýt toang bài quiz 5% vì TA nhắn cập nhật deadline trong channel Discord trôi mất tiêu."<br>- "Canvas có lịch nhưng thầy cô hay dặn thêm bài đọc trên Teams hoặc Zalo nhóm, không check hết là coi như thiếu." | Có 1 bạn bảo: "Tao chỉ cần bookmark lại tab Canvas là đủ, cần gì làm tool phức tạp." | Nhận ra pain thật không nằm ở Canvas mà nằm ở các kênh trao đổi tự do (Discord/Zalo) - nơi thông báo bị chìm trong tin nhắn chat. Nhóm thu hẹp trọng tâm vào việc bóc tách tin nhắn chat. |
| Survey / poll | 6 học viên cùng lớp | 6/6 bạn (100%) xác nhận phải dùng từ 3 kênh trở lên để theo dõi việc học; 5/6 bạn (83%) từng ít nhất 1 lần bị nộp muộn hoặc quên task nhỏ do không đọc kịp tin nhắn. | 2 bạn lo ngại việc cấp quyền tài khoản Discord/Zalo cho bot ngoài vì sợ lộ dữ liệu nhóm chat. | Bổ sung ranh giới an toàn: Giải pháp không yêu cầu cấp quyền đọc trộm tin nhắn cá nhân; người dùng chỉ cần copy đoạn thông báo cần bóc tách hoặc forward vào bot. |
| Log / ticket / review (nếu có) | 1 kênh Discord môn học | Quan sát thấy có trung bình 8-12 câu hỏi của sinh viên/tuần hỏi lại TA kiểu: "Deadline bài lab này nộp lúc mấy giờ thế ạ?", "Nộp bài trên Canvas hay Teams ạ?". | Không có phản bác. | Khẳng định việc thông báo bị trôi là có thật và lặp đi lặp lại hàng tuần. |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Pain thật không nằm ở việc học viên thiếu ứng dụng lịch (ai cũng có Google Calendar), mà nằm ở việc thông tin bài tập bị phân mảnh và chìm nghỉm trong các đoạn hội thoại tự do trên Discord và Zalo; học viên tốn nhiều công sức nhất ở bước "đọc quét và suy đoán đâu là hạn chót thật".
```

Bằng chứng đính kèm (nếu có): `02-group-problem-statement-survey.png`, `02-group-problem-statement-interview-notes.md`

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Canvas Calendar Feed (iCal Sync) | https://community.canvaslms.com/t5/Canvas-Basics-Guide/How-do-I-view-the-Calendar-iCal-feed-to-subscribe-to-an-external/ta-p/44 | Đồng bộ tự động các bài tập chính thức từ Canvas sang Google Calendar / Apple Calendar. | Tự động, chính xác 100% với các bài tập đã tạo sẵn trên hệ thống Canvas LMS. | Hoàn toàn mù tịt trước các thông báo phát sinh, thay đổi giờ nộp hoặc bài tập dặn dò qua Discord, Teams, Zalo. | Tận dụng cơ chế feed có sẵn cho Canvas, không cố làm lại phần Canvas đã làm tốt. |
| Zapier / Make.com Webhook | https://zapier.com/apps/discord/integrations/google-calendar | Tự động bắt sự kiện tin nhắn mới từ Discord để tạo event trên Google Calendar. | Kết nối đa nền tảng mạnh mẽ, chạy ngầm ổn định. | Chỉ lọc theo trigger thô (từ khóa đơn giản), không hiểu được ngữ cảnh ngôn ngữ tự nhiên tiếng Việt; dễ tạo ra hàng loạt event rác trên lịch nếu tin nhắn không phải là deadline. | Cần tầng xử lý ngôn ngữ tự nhiên (LLM) để trích xuất đúng thực thể thay vì chỉ dùng Rule lọc từ khóa. |
| Notion AI / Task Database | https://www.notion.so/product/ai | Quản lý bảng To-do list và hỗ trợ autofill thuộc tính hạn chót từ văn bản. | Giao diện quản lý công việc đẹp, trực quan, tùy biến cao. | Vẫn bắt buộc người dùng phải copy-paste thủ công từng đoạn text vào trang Notion và tự căn chỉnh ngày giờ. | Cần tạo luồng input thuận tiện nhất cho người dùng (one-click copy/paste) và tự động chuẩn hóa định dạng JSON. |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
Nhóm KHÔNG NÊN xây dựng lại ứng dụng xem lịch từ đầu (vì Google Calendar đã quá hoàn hảo), và KHÔNG NÊN cố gắng can thiệp vào các API đóng của Zalo. Nhóm NÊN tập trung xây dựng một "Parser module" nhẹ nhàng: tiếp nhận văn bản thông báo thô từ Discord/Canvas, dùng LLM bóc tách thành dữ liệu có cấu trúc [Môn, Tên bài, Hạn nộp, Link nộp], hiển thị bảng kiểm duyệt nhanh rồi đẩy thẳng sang Google Calendar qua chuẩn file .ics hoặc API.
```

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

```text
[1 Mở Canvas LMS kiểm tra To-do: 7'] 
→ [2 Lướt channel #announcement, #lab Discord: 15' - BOTTLENECK] 
→ [3 Đọc tin nhắn Zalo nhóm đồ án: 10' - BOTTLENECK] 
→ [4 Check Teams & Outlook mail trường: 5'] 
→ [5 Nhập tay hạn nộp vào Google Calendar/Notion: 6'] 
→ [6 Rà soát chéo các môn xem có trùng lịch: 2']
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| 1 | Học viên | Hệ thống Canvas LMS | Danh sách deadline chính thức môn học | 7 phút / đầu tuần | Thao tác đơn giản nhưng chỉ chứa một phần thông tin. |
| 2 | Học viên | Server Discord môn học | Các tin nhắn cập nhật đề bài, dặn dò của TA | 15 phút / đầu tuần | **BOTTLENECK CHÍNH:** Phải lướt hàng chục tin nhắn thảo luận để tìm mốc thời gian thực sự. |
| 3 | Học viên | Nhóm Zalo đồ án | Tin nhắn phân công task, hẹn lịch họp nhóm | 10 phút / đầu tuần | **BOTTLENECK PHỤ:** Tin nhắn trôi nhanh, thông tin mốc nộp bài bị lẫn trong trò chuyện phiếm. |
| 4 | Học viên | Microsoft Teams & Outlook | Email học vụ, lịch seminar bổ sung | 5 phút / đầu tuần | Kiểm tra hòm thư sinh viên để không sót thông báo khẩn. |
| 5 | Học viên | Thông tin nhặt được từ 4 bước trên | Sự kiện trên Google Calendar / bảng To-do | 6 phút / đầu tuần | Gõ thủ công từng dòng: Tên bài, Ngày giờ nộp, Ghi chú. Dễ gõ nhầm giờ. |
| 6 | Học viên | Google Calendar đã nhập | Kế hoạch học tập tuần hoàn chỉnh | 2 phút / đầu tuần | Tự đối chiếu chéo xem có bị trùng lịch thi hoặc sót bài quiz nào không. |

**Bottleneck chính (2-3 câu):**

```text
Điểm nghẽn lớn nhất nằm ở Bước 2 và Bước 3 (chiếm 25/45 phút của toàn bộ quy trình). Học viên phải dùng mắt thường để đọc quét các đoạn văn bản tự do dài hàng trăm dòng trên Discord và Zalo nhằm tìm kiếm các mốc hạn nộp bị ẩn giấu trong văn phong trao đổi đời thường của trợ giảng và bạn cùng nhóm.
```

### 5.2. Future workflow bản nhóm

```text
[1 Copy text thông báo tuần từ Discord/Canvas: 2' - Người] 
→ [2 AI phân tích ngữ cảnh & trích xuất Deadline JSON: 1' - Máy/AI] 
→ [3 Học viên review bảng tổng hợp & bấm Xác nhận: 3' - HUMAN BOUNDARY] 
→ [4 Tự động đồng bộ sự kiện vào Google Calendar: 1' - Máy]

Fallback: Nếu AI trích xuất sai ngày giờ hoặc hiểu nhầm ngữ cảnh, học viên chỉnh sửa trực tiếp trên ô dữ liệu xem trước bằng dropdown trong 5 giây, hoặc bấm nút mở link gốc đính kèm để tự đọc lại.
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Tổng thời gian | 45 phút / tuần | 7–8 phút / tuần | Bấm giờ thực tế quy trình tổng hợp đầu tuần của học viên. |
| Số bước | 6 bước | 4 bước | Đếm số thao tác người dùng phải thực hiện. |
| Số bước thủ công | 6 bước (100% thủ công) | 2 bước (Copy dữ liệu và Review duyệt) | Đếm số bước đòi hỏi con người thao tác trực tiếp. |
| Bottleneck chính | Đọc quét 25' trên Discord/Zalo | Review bảng xem trước 3' | Đo thời gian xử lý bước tốn công nhất. |
| Risk mới | Sót bài tập do trôi tin nhắn | AI trích xuất sai hạn nộp (ảo giác ngày) | Tỷ lệ lỗi được kiểm soát bằng chốt chặn Review bắt buộc của con người. |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
|---|---|
| **Actor** | Học viên tham gia chương trình đào tạo AI tại VinUni (VinUni AI20k), phải theo sát khối lượng kiến thức lớn và các thông báo cập nhật liên tục. |
| **Workflow** | Hằng tuần, học viên mở thủ công 5 kênh (Canvas, Teams, Discord, Outlook, Zalo) để đọc lướt, nhặt ra các mốc hạn nộp và tự gõ vào Google Calendar. |
| **Bottleneck** | Bước đọc quét các đoạn chat dài trên Discord và Zalo tốn tới 25 phút và gây căng thẳng mắt, rất dễ bỏ sót các thông báo quan trọng của trợ giảng. |
| **Impact** | Tốn 45 phút mỗi tuần (~30 giờ/năm); từng có học viên bị trễ bài quiz 5% điểm quá trình; luôn trong trạng thái bất an vì sợ bị sót việc. |
| **Success Metric** | Giảm tổng thời gian từ 45 phút xuống dưới 10 phút/tuần; tỷ lệ trích xuất đúng hạn nộp đạt trên 90%; tỷ lệ bỏ sót deadline quan trọng giảm về 0%. |
| **Boundary** | Chỉ tập trung vào việc đọc thông báo và trích xuất hiển thị bảng xem trước; không can thiệp vào tài khoản chat cá nhân và không tự động nộp bài thay học viên. |

**Câu hỏi AI phản biện v0 (nếu có):**
- Field nào mơ hồ: Success metric ban đầu ghi "giúp học viên nắm deadline tốt hơn" bị mơ hồ về cách đo lường; Boundary chưa làm rõ phạm vi dữ liệu đầu vào.
- Tôi sửa gì: Siết chặt Success Metric thành con số cụ thể (giảm từ 45' xuống dưới 10', độ chính xác trích xuất > 90%); định nghĩa rõ Boundary là chỉ nhận text đầu vào do học viên chủ động cung cấp, không tự ý cào dữ liệu tài khoản riêng tư.

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [x] Thấp (có đúng/sai rõ) — Vì sao: Hạn nộp bài tập là thông tin nhị phân rõ ràng (đúng ngày giờ nộp hay sai, không có vùng xám hay cảm tính).
- Độ phức tạp: [x] Trung bình (3-4 bước, phụ thuộc nhau) — Vì sao: Quy trình đi qua chuỗi bước tuần tự: Nhận văn bản thô → Parse thực thể ngày tháng → Hiển thị kiểm duyệt → Đồng bộ sang Calendar.

**Bài toán nhóm nằm ở ô nào:**

```text
Ô: Độ mơ hồ Thấp — Độ phức tạp Trung bình (Phù hợp nhất với WORKFLOW).
```

**Vì sao (2-3 câu):**

```text
Bài toán đòi hỏi độ chính xác tuyệt đối về mặt dữ liệu (ngày giờ hạn nộp không được phép sai lệch), trong khi cấu trúc luồng xử lý là một đường thẳng cố định từ đầu vào tới đầu ra. Do đó, một kiến trúc Workflow kết hợp giữa quy tắc chuẩn hóa và mô hình ngôn ngữ bóc tách ngữ cảnh là hoàn hảo nhất, không cần đến sự tùy biến tự trị của Agent.
```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | Dùng regex để tìm kiếm từ khóa thời gian (như "23h59", "dd/mm") và từ khóa "deadline", "bài tập". | Đủ khi thông báo viết chuẩn form hành chính: "Hạn nộp bài tập 1: 23h59 ngày 15/10". | Bị gãy hoàn toàn trước văn phong tự nhiên: "tối mai nộp nhé", "thầy dời sang cuối tuần", "làm trước buổi lab sau". | **Một phần:** Dùng cho bước tiền xử lý lọc link Canvas và định dạng file iCal. |
| **Workflow** | Pipeline tuần tự: Rule nhận diện link/môn → LLM trích xuất JSON [Môn, Task, Hạn, Kênh] → Giao diện Review → Sync Calendar. | Đủ cho 95% trường hợp văn phong tự do của trợ giảng và sinh viên trên Discord/Zalo. | Rủi ro LLM bị hallucination ngày tháng nếu ngữ cảnh thông báo quá rối rắm. | **CHỌN CHÍNH:** Áp dụng cho toàn bộ luồng xử lý cốt lõi từ trích xuất đến hiển thị kiểm duyệt. |
| **Agent** | AI Agent tự lập kế hoạch, tự gọi tool đăng nhập các nền tảng chat, tự đọc trộm tin nhắn, tự quyết định tạo lịch và gửi tin nhắc bài. | Chỉ cần khi bài toán yêu cầu hệ thống tự tương tác qua lại, tự thương lượng lịch họp hoặc tự nộp bài. | Cực kỳ nguy hiểm về bảo mật quyền riêng tư; Agent có thể tự ý spam tin nhắn hoặc xóa nhầm sự kiện lịch; chi phí token cao và khó kiểm soát lỗi. | **KHÔNG CHỌN:** Hoàn toàn overkill và tạo ra rủi ro không thể chấp nhận được đối với học viên. |

**5 câu hỏi chốt (trả lời câu đầy đủ):**
1. Rule có giải được 70-80% case không? -> *Không, vì thông báo trên Discord và Zalo được viết bằng ngôn ngữ tự nhiên đa dạng, chứa tiếng lóng và thời gian tương đối ("tối mai", "thứ Sáu tuần sau").*
2. Các bước có đi thẳng một đường không hay phải rẽ nhánh? -> *Các bước đi thẳng một đường tuần tự từ Input Text → JSON Extract → Human Review → Calendar Sync, không cần rẽ nhánh động.*
3. Có thật sự cần Agent tự lập kế hoạch + gọi tool không? -> *Hoàn toàn không cần, vì học viên chỉ cần trích xuất dữ liệu chứ không cần AI tự động ra quyết định hành động.*
4. Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu? -> *Học viên sẽ là người phát hiện đầu tiên ngay tại màn hình Review trước khi bấm đồng bộ, và có thể sửa lại ô ngày giờ chỉ trong 5 giây.*
5. Có hạ được từ Agent → Workflow → Rule không? -> *Có thể hạ từ Agent xuống Workflow một cách hoàn hảo, vừa giải quyết triệt để bài toán vừa loại trừ được mọi rủi ro bảo mật.*

**Mức chọn:**

```text
WORKFLOW (Quy trình làm việc có cấu trúc: Rule tiền xử lý + LLM trích xuất thực thể + Human-in-the-loop review).
```

**Vì sao chọn (3-4 câu):**

```text
Nhóm chọn Workflow vì đây là điểm cân bằng hoàn hảo giữa năng lực hiểu ngôn ngữ tự nhiên của LLM và sự an toàn, có thể kiểm soát của quy trình tuyến tính. Workflow giải quyết trọn vẹn điểm nghẽn đọc quét tin nhắn phức tạp mà không đưa hệ thống vào trạng thái rủi ro bảo mật như Agent. Chi phí vận hành thấp, dễ triển khai và kiểm thử trong phạm vi bài lab.
```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text
Nhóm không chọn phương án Rule thuần túy vì hệ thống regex cứng nhắc không thể xử lý được ngôn ngữ tự nhiên tiếng Việt trong giao tiếp hàng ngày của sinh viên và trợ giảng (ví dụ các mốc thời gian tương đối như "hết tuần này", "sau giờ học 2 tiếng"). Nếu dùng Rule, tỷ lệ bỏ sót deadline sẽ vẫn ở mức rất cao (~40-50%).
```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | Học viên tham gia chương trình đào tạo AI tại VinUni (VinUni AI20k), phải theo sát khối lượng kiến thức lớn, nhiều bài lab hands-on và các thông báo cập nhật liên tục từ giảng viên/TA. |
| **Workflow** | Hằng tuần, học viên mở thủ công 5 kênh liên lạc (Canvas, Teams, Discord, Outlook, Zalo nhóm) để đọc quét các đoạn thảo luận, nhặt ra các mốc hạn nộp và tự gõ từng dòng vào Google Calendar. |
| **Bottleneck** | Bước đọc quét thủ công hàng trăm dòng chat tự do trên Discord và Zalo tốn tới 20-25 phút, gây mỏi mắt và rất dễ bỏ sót các thông báo dời lịch hoặc giao thêm bài tập phụ của TA. |
| **Impact** | Tốn 45 phút mỗi đầu tuần (~30 giờ/năm học); nguy cơ bị trễ bài quiz 5% điểm quá trình hoặc trễ hạn nộp lab report; gây căng thẳng tâm lý thường trực. |
| **Success Metric** | Giảm tổng thời gian tổng hợp từ 45 phút xuống dưới 10 phút/tuần; tỷ lệ trích xuất đúng hạn nộp đạt trên 90%; tỷ lệ bỏ sót deadline bài tập quan trọng giảm về 0%. |
| **Boundary** (làm / không làm) | **LÀM:** Trích xuất các thực thể [Môn học, Tên nhiệm vụ, Hạn nộp, Link nộp] từ văn bản thông báo công khai do người dùng cung cấp; xuất file .ics hoặc đồng bộ sang Google Calendar khi có sự đồng ý.<br>**KHÔNG LÀM:** Không can thiệp vào tài khoản riêng tư; không đọc lén tin nhắn cá nhân; không tự động nộp bài hay gửi email thay sinh viên. |
| **AI intervention point** (can thiệp sau bước nào, trước bước nào) | Can thiệp ngay sau bước người dùng dán văn bản thông báo thô (Input) và ngay trước bước học viên xem bảng tổng hợp (Review), thay thế hoàn toàn công đoạn đọc quét và gõ tay thủ công. |
| **Mức chọn** (Rule / Workflow / Agent + 1 câu vì sao) | **WORKFLOW:** Kết hợp Rule chuẩn hóa dữ liệu + LLM parse ngữ cảnh tiếng Việt + Giao diện người duyệt, vì luồng xử lý tuyến tính rõ ràng và không cần quyền tự trị của Agent. |
| **Rủi ro & người thật kiểm tra** (rủi ro lớn nhất + ai kiểm tra bằng cách nào) | Rủi ro lớn nhất là AI bị hallucination trích xuất sai ngày/giờ nộp bài. Người thật kiểm tra: Học viên bắt buộc phải kiểm tra bảng xem trước trong 2-3 phút và nhấn nút "Xác nhận & Đồng bộ" thì sự kiện mới được ghi vào lịch. |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|---|---|
| Actor + workflow rõ chưa? | Yes | Học viên lớp VinUni AI và quy trình 6 bước hiện tại đã được bấm giờ đo lường cụ thể. |
| Baseline + metric đo được chưa? | Yes | Baseline 45 phút/tuần, mục tiêu dưới 10 phút/tuần; tỷ lệ sót deadline giảm về 0%. |
| Data/input đủ dùng chưa? | Yes | Dữ liệu văn bản thông báo thực tế từ kênh Discord và Canvas môn học có sẵn hàng tuần. |
| AI sai, hậu quả chấp nhận được không? | Yes | Hậu quả được chặn đứng hoàn toàn nhờ bước Human review trước khi lưu vào lịch. |
| Có người review/owner không? | Yes | Chính học viên sở hữu lịch là người kiểm duyệt và chịu trách nhiệm cuối cùng. |
| Có cách non-AI đơn giản hơn không? | No | Các giải pháp Rule hoặc template có sẵn không giải quyết được bài toán hiểu ngôn ngữ tự nhiên trong chat. |

**Decision:**

```text
GO (Triển khai thử nghiệm phiên bản Pilot nhỏ nhất).
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text
Cả nhóm quyết định GO vì bài toán đã thỏa mãn cả 6 tiêu chí kiểm tra: nỗi đau có thật và cấp bách, quy trình Before/After rõ ràng từng phút, ranh giới an toàn được thiết lập chặt chẽ và giải pháp kỹ thuật Workflow nằm hoàn toàn trong tầm tay. Việc áp dụng AI vào đúng điểm nghẽn bóc tách ngôn ngữ tự nhiên mang lại ROI (hiệu quả trên công sức) rất lớn, giúp tiết kiệm 75% thời gian hàng tuần cho học viên mà không tạo ra rủi ro vận hành.
```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text
- Data pilot: 10 đoạn thông báo thật thu thập từ kênh #announcement và #lab-discussion của lớp VinUni AI trong 2 tuần gần nhất.
- Chạy tay: Copy 10 đoạn text này đưa vào prompt trích xuất cấu trúc JSON của mô hình ngôn ngữ lớn (Gemini / Claude).
- Đo 3 số cụ thể:
  1. Thời gian trích xuất trung bình: Mục tiêu < 5 giây / thông báo.
  2. Độ chính xác trích xuất hạn nộp: Mục tiêu đạt tối thiểu 9/10 trường hợp đúng tuyệt đối ngày giờ (>= 90%).
  3. Thời gian học viên review bảng dữ liệu: Mục tiêu < 2 phút cho toàn bộ 10 thông báo.
```

**Nếu Not Yet — cần validate gì trước:**

```text
(Không áp dụng vì nhóm chọn GO. Tuy nhiên nếu lùi lại, nhóm sẽ cần kiểm tra kỹ hơn về khả năng parse các mốc thời gian viết tắt bằng tiếng Việt của mô hình).
```

**Nếu No-Go — làm gì thay AI:**

```text
(Không áp dụng vì nhóm chọn GO. Phương án Non-AI thay thế là cử luân phiên một bạn trong lớp làm "thư ký tuần" nhập chung một Google Calendar chia sẻ cho cả lớp).
```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text
Nhóm sẽ lập tức dừng giải pháp và quay về quy trình cũ nếu:
1. Tỷ lệ trích xuất sai lệch ngày giờ của AI vượt quá 15% trong đợt thử nghiệm pilot.
2. Học viên phản hồi rằng thời gian rà soát lại bảng xem trước còn lâu hơn việc tự đọc tin nhắn gốc.
3. Có sự cố làm sai lệch lịch dẫn đến học viên bị nộp trễ bài tập thực tế.
```

---

### Self-check nộp phần 02 (nhóm)
- [x] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score)
- [x] Có validation (quote thật) + research (link kiểm được)
- [x] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [x] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [x] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do
