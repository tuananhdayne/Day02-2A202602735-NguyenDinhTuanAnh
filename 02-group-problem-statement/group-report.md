# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1   | Châu Tùng Dương | 2A202602822 | Facilitator & Problem Owner (Điều phối, bảo vệ bài toán, chốt scope) |
| 2   | Đỗ Mạnh Nghĩa | 2A202602971 | Workflow & Process Architect (Vẽ quy trình trước/sau, phân tích bottleneck) |
| 3   | Nguyễn Đình Tuấn Anh | 2A202602735 | Research & Benchmark (Khảo sát thị trường, đối chiếu giải pháp hiện có) |
| 4   | Hoàng Phong | 2A202602943 | Validation & Documentation (Thực hiện interview/survey, hoàn thiện báo cáo) |

**Candidate problem nhóm chọn (1 câu):**
Tự động tổng hợp, phân loại mức độ ưu tiên và trích xuất Action Items / Deadline từ các thông báo phân tán đa kênh (Discord nhiều channel, Email và GitHub) cho học viên khóa AI VinUni.

---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Châu Tùng Dương | Bị miss thông tin quan trọng (deadline nộp lab, link Zoom) do thông báo rải rác trên Discord, Email, GitHub | Học viên khóa AI VinUni (gần 1000 học viên) | Phải lội tin nhắn thủ công trên 4-5 channels và mail; mất 20-30'/ngày | Cực kỳ nhức nhối, cả nhóm và cả lớp đều đang chịu trận mỗi ngày |
| 2 | Châu Tùng Dương | Tóm tắt Action Items và quyết định kỹ thuật sau buổi họp Google Meet đồ án tốt nghiệp KMA | Trưởng nhóm, thành viên làm đồ án | Nghe lại audio/ghi chú nháp lúc đêm muộn để viết biên bản task | Rất thật, workflow rõ, nhưng phạm vi hơi hẹp cho nhóm làm đồ án |
| 3 | Châu Tùng Dương | Tóm tắt slide lý thuyết VLearn (40-50 trang) thành Cheat-sheet để làm lab chiều | Học viên khóa AI VinUni | Lật từng trang slide tìm lại công thức/khái niệm khi làm lab | Khá hữu ích, nhưng học viên vẫn có thể tự mở 2 màn hình xem slide |
| 4 | Đỗ Mạnh Nghĩa | Khó tìm kiếm lại các quyết định kỹ thuật cũ bị trôi trên Slack/Discord | Developer trong dự án, học viên | Thanh search của chat chỉ khớp keyword cứng, không hiểu ngữ cảnh | Pain thật nhưng việc lấy quyền truy cập dữ liệu chat cũ khá phức tạp |
| 5 | Đỗ Mạnh Nghĩa | Hay quên deadline nộp bài tập lab do không có hệ thống nhắc việc tự động | Học viên hay bị phân tâm | Phải tự ghi chép thủ công vào lịch cá nhân, hay bị sót | Rule đơn giản (Google Calendar) có thể giải quyết được 80% |
| 6 | Đỗ Mạnh Nghĩa | Review và tóm tắt Pull Request dài trên GitHub khi làm bài tập nhóm | Học viên review code, team lead | Đọc từng file code diff để hiểu toàn bộ thay đổi của thành viên | Bài tập Day 2 và các lab đầu khóa chủ yếu là Markdown, chưa nhiều code diff |
| 7 | Nguyễn Đình Tuấn Anh | Tổng hợp Weekly Report tiến độ đồ án từ Git commit log và board Trello | Sinh viên năm cuối làm đồ án | Viết narrative kết nối các commit kỹ thuật thành báo cáo học thuật | Workflow rất chuẩn, nhưng hơi trùng lặp với ví dụ mẫu trong Worksheet |
| 8 | Nguyễn Đình Tuấn Anh | Hòm thư sinh viên bị quá tải bởi các email thông báo spam từ trường học | Sinh viên đại học | Mất thời gian đọc tiêu đề để lọc xem email nào thực sự cần xử lý | Tính năng Filter & Tag có sẵn của Gmail đã giải quyết tương đối tốt |
| 9 | Hoàng Phong | Soạn thảo biên bản họp và phân chia công việc cho Câu lạc bộ sinh viên | Ban chủ nhiệm CLB | Vừa điều phối vừa ghi chép, biên bản hay bị thiếu người nhận việc | Tần suất thấp (chỉ họp 1 lần/tuần), không cấp bách bằng việc học hàng ngày |
| 10 | Hoàng Phong | Tìm kiếm và gợi ý paper học thuật phù hợp cho đề tài nghiên cứu tốt nghiệp | Sinh viên làm khóa luận | Đọc lướt hàng chục bài báo tiếng Anh nhưng độ liên quan thấp | Bài toán quá rộng, khó đánh giá độ chính xác (Ground Truth) trong buổi lab |

### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A. Quản lý & Lọc thông báo đa kênh | #1, #5, #8 | Tiếp nhận thông tin từ nhiều nguồn rời rạc, cần lọc ra thông tin quan trọng có chứa hành động cần làm | Pain point xảy ra hàng ngày, tần suất cao nhất, ảnh hưởng diện rộng |
| B. Trích xuất Action Items cuộc họp | #2, #9 | Chuyển đổi dữ liệu âm thanh/hội thoại trao đổi tự do thành biên bản có cấu trúc và phân công nhiệm vụ | Có bottleneck rõ ràng, dễ đo lường bằng thời gian soạn thảo |
| C. Tóm tắt & Tra cứu tài liệu học tập | #3, #4, #10 | Tìm kiếm ngữ nghĩa và cô đọng tài liệu dài (slide, paper, chat history) thành kiến thức ngắn gọn | Cần AI đọc hiểu tốt, nhưng rủi ro hallucination cần kiểm soát kỹ |
| D. Báo cáo tiến độ & Code Review | #6, #7 | Tổng hợp dữ liệu kỹ thuật (Git, Trello, PR) thành văn bản tóm tắt cho người khác review | Workflow rõ ràng nhưng hơi phụ thuộc vào công cụ của bên thứ ba |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| **Candidate 1: Miss thông báo quan trọng trên Discord/Email/GitHub** (Đề xuất bởi C.T.Dương) | 1. Actor cực kỳ rõ và có sẵn ngay tại lớp (gần 1000 học viên).<br>2. Pain point diễn ra đều đặn 3 lần/ngày; đo được chính xác bằng phút (20-30') và số lần miss deadline.<br>3. Kiểm chứng được ngay lập tức bằng khảo sát thật tại lớp. | Phạm vi tích hợp API đa nền tảng có thể bị phình to nếu không giới hạn rõ boundary ở mức AI Workflow xử lý text nguồn. |
| **Candidate 2: Trích xuất Action Items sau họp Google Meet đồ án** (Đề xuất bởi C.T.Dương) | 1. Workflow lặp lại hàng tuần (2-3 lần), bottleneck rất rõ ở khâu nghe lại audio.<br>2. Giảm trực tiếp thời gian soạn biên bản từ 30' xuống dưới 5'. | Độ chính xác của transcript tiếng Việt cho các thuật ngữ chuyên ngành mật mã/CNTT chưa chắc chắn. |
| **Candidate 7: Tổng hợp Weekly Report đồ án từ Git/Trello** (Đề xuất bởi N.Đ.Tuấn Anh) | 1. Workflow kinh điển, dữ liệu đầu vào có cấu trúc rõ (Git commits, Trello cards).<br>2. Đo lường được bằng thời gian hoàn thành báo cáo. | Quá giống với bài Worked Example mẫu trong Worksheet; cả nhóm muốn giải một bài toán mới và sát sườn hơn. |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| **Candidate 1 (Miss thông báo đa kênh)** | 5 | 5 | 5 | 5 | 5 | 5 | 5 | **35** |
| **Candidate 2 (Action Items họp Meet)** | 5 | 4 | 4 | 4 | 4 | 4 | 4 | **29** |
| **Candidate 7 (Weekly Report đồ án)** | 4 | 4 | 4 | 4 | 4 | 4 | 3 | **27** |

**Candidate nhóm chọn (1 bài duy nhất):**

```text
Tự động tổng hợp, phân loại mức độ ưu tiên và trích xuất Action Items / Deadline từ các thông báo phân tán đa kênh (Discord nhiều channel, Email và GitHub) cho học viên khóa AI VinUni.
```

**Vì sao chọn (4-5 câu):**

```text
Bài toán đạt điểm tối đa (35/35) trên cả 7 tiêu chí đánh giá vì đây là vấn đề "sống còn" diễn ra mỗi ngày của chính 4 thành viên trong nhóm và gần 1000 bạn học cùng khóa. Workflow hiện tại có điểm nghẽn rất rõ ràng (mất 20-30 phút/ngày lội tin nhắn thủ công) và để lại hậu quả đo đếm được (nộp trễ bài lab, vào nhầm link Zoom workshop). Nhóm có lợi thế tuyệt đối khi sở hữu sẵn tập người dùng thật ngay tại chỗ để phỏng vấn, khảo sát lấy số liệu kiểm chứng chỉ trong 10 phút. Quan trọng nhất, bài toán cho phép so sánh rạch ròi giữa Rule (lọc từ khóa), AI Workflow (bóc tách ngữ cảnh) và Agent (tự động hóa hoàn toàn), hoàn toàn vừa vặn để giải quyết triệt để trong khuôn khổ buổi lab 4 tiếng.
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
- Không chọn Candidate 2 (Action Items họp Meet): Mặc dù pain point có thật, nhưng việc kiểm chứng phụ thuộc vào lịch họp đột xuất của nhóm KMA vào buổi tối, không thể kiểm chứng trực tiếp ngay trên lớp học; đồng thời phụ thuộc nhiều vào chất lượng công cụ Speech-to-Text bên ngoài.
- Không chọn Candidate 7 (Weekly Report đồ án): Bài toán này có cấu trúc tương tự 90% với Worked Example trong tài liệu hướng dẫn, nếu chọn sẽ làm giảm tính sáng tạo và không mang lại giá trị giải quyết bức xúc thực tế hàng ngày cho cả nhóm trong khóa học hiện tại.
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
Thành viên Đỗ Mạnh Nghĩa lo ngại rằng việc kết nối trực tiếp vào bot Discord và Gmail API sẽ gặp rào cản về bảo mật, quyền riêng tư và thời gian thiết lập kỹ thuật quá dài cho một buổi lab. Nhóm đã thảo luận và thống nhất chốt boundary chặt chẽ: Ở phạm vi lab này, nhóm không xây dựng bot can thiệp hệ thống phức tạp mà thiết kế một AI Workflow nhận dữ liệu đầu vào là các đoạn text thông báo được xuất/copy từ các kênh, AI tập trung xử lý trích xuất Entity (Deadline, Link, Action) và xuất ra Daily Digest kèm link gốc để con người đối soát.
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Interview | 3 bạn học viên lớp K4B | - Bạn Nam (K4B): *"Hôm thứ Tư tao suýt trễ nộp Lab 1 vì đinh ninh hạn chót là 18h như hôm trước, ai ngờ thầy thông báo đổi thành 17h trong một tin nhắn reply ở Discord mà tao không để ý."*<br>- Bạn Mai (K4B): *"Sáng nào mở mắt ra cũng hoang mang vì không biết link Zoom hôm nay gửi qua mail hay ghim ở Discord. Lội 4 channels mất cả 15 phút vẫn sợ vào nhầm phòng."*<br>- Bạn Tuấn (K4B): *"Thông báo quan trọng hay bị trôi mất vì các bạn chat hỏi đáp và thả meme quá nhiều trong channel chung."* | Bạn Đức (K4B): *"Tao bật thông báo điện thoại nên ai nhắn gì cũng biết ngay, không thấy bị miss."* (Tuy nhiên bạn thừa nhận bị chuông báo làm phiền cả ngày nên thường xuyên phải bấm Mute channel). | Nhận ra vấn đề không phải là "thiếu kênh thông báo", mà là học viên bị "ngộ độc thông tin" (Information Overload), cần một cơ chế phân loại tin nhắn rác/thảo luận với tin nhắn có "Hành động / Deadline bắt buộc". |
| Survey / poll | 12 học viên trong lớp K4B | - 10/12 bạn (83.3%) xác nhận mất từ 20-30 phút/ngày chỉ để kiểm tra các kênh thông báo.<br>- 8/12 bạn (66.7%) từng ít nhất 1 lần bị lỡ thông tin (link Zoom, deadline đổi, repo mới).<br>- 12/12 bạn (100%) mong muốn có một bản tóm tắt 3 dòng mỗi sáng/tối. | 2/12 bạn (16.7%) cho rằng chỉ cần giảng viên ghim tin nhắn (Pin) là đủ, không cần công cụ gì mới. | Nhóm bổ sung boundary: AI Workflow chỉ xử lý thông báo công khai trong các kênh chính thống, không can thiệp tin nhắn riêng tư, và phải luôn dẫn link gốc về tin nhắn đã ghim để học viên bấm vào xem ngay. |
| Log / ticket / review (nếu có) | Quan sát thực tế channel Discord lớp | Trong 3 ngày đầu khóa học, có ít nhất 15 câu hỏi của học viên hỏi lại về: *"Hôm nay học link Zoom nào ạ?"*, *"Hạn nộp bài lab mấy giờ thế mọi người?"* ngay sau khi thông báo đã được đăng trước đó vài tiếng. | Không có phản bác. | Chứng minh rõ ràng: Kênh thông báo hiện tại đang thất bại trong việc truyền tải thông tin hành động tới người học. |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Pain thật không nằm ở việc học viên lười đọc, mà nằm ở việc thông tin hành động quan trọng (Deadline, Link Zoom, Đổi yêu cầu) bị pha loãng và chìm nghỉm giữa hàng trăm tin nhắn thảo luận và các thread con trên Discord. Giải pháp cần giải quyết đúng nút thắt: Tách biệt hoàn toàn tín hiệu quan trọng (Signal) ra khỏi tạp âm thảo luận (Noise) và cô đọng thành dạng checklist hành động.
```

Bằng chứng đính kèm (nếu có): Ghi nhận từ phỏng vấn trực tiếp 3 học viên K4B và khảo sát nhanh tại bàn học chiều ngày 12/09/2026.

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Discord Native Notifications & Mentions | [discord.com/safety](https://discord.com) | Bắn thông báo đẩy khi có tin nhắn mới hoặc được tag @everyone / @here | Có sẵn, thời gian thực, không tốn phí | Bắn chuông vô tội vạ khiến người dùng bị mệt mỏi và bấm "Mute"; hoàn toàn bỏ sót các thông báo dặn dò không tag tên của Giảng viên/Coach | Không dựa vào cơ chế notification đẩy của Discord; cần gom nhóm và xử lý theo đợt (Batch digest). |
| Zapier / Make (Automation Workflow) | [zapier.com/apps/discord/integrations](https://zapier.com) | Bắt sự kiện có tin nhắn mới trong channel và chuyển tiếp về Google Sheet hoặc gửi Email | Tự động hóa kết nối đa nền tảng theo Rule cứng rất ổn định | Không có khả năng hiểu ngữ nghĩa tiếng Việt tự nhiên; không tự bóc tách được ngày giờ nếu giảng viên gõ linh hoạt (ví dụ: "chiều mai nộp nhé") | Cần một lớp AI ngữ nghĩa (LLM) để trích xuất thực thể, Rule thông thường không giải quyết nổi ngôn ngữ tự do. |
| Mailbrew / Feedly AI Feeds | [feedly.com](https://feedly.com) | Tổng hợp các bản tin RSS, Email newsletters thành một bản Daily Digest gửi định kỳ | Giao diện đọc rất thoáng, cấu trúc thông tin rõ ràng | Chỉ áp dụng cho văn bản có cấu trúc tĩnh (báo chí, newsletter), không hỗ trợ luồng chat tương tác đa thread phức tạp của Discord | Học tập format trình bày "Daily Digest" 3 dòng: [Sự kiện/Link] - [Deadline] - [Hành động cần làm]. |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
Nhóm KHÔNG NÊN tốn công xây dựng hệ thống bot tự động phức tạp can thiệp sâu vào tài khoản người dùng (nguy cơ lỗi API và bảo mật token). Thay vào đó, nhóm NÊN tập trung xây dựng một AI Workflow chuyên xử lý ngôn ngữ tự nhiên: Tiếp nhận nguồn dữ liệu text thô → LLM phân loại mức độ ưu tiên và trích xuất thực thể có cấu trúc (Entity Extraction) → Trả về một bản "Daily Digest" ngắn gọn với đường link đối soát nguyên bản.
```

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

Dán workflow hoặc link file: `02-group-problem-statement-workflow.png`

```text
CURRENT STATE — 27 phút

[1 Mở Discord, duyệt 4-5 channel: 3' - Học viên]
→ [2 Cuộn lội tin nhắn & đọc các thread con: 15' - Học viên]  <-- BOTTLENECK CHÍNH
→ [3 Mở Gmail tìm kiếm email từ VLearn/BTC: 4' - Học viên]
→ [4 Mở GitHub kiểm tra commits cập nhật đề bài: 2' - Học viên]
→ [5 Tự ghi chép thủ công mốc deadline/link vào sổ/lịch: 3' - Học viên]
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| 1. Kiểm tra Discord | Học viên | Ứng dụng Discord, danh sách 4-5 channels | Mở sẵn các channel thông báo và thảo luận | 3 phút / 3 lần mỗi ngày | Mở phân tán nhiều channel (#announcements, #general, #lab-submission, #qa) |
| 2. Cuộn đọc & lọc tin nhắn | Học viên | Hàng trăm dòng tin nhắn chat, tin nhắn reply, thread thảo luận | Nhận diện được đâu là tin nhắn dặn dò của GV/Coach | 15 phút / 3 lần mỗi ngày | **BOTTLENECK CHÍNH:** Hoa mắt, dễ bỏ sót dặn dò quan trọng nằm trong thread con |
| 3. Kiểm tra hòm thư Gmail | Học viên | Hòm thư cá nhân, hộp thư đến | Đọc email thông báo phòng học Zoom hoặc cập nhật lịch | 4 phút / 2 lần mỗi ngày | Dễ bị trôi vào mục Updates/Spam hoặc lẫn với email trường khác |
| 4. Kiểm tra repo GitHub | Học viên | Trình duyệt web, link GitHub repo của lớp | Xem commit history của giảng viên | 2 phút / 1 lần mỗi ngày | Kiểm tra xem đề lab có thay đổi rubric hay test case mới không |
| 5. Tự ghi chú deadline/link | Học viên | Thông tin rải rác vừa nhặt được | Note trên Google Calendar hoặc sổ tay cá nhân | 3 phút / 2 lần mỗi ngày | Handoff sang bộ nhớ cá nhân, nguy cơ ghi nhầm giờ hoặc quên cập nhật |

**Bottleneck chính (2-3 câu):**

```text
Điểm nghẽn nghiêm trọng nhất nằm ở Bước 2: Học viên phải cuộn đọc thủ công hàng trăm tin nhắn thảo luận tự do trên Discord để chắt lọc ra vài dòng thông báo dặn dò của ban tổ chức. Bước này ngốn tới hơn 55% tổng thời gian quy trình (15/27 phút), gây mệt mỏi thị giác và là nguyên nhân trực tiếp dẫn đến việc bỏ sót các deadline hoặc đường link Zoom quan trọng.
```

### 5.2. Future workflow bản nhóm

Phải nhìn ra 5 thứ: bước nào máy (Rule), bước nào AI, bước nào người, boundary ở đâu, fallback khi AI sai.

```text
FUTURE STATE — 4 phút

[1 Tự động gom tin nhắn/email mới trong khung giờ: 30s - Máy/Rule]
→ [2 Phân loại ưu tiên & trích xuất Deadline, Link, Action: 30s - Máy/AI Workflow]
→ [3 Hiển thị bản Daily Digest 3 gạch đầu dòng kèm link đối soát: 10s - Máy/Rule]
→ [4 Học viên đọc lướt, bấm link kiểm tra và xác nhận lịch: 2.5' - Người/Human Boundary]  <-- BOUNDARY
→ [5 Đồng bộ 1 chạm vào Google Calendar: 20s - Máy/Rule]

Fallback: Nếu AI trích xuất sai hoặc nghi ngờ sót tin → Học viên bấm trực tiếp vào "Link tin nhắn gốc" đính kèm ngay cạnh gạch đầu dòng để mở đúng bài viết gốc trên Discord/Gmail kiểm tra lại.
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Tổng thời gian theo dõi thông báo | 27 phút / ngày | Dưới 4 phút / ngày | Bấm giờ thực tế của học viên từ lúc bắt đầu đọc tin đến khi nắm đủ lịch |
| Số bước quy trình | 5 bước rời rạc | 5 bước liên hoàn | Đếm số thao tác trên các nền tảng |
| Số bước làm thủ công bằng tay | 5 bước hoàn toàn thủ công | 1 bước duy nhất (duyệt & xác nhận) | Đếm các thao tác đọc - chép thủ công của con người |
| Bottleneck chính | Lội đọc hàng trăm tin nhắn chat (15') | Đọc lướt bản tóm tắt 3 dòng & đối soát link (2.5') | Đo thời gian của bước tốn nhiều công sức nhất |
| Risk mới phát sinh | Đọc sót tin nhắn do trôi bài | AI bịa giờ (Hallucination) hoặc trích xuất sai deadline | Đo tỷ lệ lỗi trích xuất trên tổng số thông báo (mục tiêu < 2%) |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
|---|---|
| **Actor** | Gần 1000 học viên đang tham gia khóa đào tạo AI Thực chiến VinUni (tiêu biểu là lớp K4B), những người phải theo dõi sát sao lịch học lý thuyết, lịch làm lab thực hành và các workshop chuyên đề hàng ngày. |
| **Workflow** | Mỗi ngày 3 lần (sáng trước 9h00, chiều sau giờ học và buổi tối), học viên phải mở ứng dụng Discord duyệt qua 4-5 channels, mở hòm thư Gmail và kiểm tra GitHub repo để rà soát tất cả các dặn dò, link phòng học và hạn nộp bài. |
| **Bottleneck** | Khâu cuộn đọc thủ công hàng trăm tin nhắn trao đổi tự do và các thread con trên Discord để tìm kiếm thông báo chính thức chiếm tới 15/27 phút mỗi ngày và gây mệt mỏi nhận thức cao độ. |
| **Impact** | Mỗi học viên lãng phí khoảng 20-30 phút/ngày (~3 giờ/tuần). Nghiêm trọng hơn, ít nhất 3-4 học viên trong lớp đã từng bị nộp trễ bài lab hoặc không tìm thấy link Zoom workshop do thông báo bị trôi, ảnh hưởng trực tiếp đến kết quả đánh giá cuối khóa. |
| **Success Metric** | Giảm tổng thời gian theo dõi và tổng hợp thông báo từ 27 phút/ngày xuống dưới 4 phút/ngày; tỷ lệ học viên bị bỏ sót deadline hoặc link Zoom giảm về 0%. |
| **Boundary** | Hệ thống chỉ làm nhiệm vụ trích xuất, phân loại và tóm tắt thông báo kèm link dẫn chứng; TUYỆT ĐỐI KHÔNG tự động bấm nộp bài lab, KHÔNG tự ý trả lời tin nhắn thay học viên và KHÔNG tự động tạo lịch mà chưa có sự xác nhận của người dùng. |

**Câu hỏi AI phản biện v0 (nếu có):**
- Field nào mơ hồ: Field Success Metric ban đầu chỉ ghi "tiết kiệm thời gian" mà chưa nói rõ cách đo; Field Boundary chưa nói rõ nếu AI trích xuất sai giờ nộp bài thì ai chịu trách nhiệm.
- Tôi sửa gì: Đã bổ sung con số định lượng cụ thể (từ 27 phút xuống dưới 4 phút/ngày, đo bằng bấm giờ); quy định rõ ranh giới con người: AI chỉ hỗ trợ soạn bản Digest, học viên bắt buộc phải duyệt và bấm xác nhận trước khi lưu lịch.

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [ ] Thấp / [x] Cao (nhiều cách diễn đạt bằng ngôn ngữ tự nhiên tự do của giảng viên/coach) — Vì sao: Thông báo không theo mẫu cố định, có thể là câu chat dặn dò ngắn ("hôm nay nộp trước 5h chiều nhé"), có thể là thông báo dài có format, hoặc câu trả lời trong thread. Rule thông thường không thể bao quát hết các cách hành văn.
- Độ phức tạp: [x] Thấp-Trung bình (Quy trình 3-4 bước nối tiếp, luồng đi thẳng một chiều) — Vì sao: Dữ liệu đi thẳng từ Thu thập text thô → Trích xuất thực thể → Định dạng bản Digest → Hiển thị cho người dùng duyệt. Không cần rẽ nhánh động hay tự quyết định vòng lặp phức tạp.

**Bài toán nhóm nằm ở ô nào:**

```text
Ô "Độ mơ hồ cao × Độ phức tạp thấp-trung bình" → Hoàn toàn phù hợp với giải pháp [AI WORKFLOW].
```

**Vì sao (2-3 câu):**

```text
Bài toán đòi hỏi năng lực đọc hiểu ngôn ngữ tự nhiên và trích xuất thực thể (Named Entity Extraction) rất linh hoạt của AI để xử lý văn phong chat tự do của giảng viên mà Rule cứng không làm được. Tuy nhiên, logic xử lý lại đi thẳng một chiều rất rõ ràng và có ranh giới kiểm soát chặt chẽ, không hề cần đến khả năng tự lập kế hoạch (autonomous planning) hay tự gọi công cụ không kiểm soát của một Agent.
```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | Thiết lập bộ lọc từ khóa cứng (vd: "deadline", "zoom", "hạn nộp") trên Discord & Gmail Filter. | Đủ khi 100% giảng viên và BTC luôn dùng đúng cú pháp chuẩn và luôn tag @everyone hoặc ghim bài. | Bỏ sót các câu dặn dò tự nhiên không chứa từ khóa định sẵn (vd: "bài chiều nay nộp trước 17h nha cả lớp"); gây báo động giả khi học viên khác chat nhắc lại từ khóa. | **Có dùng một phần:** Dùng Rule ở Bước 1 (Gom tin nhắn theo mốc thời gian) và Bước 3 (Render giao diện hiển thị). |
| **Workflow** | Rule gom tin nhắn thô → AI phân tích ngữ cảnh, phân loại mức độ quan trọng và trích xuất [Sự kiện/Link - Deadline - Action] → Rule xuất bản Daily Digest 3 dòng kèm link gốc → Người dùng duyệt và bấm lưu. | Đủ để giải quyết triệt để bài toán: AI xử lý phần ngữ nghĩa mơ hồ, Rule xử lý phần kết nối và con người giữ quyền quyết định cuối cùng. | AI có thể tóm tắt sót hoặc hallucination về mốc thời gian nếu câu văn quá mơ hồ. (Khắc phục bằng việc bắt buộc hiển thị trích dẫn câu gốc và link tin nhắn để người dùng đối soát 1 chạm). | **CHỌN ĐÂY LÀ MỨC CHÍNH:** Giải quyết đúng điểm nghẽn, kiểm soát được rủi ro, chi phí vận hành cực rẻ và triển khai ngay được. |
| **Agent** | Một AI Agent tự đăng nhập tài khoản Discord/Gmail của học viên, tự quyết định lúc nào cần đọc kênh nào, tự suy luận và tự tạo sự kiện trên Google Calendar, tự nộp bài lab thay học viên. | Chỉ cần khi học viên hoàn toàn không có mặt và muốn trao quyền tự chủ tuyệt đối cho AI đưa ra quyết định hành động thay mình. | Cực kỳ nguy hiểm: Nguy cơ lộ lọt Token/API key cá nhân; Agent có thể hiểu sai ngữ cảnh và tự nộp bài nhầm file hoặc tạo lịch sai giờ gây lỡ thi; chi phí token cao và khó kiểm soát vòng lặp vô tận. | **KHÔNG CHỌN:** Bài toán không cần quyền tự chủ hành động (autonomy); rủi ro vượt xa giá trị mang lại. |

**5 câu hỏi chốt (trả lời câu đầy đủ):**
1. **Rule có giải được 70-80% case không?**  
   *Trả lời:* Không, vì ngôn ngữ dặn dò trên Discord mang tính hội thoại tự do cao, các thông báo thay đổi đột xuất của giảng viên thường không theo cấu trúc cố định nên Rule chỉ bắt được khoảng 30-40% trường hợp có từ khóa chuẩn.
2. **Các bước có đi thẳng một đường không hay phải rẽ nhánh?**  
   *Trả lời:* Toàn bộ quy trình đi thẳng một đường tuần tự: Thu thập tin nhắn → Trích xuất thực thể bằng AI → Xuất bản Digest → Người dùng duyệt xác nhận.
3. **Có thật sự cần Agent tự lập kế hoạch + gọi tool không?**  
   *Trả lời:* Hoàn toàn không cần, vì các nguồn dữ liệu và mục tiêu đầu ra đã được xác định cố định, không đòi hỏi AI phải tự suy nghĩ xem bước tiếp theo cần làm gì.
4. **Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu?**  
   *Trả lời:* Học viên phát hiện ngay lập tức trong vòng 10-15 giây khi đọc bản Digest, vì mỗi đầu việc đều có link dẫn trực tiếp về tin nhắn gốc để đối soát nhanh.
5. **Có hạ được từ Agent → Workflow → Rule không?**  
   *Trả lời:* Có, nhóm chủ động hạ thẳng từ Agent xuống Workflow để loại bỏ hoàn toàn rủi ro bảo mật và mất kiểm soát, chỉ dùng AI ở đúng mắt xích đọc hiểu ngôn ngữ tự nhiên.

**Mức chọn:**

```text
[ WORKFLOW ]
```

**Vì sao chọn (3-4 câu):**

```text
Nhóm chọn mức Workflow vì đây là điểm cân bằng hoàn hảo giữa tính hiệu quả và độ an toàn. Năng lực LLM được tận dụng chính xác vào mắt xích khó nhất là bóc tách ngữ nghĩa từ ngôn ngữ chat tự do thành các trường dữ liệu có cấu trúc (Entity Extraction), điều mà Rule không thể làm được. Đồng thời, cấu trúc Workflow tuần tự cho phép con người giữ vai trò Human-in-the-loop để kiểm duyệt thông tin trước khi hành động, loại bỏ hoàn toàn nguy cơ hành vi mất kiểm soát của Agent.
```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text
Nhóm không chọn mức Rule đơn thuần vì các công cụ lọc từ khóa có sẵn của Discord và Gmail đã được chứng minh là thất bại trong thực tế: Giảng viên và Coach thường xuyên dặn dò bằng câu văn tự nhiên không theo cú pháp cố định, khiến Rule bỏ sót những thông báo quan trọng nhất hoặc gây ra báo động giả làm người dùng mất kiên nhẫn.
```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | Gần 1000 học viên đang tham gia khóa đào tạo AI Thực chiến VinUni (tiêu biểu là lớp K4B), những người phải theo dõi sát sao lịch học lý thuyết, lịch làm lab thực hành và các workshop chuyên đề hàng ngày. |
| **Workflow** | Mỗi ngày 3 lần (sáng trước 9h00, chiều sau giờ học và buổi tối), học viên phải mở ứng dụng Discord duyệt qua 4-5 channels, mở hòm thư Gmail và kiểm tra GitHub repo để rà soát tất cả các dặn dò, link phòng học và hạn nộp bài. |
| **Bottleneck** | Khâu cuộn đọc thủ công hàng trăm tin nhắn trao đổi tự do và các thread con trên Discord để tìm kiếm thông báo chính thức chiếm tới 15/27 phút mỗi ngày và gây mệt mỏi nhận thức cao độ. |
| **Impact** | Mỗi học viên lãng phí khoảng 20-30 phút/ngày (~3 giờ/tuần). Nghiêm trọng hơn, ít nhất 3-4 học viên trong lớp đã từng bị nộp trễ bài lab hoặc không tìm thấy link Zoom workshop do thông báo bị trôi, ảnh hưởng trực tiếp đến kết quả đánh giá cuối khóa. |
| **Success Metric** | Giảm tổng thời gian theo dõi và tổng hợp thông báo từ 27 phút/ngày xuống dưới 4 phút/ngày; tỷ lệ học viên bị bỏ sót deadline hoặc link Zoom giảm về 0%. |
| **Boundary (làm / không làm)** | **LÀM:** Thu thập văn bản thông báo công khai, trích xuất thực thể (Deadline, Link Zoom, Yêu cầu hành động) và hiển thị bản tóm tắt Daily Digest 3 dòng kèm link nguồn đối soát.<br>**KHÔNG LÀM:** Không đọc tin nhắn riêng tư (DM); không tự ý tương tác chat thay học viên; không tự động nộp bài; không tự tạo lịch nếu người dùng chưa bấm xác nhận. |
| **AI intervention point** | AI can thiệp chính xác ở **Bước 2** (ngay sau khi Script/Rule gom các đoạn text tin nhắn mới trong khung giờ và ngay trước khi hiển thị bản Daily Digest cho học viên kiểm duyệt). |
| **Mức chọn** | **AI Workflow** — Phối hợp nhịp nhàng giữa Rule thu thập dữ liệu, AI xử lý ngôn ngữ tự nhiên và Human kiểm tra phê duyệt cuối cùng. |
| **Rủi ro & người thật kiểm tra** | Rủi ro lớn nhất là AI bị ảo giác (hallucination) dẫn đến trích xuất nhầm giờ nộp bài hoặc sót link; **Học viên là người thật chịu trách nhiệm kiểm tra** bằng cách đối soát nhanh thông qua đường link dẫn chứng nguyên bản được gắn kèm ngay cạnh từng dòng tóm tắt. |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|---|---|
| Actor + workflow rõ chưa? | **Yes** | Actor là học viên lớp K4B; workflow 5 bước trước/sau đã được định lượng chi tiết đến từng phút. |
| Baseline + metric đo được chưa? | **Yes** | Baseline hiện tại là 27 phút/ngày; mục tiêu kéo giảm xuống dưới 4 phút/ngày và 0% miss deadline. |
| Data/input đủ dùng chưa? | **Yes** | Toàn bộ tin nhắn và email thông báo công khai của khóa học đều có sẵn và cập nhật hàng ngày. |
| AI sai, hậu quả chấp nhận được không? | **Yes** | Hậu quả hoàn toàn kiểm soát được vì có Human Boundary: Bản digest luôn có link nguồn để đối soát ngay lập tức. |
| Có người review/owner không? | **Yes** | Từng học viên là owner trực tiếp duyệt bản digest của mình trước khi bấm lưu vào lịch cá nhân. |
| Có cách non-AI đơn giản hơn không? | **No** | Rule lọc từ khóa cứng đã thất bại trong thực tế do ngôn ngữ giao tiếp chat quá tự do và biến đổi liên tục. |

**Decision:**

```text
[ GO ]
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text
Nhóm quyết định GO vì bài toán đáp ứng trọn vẹn cả 6 tiêu chí của một dự án AI có giá trị thực tiễn cao: Nhu cầu có thật từ gần 1000 người dùng ngay tại chỗ, dữ liệu đầu vào dồi dào, giải pháp non-AI không xử lý triệt để được, và cấu trúc AI Workflow có ranh giới con người kiểm soát chặt chẽ nên rủi ro gần như bằng không. Việc kéo giảm thời gian từ 27 phút xuống 4 phút/ngày sẽ giải phóng năng lượng đáng kể cho học viên tập trung vào chất lượng làm lab.
```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text
- Phạm vi pilot: Thử nghiệm trong 3 ngày liên tiếp với nhóm AGI và 5 học viên tình nguyện lớp K4B.
- Dữ liệu & cách chạy tay: Hằng ngày lúc 8h30 sáng và 17h00 chiều, copy toàn bộ text thông báo mới từ 3 channel Discord chính (#announcements, #general, #lab-submission) và 1 email mới nhất dán vào prompt AI Workflow chuẩn hóa để sinh ra bản Daily Digest. Gửi bản Digest kèm link nguồn vào nhóm chat thử nghiệm.
- Đo 3 con số then chốt:
  1. Thời gian đọc và nắm bắt thông tin của người tham gia (mục tiêu: < 3 phút).
  2. Tỷ lệ trích xuất chính xác thông tin thực thể của AI (mục tiêu: >= 95% không sai lệch ngày/giờ).
  3. Tỷ lệ học viên bị bỏ sót thông tin trong 3 ngày thử nghiệm (mục tiêu: 0%).
```

**Nếu Not Yet — cần validate gì trước:**

```text
(Không áp dụng vì nhóm đã chọn GO dựa trên đầy đủ căn cứ)
```

**Nếu No-Go — làm gì thay AI:**

```text
(Không áp dụng)
```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text
Nhóm sẽ lập tức dừng giải pháp AI và quay về cách đọc thủ công truyền thống nếu:
1. Trong giai đoạn pilot, tỷ lệ AI trích xuất sai lệch giờ deadline hoặc link Zoom vượt quá 5%, gây hiểu lầm cho học viên.
2. Thời gian học viên phải bấm vào link đối soát và sửa lỗi tóm tắt của AI vượt quá 10 phút/ngày (mất nhiều thời gian hơn cả việc đọc trực tiếp).
3. Có thay đổi lớn từ ban tổ chức về việc chuẩn hóa toàn bộ thông báo về một kênh duy nhất có cấu trúc cố định (khi đó giải pháp Rule đơn thuần sẽ thay thế hoàn toàn AI).
```

---

### Self-check nộp phần 02 (nhóm)
- [x] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score)
- [x] Có validation (quote thật) + research (link kiểm được)
- [x] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [x] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [x] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do
