# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: 911
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu):
- Quyết định cuối: Go / Not Yet / No-Go

---

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Lê Quân Bảo | Khi cập nhật API endpoint mới ở backend, tôi muốn Swagger/Postman collection đồng bộ ngay kèm schema và ví dụ, để Frontend dev ghép API không bị lỗi | Backend Dev | Bước viết mô tả params & tạo ví dụ JSON thực tế (15–20 phút/lần) | "Nếu dev chịu khó viết XML comment chuẩn trong code để Swagger tự trích xuất thì cần gì AI nữa?" (Minh hỏi) |
| 2 | Lê Quân Bảo | Khi QA trả về bug ticket ghi chung chung "nút bấm không chạy", tôi muốn trích xuất nhanh payload và stack trace tương ứng trong log, để sửa ngay mà không phải nhờ thao tác lại | Backend Dev | Bước trao đổi và đứng nhìn QA thao tác lại trên màn hình (15–20 phút/lần) | "Nếu QA không ghi rõ mốc thời gian hay tài khoản test, làm sao dev lọc ra đúng đoạn log bị lỗi giữa hàng nghìn request?" (Quang hỏi) |
| 3 | Lê Quân Bảo | Khi nhận một module mới trong dự án legacy, tôi muốn nắm nhanh Data Flow giữa các tầng Controller-Service-Repo-DB, để bắt tay vào sửa bug/viết code đúng chỗ | Dev mới vào dự án | Bước dò Call Hierarchy và debug trace dữ liệu qua nhiều tầng (12–16 tiếng) | "Dự án lớn có hàng trăm file và logic ngầm trong SQL/Trigger thì làm sao tránh bị tràn context hoặc AI hiểu sai luồng?" (Hậu hỏi) |
| 4 | Nguyễn Văn Hậu | Khi khách nhắn hỏi giá sỉ/lẻ qua Zalo/FB, tôi muốn bóc tách đúng mã hàng và tra tồn kho/chiết khấu để gửi báo giá trong 2 phút, giúp chốt đơn kịp thời | Nhân viên CSKH / Sale shop SME | Bóc tách tên hàng gõ tắt để tra mã SKU trong Sheets và tính bậc chiết khấu (3,5–4,5 phút/lần) | "Nếu chỉ chuẩn hóa file Google Sheets dùng hàm tìm kiếm và tính sẵn công thức (Rule/No AI) thì đã giải quyết được 70–80% thời gian chưa?" (Bảo hỏi) |
| 5 | Nguyễn Văn Hậu | Khi tìm kiếm việc làm, tôi muốn quét và đối chiếu tự động JD mới từ nhiều trang với CV cá nhân, để chọn ra việc phù hợp nộp trong ngày mà không cần mở hàng chục tab | Ứng viên IT / Fresher | Mở 20–30 tab đọc lướt nội dung, bóc tách yêu cầu kinh nghiệm thật và so khớp với CV (45–60 phút/ngày) | "Các trang tuyển dụng lớn đều chặn bot cào dữ liệu (anti-scraping), liệu giải pháp có lấy được dữ liệu JD sạch và đều đặn không?" (Kim hỏi) |
| 6 | Nguyễn Văn Hậu | Khi có thông báo học vụ, lịch thi từ Portal trường, LMS và email, tôi muốn biết ngay các mốc hạn chót trong tuần, để nộp bài đúng hạn | Sinh viên / Học viên | Đăng nhập 4–5 hệ thống rời rạc, đọc thông báo dài và đối chiếu ngày giờ hạn chót (15–20 phút/ngày) | "Cơ chế bảo mật SSO và Captcha của cổng thông tin trường có cho phép tool tự động kết nối kéo thông báo về an toàn không?" (Quang hỏi) |
| 7 | Trần Quang Minh | Khi nhận hàng tại khu nhiều tòa nhà, tôi muốn xác định chính xác điểm gặp shipper, để nhận kiện hàng mà không phải gọi điện và đi tìm nhiều lần | Người nhận hàng chung cư | Đi tìm nhau và xác định điểm nhận hàng sau khi shipper báo đến (10 phút) | "Nếu khu chung cư đã có sảnh đón hoặc bàn bảo vệ giữ hàng cố định (Rule/No AI) thì người nhận có cần AI chỉ điểm gặp không?" (Bảo hỏi) |
| 8 | Trần Quang Minh | Khi đặt món trên ShopeeFood lúc cần ăn đúng giờ, tôi muốn biết sớm đơn có tài xế nhận hay nguy cơ bị hủy, để kịp đổi phương án ăn uống khác | Người đặt món online | Khoảng thời gian chờ quán/tài xế nhận đơn mà không rõ tiến độ và không có cảnh báo trễ | "Ngoài chuyện kẹt xe, việc quán hết món hoặc đóng cửa đột xuất cũng gây hủy đơn, AI có phân biệt được rủi ro thiếu tài xế do giao thông với lỗi từ phía quán không?" (Hậu hỏi) |
| 9 | Trần Quang Minh | Khi đến căng tin vào giờ nghỉ giữa buổi, tôi muốn biết việc xếp hàng và nhận món mất bao lâu, để chọn thời điểm ăn phù hợp không bị muộn học | Sinh viên ăn trưa/nghỉ giữa giờ | Đoạn từ lúc vào hàng đến lúc nhận món mất 11 phút (chưa tách được xếp hàng hay chờ làm món) | "Thời gian làm món phụ thuộc vào bếp, liệu camera đếm người xếp hàng (Rule/CV) hay bảng ước lượng giờ cao điểm thông thường đã đủ giải quyết chưa?" (Kim hỏi) |
| 10 | Nguyễn Hải Quang | Khi so sánh các phòng trọ vừa túi tiền, tôi muốn biết mỗi phòng thực sự tốn bao nhiêu/tháng, để chọn phòng đi xem phù hợp với ngân sách | Người tìm phòng trọ | Nhắn/gọi hỏi chủ trọ về các khoản phí ẩn chưa rõ trong tin đăng và chờ phản hồi (45 phút) | "Việc chủ trọ trả lời chậm hoặc giấu phí phát sinh là rào cản con người ngoài đời thực, liệu AI hay tool có giúp họ phản hồi nhanh hơn được không?" (Bảo hỏi) |
| 11 | Nguyễn Hải Quang | Khi mua nguyên liệu nấu ăn cho một người, tôi muốn biết cần mua bao nhiêu, để dùng hết trước khi rau củ bị hỏng | Người sống một mình tự nấu | Khâu chọn lượng thực mua tại siêu thị/cửa hàng vì gói đóng sẵn thường vượt quá khẩu phần một bữa (30–50 phút) | "Lượng ăn phụ thuộc vào số người và sức ăn từng hôm; nếu siêu thị chỉ bán gói lớn đóng sẵn thì AI gợi ý khẩu phần có giúp giảm lượng rau thừa bị bỏ đi không?" (Minh hỏi) |
| 12 | Nguyễn Hải Quang | Khi chuẩn bị ứng tuyển vị trí thực tập/entry-level, tôi muốn biết dự án nào của mình khớp với từng yêu cầu trong JD, để chọn nội dung đưa vào CV | Sinh viên năm cuối / Fresher | Bước đối chiếu từng yêu cầu trong JD với các việc đã làm trong các dự án cũ (30–40 phút) | "Nếu ứng viên chỉ có 2–3 dự án học tập quen thuộc, việc tự đọc và chọn bằng mắt mất khoảng 15 phút, liệu có đáng phải dùng AI can thiệp không?" (Hậu hỏi) |
| 13 | Nguyễn Bá Kim | Khi nhận thông báo từ nhiều nền tảng (LMS, Teams, Email), tôi muốn xem tất cả deadline ở một nơi, để không bị bỏ sót bài tập | Sinh viên đại học | Mở lần lượt 3–4 ứng dụng để đọc và ghi chú deadline thủ công (15–20 phút/ngày) | "Nếu bạn bè spam mail hoặc nhắn rủ 'mai 9h đi đá banh, 10h đi bơi', làm sao AI phân biệt được đâu là deadline học tập thật để không đưa nhầm vào lịch?" (Bảo hỏi) |
| 14 | Nguyễn Bá Kim | Khi cần tài liệu học tập trước giờ học, tôi muốn tìm thấy file bài giảng/tài liệu nhanh chóng, để tiết kiệm thời gian chuẩn bị bài | Sinh viên đại học | Tìm kiếm rời rạc trên Email, Teams, Drive và nhắn hỏi bạn bè (10–30 phút/lần) | "Drive và Teams vốn đã có thanh tìm kiếm theo tên, công cụ này sẽ tìm theo ngữ cảnh hay tóm tắt nội dung bên trong file như thế nào để người dùng không phải mở từng file lên xem?" (Quang hỏi) |
| 15 | Nguyễn Bá Kim | Khi kết thúc buổi họp nhóm làm bài tập, tôi muốn có biên bản tóm tắt tự động, để tiết kiệm thời gian tổng hợp và không sót việc | Nhóm trưởng / Leader | Nghe lại nội dung, lọc ý chính và gõ văn bản biên bản phân công công việc (30–60 phút/buổi) | "Cuộc họp sinh viên thường có nhiều tạp âm, nói chêm tiếng lóng hoặc chen ngang, liệu transcript có đủ sạch để AI tóm tắt đúng việc không?" (Minh hỏi) |
### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A — Gom & đồng bộ thông tin rải rác | #6 (Hạn chót học vụ), #10 (Tổng hợp phí thuê trọ), #13 (Deadline từ LMS/Teams), #14 (Tìm tài liệu học tập), #15 (Biên bản họp nhóm) | Dữ liệu/thông báo phân tán ở nhiều kênh khác nhau, phải mở từng công cụ đọc và tự ghi chép thủ công |
| B — Lệch pha giao tiếp & đối chiếu dữ liệu nghiệp vụ | #1 (Swagger/Postman cho FE), #2 (Log/Payload tái hiện bug QA), #4 (Tra mã SKU & báo giá sỉ/lẻ Zalo) | Hai bên Dev–FE, Dev–QA, Khách–Sale dùng ngôn ngữ/công cụ khác nhau, mất thời gian tra cứu và giải thích qua lại |
| C — So khớp ngữ cảnh văn bản (Matching) | #5 (Quét JD so khớp với CV), #12 (Ghép yêu cầu JD với minh chứng dự án cũ) | Đối chiếu tiêu chí giữa hai tập tài liệu không có cấu trúc cố định để tìm điểm tương đồng |
| D — Theo dõi & dự báo vận hành thực tế | #7 (Điểm hẹn shipper ở chung cư), #8 (Dự báo hủy đơn ShopeeFood), #9 (Xếp hàng căng tin), #11 (Khẩu phần nguyên liệu nấu ăn), #3 (Trace data flow code cũ) | Quy trình phụ thuộc vào hành vi con người và yếu tố vật lý bên ngoài, khó can thiệp bằng phần mềm thuần túy |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Giảm thời gian người đặt đồ ăn phải chờ đợi mập mờ trong đơn hàng có nguy cơ bị hủy từ 20 phút xuống dưới 3 phút

├── Opportunity: Người dùng không biết tuyến đường từ quán đến chỗ mình đang gặp cản trở (kẹt xe, triều cường, ngập nước) khiến tài xế né nhận đơn
├── Opportunity: Người dùng bị giam đơn ngầm, app không cảnh báo xác suất có tài xế nhận trước khi bấm đặt
└── Opportunity: Người dùng phát hiện đơn bị hủy quá muộn, lỡ mất khung giờ ăn để kịp chuyển sang đặt quán khác
    X "Tích hợp Google Maps API kiểm tra kẹt xe"   ← solution, gạch khỏi tầng này
    X "Nút tự động hủy đơn sau 10 phút"            ← solution, gạch khỏi tầng này
    X "Chatbot tự động báo kẹt xe và gợi ý quán"   ← solution, gạch khỏi tầng này
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

- "Tích hợp Google Maps API kiểm tra kẹt xe": Đây là giải pháp tích hợp công cụ kỹ thuật của bên thứ ba, không phải nhu cầu hay nỗi đau thực tế của người dùng.
- "Nút tự động hủy đơn sau 10 phút": Đây là tính năng/quy tắc hệ thống do người làm giải pháp tự nghĩ ra, không phải là cơ hội giải quyết cốt lõi việc thiếu thông tin tuyến đường.
- "Chatbot tự động báo kẹt xe và gợi ý quán": Đây là giải pháp AI/giao diện bị cài cắm quá sớm trước khi xác định rõ ranh giới vấn đề.


### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Cảnh báo rủi ro không có tài xế ShopeeFood (giao thông/ngập) | 5 | 4 | 5 | 5 | 4 | 5 | 5 | **33** |
| Đồng bộ API Swagger/Postman cho Frontend | 5 | 5 | 4 | 4 | 5 | 5 | 4 | **32** |
| Bóc tách mã SKU và tính giá sỉ/lẻ từ tin nhắn Zalo | 4 | 4 | 4 | 4 | 4 | 4 | 3 | **27** |

**Candidate được chọn:**
Cảnh báo rủi ro đơn khó tìm tài xế trên ShopeeFood do cản trở giao thông (kẹt xe, triều cường, ngập nước).

**Vì sao chọn:**
Nỗi đau rất nhức nhối và phổ biến: app chỉ chặn bán kính 10 km, nhưng cùng cự ly 3 km, tuyến đường thoáng tài xế nhận ngay, còn tuyến dính kẹt xe ngã tư hoặc ngập nước thì thời gian di chuyển vọt từ 7 phút lên hơn 30 phút khiến tài xế đồng loạt né đơn. Người dùng bị giam đơn mập mờ 15–20 phút rồi bị hủy thì đã quá giờ ăn trưa. Vấn đề có ranh giới so sánh 4 mức rõ ràng: Rule tĩnh (khoảng cách km) hoàn toàn bất lực trước điều kiện thực tế, trong khi AI/Workflow kết hợp dữ liệu giao thông theo thời gian thực giải quyết đúng điểm nghẽn.

**Vì sao loại các candidate còn lại:**
- *Đồng bộ API Swagger/Postman:* Quy trình kỹ thuật rất chặt chẽ nhưng tệp người dùng hẹp (chỉ trong nội bộ dev), tính cấp bách và tác động đời sống không rõ nét bằng bài toán đặt đồ ăn hằng ngày.
- *Bóc tách SKU & báo giá sỉ Zalo:* Bị phụ thuộc nặng vào cách lưu trữ nội bộ của từng shop (Google Sheets/Excel không chuẩn hóa), khó tiếp cận dữ liệu thật để kiểm chứng nhanh trong phạm vi bài lab.

**Xử lý bất đồng (nếu có):**
Bảo và Kim lo ngại nhóm không có dữ liệu nội bộ về vị trí tài xế và thuật toán điều phối của ShopeeFood thì không thể dự báo. Nhóm đã thống nhất khoanh vùng ranh giới: không can thiệp thuật toán sàn, mà đứng ở góc độ người dùng (Client Copilot) tổng hợp dữ liệu giao thông ngoại cảnh (Google Maps Traffic, triều cường, thời tiết theo khung giờ) để tính xác suất "tài xế từ chối cuốc" ngay tại bước giỏ hàng.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |

*Điền 4–6 giả định; xóa dòng thừa.*

Giả định nhóm kiểm chứng trong buổi này:

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey / Log, ticket, review

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | |
| Câu nói đáng nhớ nhất (nguyên văn) | |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | |
| Hiện đang xử lý bằng cách nào (workaround)? | |
| Mất bao lâu, bao lần? | |
| Insight / opportunity rút ra | |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| | | | |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |
| | | | | | |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |

**Bottleneck chính:**

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text

```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | | | |
| Tổng thời gian | | | |
| Số bước thủ công | | | |
| Bottleneck chính | | | |
| Rủi ro mới phát sinh | | | |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

-

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
