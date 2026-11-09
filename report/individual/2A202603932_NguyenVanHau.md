# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Nguyễn Văn Hậu
- MSSV: 2A202603932
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: 911
- Link repo nhóm: https://github.com/MinhTrannnnn/K5-L3B-DAY02-911-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi khách hàng nhắn hỏi giá, tồn kho và phí ship qua Zalo/Facebook mỗi ngày, tôi muốn đối chiếu nhanh thông tin sản phẩm và chính sách hiện hành từ bảng giá, để phản hồi báo giá chuẩn xác trong vài phút thay vì tra cứu thủ công từng mã | Nhân viên CSKH / Chủ shop bán lẻ (SME) | Trung bình 40–60 tin nhắn/ngày/shop; mỗi lần tra cứu tồn kho + bảng giá sỉ/lẻ mất 3–5 phút (tổng ~2,5 giờ/ngày); khảo sát 5 shop thấy ~20% khách rời đi nếu phản hồi sau 15 phút |
| 2 | Lặp lại | Khi chạy thử nghiệm huấn luyện mô hình nhiều lần trong ngày, tôi muốn ghi lại tự động các tham số và kết quả lỗi của từng lần chạy, để không chạy trùng lại cấu hình đã thất bại | Kỹ sư IT / Lập trình viên | Chạy 10–15 lần thử nghiệm/ngày; mất 5–10 phút/lần copy-paste tham số (`lr`, `batch_size`, dataset version, log lỗi) vào Notion/Sheets hoặc quên ghi dẫn đến chạy trùng 2–3 cấu hình lỗi/tuần (lãng phí 3–5 giờ GPU/tuần) |
| 3 | Tốn thời gian | Khi nhóm làm việc chung trên một báo cáo Markdown, tôi muốn gộp phần viết của 4 người và kiểm tra xung đột nội dung trước khi copy sang repo cá nhân, để không nộp nhầm bản cũ | Thành viên nhóm làm báo cáo chung trên GitHub | Diễn ra ở mỗi buổi lab/sprint (2–3 lần/tuần); mất 20–30 phút cuối buổi để gộp bài, xử lý merge conflict thủ công và đối chiếu tính nhất quán giữa báo cáo nhóm với 4 file cá nhân; từng có 1–2 thành viên commit nhầm bản thiếu cập nhật mới nhất |
| 4 | Tốn thời gian | Khi quay xong một video dài (podcast, webinar, bài giảng, livestream bán hàng), tôi muốn xác định ngay các đoạn cao trào (hook) và chuẩn hóa phụ đề đúng thuật ngữ ngành, để cắt thành 5–10 clip ngắn đăng đa kênh trong ngày | Content Creator / Đội Marketing in-house của SME | 2–3 video dài/tuần; mất 3–4 giờ/video chỉ để nghe lại, ghi timestamp và sửa lỗi chính tả phụ đề chuyên ngành; chi phí thuê editor ngoài khoảng 150k–300k/clip ngắn |
| 5 | Cần đọc, tổng hợp nhiều thông tin | Khi tìm kiếm thông báo học vụ, lịch thi và quy định nộp bài trên cổng thông tin trường, LMS và email, tôi muốn biết ngay các mốc hạn chót trong tuần của mình, để không bị trễ hạn | Sinh viên / Học viên học song song nhiều môn | Mỗi ngày phải mở 3–4 kênh rời rạc (Portal trường, LMS, Gmail, nhóm Zalo/Discord lớp) mất 15–20 phút/ngày; trong học kỳ gần nhất có ~15% sinh viên trong lớp từng trễ hạn ít nhất 1 quiz/bài nộp phụ do thông báo đổi lịch bị trôi |
| 6 | Cần đọc, tổng hợp nhiều thông tin | Khi ký hợp đồng thuê mặt bằng, hợp đồng dịch vụ hoặc hợp đồng lao động/freelance mới, tôi muốn phát hiện các điều khoản bất lợi, phạt vi phạm ẩn hoặc nghĩa vụ thanh toán rủi ro so với khung chuẩn, để đàm phán sửa đổi trước khi đặt bút ký | Chủ doanh nghiệp nhỏ (SME) / Người làm Freelance | Trung bình 2–5 hợp đồng/đợt (dài 8–20 trang/bản, nhiều điều khoản ràng buộc IP, bảo mật NDA, phạt vi phạm); tự đọc mất 60–90 phút/bản nhưng vẫn dễ sót điều khoản bất lợi; thuê luật sư rà soát lẻ tốn 1,5–3 triệu đồng/hợp đồng |
| 7 | Pain từ người khác | Khi khách thuê phòng trọ / căn hộ dịch vụ tới kỳ đóng tiền hàng tháng, chủ nhà muốn chốt chỉ số điện nước từ ảnh chụp đồng hồ, tính tổng phí dịch vụ và gửi thông báo kèm mã QR thanh toán chính xác cho từng phòng, để thu tiền đúng hạn mà không bị khách thắc mắc tính sai | Chủ nhà trọ / Quản lý chuỗi phòng cho thuê (15–100 phòng) | Ngày 1–5 hàng tháng; quản lý 30 phòng mất ~3–4 giờ nhập tay chỉ số từ ảnh Zalo vào Excel, xuất phiếu thu và nhắn từng người; mỗi tháng có 3–5 phòng phản ánh ghi nhầm số điện/nước hoặc quên cộng trừ tiền cọc |
| 8 | Pain từ người khác | Khi phụ huynh có con học tại trung tâm ngoại ngữ/luyện thi sau mỗi tuần học, họ muốn nắm rõ con mình đang hổng kiến thức phần nào, thái độ học và bài tập về nhà ra sao, để phối hợp nhắc nhở con thay vì chỉ nhận điểm số chung chung | Trợ giảng (TA) / Giáo viên trung tâm ngoại ngữ & Phụ huynh | Mỗi trợ giảng phụ trách 2–3 lớp (20–25 học viên/lớp), cuối tuần mất 90–120 phút viết nhận xét cá nhân hóa gửi Zalo cho từng phụ huynh; trung tâm ghi nhận ~25% phụ huynh phàn nàn nhận xét bị "văn mẫu copy-paste" |
| 9 | Pain từ người khác | Khi nhân viên mới vào làm trong 2 tuần đầu, quản lý trực tiếp muốn nhân viên tra cứu được ngay quy trình xử lý tình huống thực tế (đổi trả, bảo hành, khiếu nại khó) theo đúng SOP công ty, để không phải hỏi đi hỏi lại người cũ đang bận | Quản lý trực tiếp (Team Lead) và nhân viên mới tại doanh nghiệp dịch vụ/bán lẻ | Trung bình 1 nhân viên mới hỏi người cũ 6–8 lần/ngày trong 2 tuần đầu (làm gián đoạn ~45 phút/ngày của nhân viên cũ); tài liệu SOP nằm rải rác ở 10+ file Notion/Google Docs dài nên người mới ngại đọc hoặc tìm không ra |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- **Ý giữ lại và chỉnh sửa theo thực tế:** Sau khi tự liệt kê các vấn đề gặp trực tiếp trong công việc kỹ thuật, học tập (#2, #3, #5) và các bài toán thực tế quan sát được (#1, #4, #6), tôi dùng AI để gợi ý mở rộng thêm góc nhìn **"Pain từ người khác"** có tiềm năng làm thành sản phẩm kinh doanh (B2B/SME) và giữ lại **#7 (Chốt điện nước & thu tiền phòng trọ)**, **#8 (Báo cáo học tập cá nhân hóa gửi phụ huynh)** và **#9 (Tra cứu SOP cho nhân viên mới)**. Lý do: cả 3 ý đều có nỗi đau lặp lại định kỳ, quy trình thủ công rõ ràng và khách hàng mục tiêu sẵn sàng trả phí nếu giải quyết được.
- **Ý loại bỏ:**
  - Bỏ gợi ý *"Siêu trợ lý AI tự động quản lý toàn bộ dự án và vận hành doanh nghiệp từ A–Z"* vì phạm vi quá rộng, không chỉ ra được một bước nghẽn (bottleneck) cụ thể và gài sẵn giải pháp vào đề bài.
  - Bỏ gợi ý *"Ứng dụng nhắc lịch uống nước và thói quen sinh hoạt hàng ngày"* vì pain point yếu, thị trường đã bão hòa với hàng trăm app miễn phí, khó phát triển thành sản phẩm kinh doanh.
  - Bỏ gợi ý *"Hệ thống AI tự động chẩn đoán bệnh qua triệu chứng"* vì rủi ro pháp lý, y tế và đạo đức quá cao, vượt quá khả năng kiểm chứng và xây dựng sản phẩm thực tế của nhóm.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Đối chiếu bảng giá sỉ/lẻ, tồn kho & soạn báo giá cho khách qua Zalo/FB (#1) | Nỗi đau diễn ra hàng chục lần mỗi ngày ở các shop/đại lý SME; tác động trực tiếp đến doanh thu (tỷ lệ chốt đơn); quy trình rõ ràng, rất dễ đóng gói thành sản phẩm SaaS/Copilot thu phí hàng tháng | Các shop đang lưu bảng giá và tồn kho trên Google Sheets chuẩn hóa hay file Excel/ảnh chụp rời rạc? |
| 2 | Chốt chỉ số điện nước từ ảnh chụp, tính phí & tạo thông báo QR thanh toán cho phòng trọ (#7) | Nỗi đau lặp lại định kỳ mỗi đầu tháng của hàng trăm ngàn chủ trọ/quản lý căn hộ dịch vụ; khách hàng sẵn sàng trả phí phần mềm để không phải dò số thủ công và tránh cãi nhau về tiền điện nước; giải pháp kết hợp OCR + Rule tạo mã VietQR rất khả thi làm MVP | Ảnh chụp công tơ thực tế từ khách thuê gửi qua Zalo có đủ rõ nét để OCR đọc chính xác trên 90% không? |
| 3 | Ghi lại tự động tham số và kết quả lỗi khi chạy thử nghiệm huấn luyện mô hình (#2) | Nỗi đau lặp lại nhiều lần trong ngày của kỹ sư IT/lập trình viên khi thử nghiệm; dễ đo số giờ GPU bị lãng phí do chạy trùng cấu hình lỗi; có thể đóng gói thành DevTool/CLI plugin tiện ích | Vì sao lập trình viên không bật sẵn MLflow/W&B: do công cụ quá nặng/khó cấu hình hay do thiếu tính năng tóm tắt nguyên nhân lỗi trong traceback? |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi khách hàng nhắn danh sách hàng cần mua kèm yêu cầu báo giá sỉ/lẻ qua Zalo/Facebook, tôi muốn bóc tách đúng mã hàng, đối chiếu tồn kho và bậc chiết khấu hiện hành để gửi bảng báo giá chuẩn xác trong dưới 2 phút, để chốt đơn ngay khi khách đang có nhu cầu cao |
| Actor | Nhân viên CSKH / nhân viên kinh doanh tại các cửa hàng bán buôn, bán lẻ (văn phòng phẩm, linh kiện, phụ kiện, mỹ phẩm) quy mô 2–10 người |
| Thời điểm / bối cảnh | Trong giờ bán hàng cao điểm (9h–11h30 và 14h–17h hàng ngày), khi cùng lúc nhận 5–10 tin nhắn hỏi giá từ nhiều khách sỉ và lẻ trên Zalo/Messenger |
| Quy trình hiện tại (3–7 bước) | 1. Đọc tin nhắn tự nhiên của khách (thường gõ tắt, viết sai chính tả, gửi nhiều tin vụn) · 2. Mở file Google Sheets / phần mềm bán hàng tìm từng mã SKU để kiểm tra tồn kho · 3. Tra bảng chính sách giá theo số lượng (bậc sỉ 1, sỉ 2, đại lý) và khuyến mãi hiện hành · 4. Tính nhẩm hoặc bấm máy tính tổng tiền hàng + ước tính phụ phí giao hàng theo khu vực · 5. Soạn tin nhắn báo giá chi tiết từng dòng gửi lại cho khách · 6. Chỉnh sửa lại báo giá khi khách yêu cầu tăng/giảm số lượng hoặc đổi mặt hàng |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2 & Bước 3 (Bóc tách tên hàng gõ tắt để tra mã SKU trong bảng tồn kho và áp đúng bậc giá chiết khấu): mất trung bình 3,5–4,5 phút/đơn báo giá |
| Impact (nếu không giải thì sao) | 1 nhân viên xử lý 40 lượt hỏi giá/ngày mất ~200–220 phút/ngày (~3,5 giờ); khách mua sỉ thường hỏi cùng lúc 2–3 shop, nếu phản hồi chậm sau 10–15 phút thì 20–25% khách sang mua shop khác (mất 5–15 triệu đồng doanh thu/tuần); báo nhầm giá hoặc sót hàng hết tồn kho phải tự bù tiền hoặc mất uy tín |
| Success metric (baseline → target) | Thời gian từ lúc nhận tin nhắn hỏi giá đến khi gửi báo giá chuẩn giảm từ **5,5 phút/lượt** xuống **dưới 1,5 phút/lượt**; tỷ lệ tính sai đơn giá/chiết khấu giảm về **0%** |
| Phương án không dùng AI | Chuẩn hóa bảng giá trên Google Sheets với hàm `XLOOKUP` và tạo sẵn form/template báo giá cố định: giúp bước cộng tiền nhanh hơn (giảm ~1,5 phút), nhưng nhân viên vẫn phải tự đọc tin nhắn gõ tắt của khách rồi gõ từng mã SKU vào bảng tính thủ công |
| Giả thuyết về AI (nếu có) | AI (LLM) đọc tin nhắn gõ tắt của khách, bóc tách tên hàng + số lượng rồi fuzzy-match sang mã SKU trong kho; sau đó chuyển sang Rule/Script để tra bảng giá và tính tổng tiền chính xác 100%; nhân viên CSKH duyệt lại bản nháp và bấm gửi Zalo |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 5,5 phút/lượt báo giá (x 40 lượt/ngày = ~220 phút/ngày)

[1. Đọc tin nhắn gõ tắt của khách & lọc tên hàng: 1,0']
→ [2. Mở Sheets dò mã SKU & check tồn kho: 1,5'] ← BOTTLENECK (phần 1)
→ [3. Tra bảng chiết khấu theo bậc số lượng: 1,5'] ← BOTTLENECK (phần 2)
→ [4. Cộng tổng tiền & ước tính phí ship: 0,5']
→ [5. Gõ tin nhắn báo giá chi tiết & gửi Zalo: 1,0']
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi khách thuê phòng trọ / căn hộ dịch vụ tới kỳ đóng tiền hàng tháng, tôi muốn bóc tách nhanh chỉ số điện nước từ ảnh chụp công tơ, tự động tính tổng tiền theo định mức và gửi thông báo kèm mã QR chuyển khoản chính xác cho từng phòng, để thu tiền đúng hạn mà không mất nhiều ngày nhập liệu thủ công hay bị khách thắc mắc tính nhầm |
| Actor | Chủ nhà trọ / Quản lý chuỗi căn hộ mini, nhà cho thuê (quy mô 15–80 phòng) |
| Thời điểm / bối cảnh | Định kỳ ngày 1–5 hàng tháng, khi các phòng đồng loạt gửi ảnh chụp đồng hồ điện nước qua Zalo hoặc quản lý đi chụp từng tầng |
| Quy trình hiện tại (3–7 bước) | 1. Mở tin nhắn Zalo nhận ảnh chụp đồng hồ điện nước của từng phòng gửi về (hoặc tự đi chụp từng phòng) · 2. Căng mắt nhìn ảnh, phóng to để đọc chỉ số cũ và chỉ số mới, ghi chép ra giấy nháp hoặc gõ tay vào bảng Excel · 3. Lấy chỉ số mới trừ chỉ số cũ, nhân đơn giá điện nước (theo bậc thang hoặc giá cố định), cộng tiền phòng và các phí dịch vụ (rác, wifi, thang máy, xe) · 4. Mở app ngân hàng tạo mã VietQR kèm số tiền đúng từng phòng, hoặc chụp lại dòng tính tiền gửi qua Zalo riêng từng khách · 5. Trả lời giải thích khi khách thắc mắc tính sai số điện/nước hoặc thắc mắc khoản trừ cọc |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2 & Bước 4 (Đọc chỉ số từ ảnh mờ/góc nghiêng gõ vào Excel và tạo từng thông báo bill/QR gửi riêng lẻ cho từng phòng): mất 5–7 phút/phòng |
| Impact (nếu không giải thì sao) | Quản lý 35 phòng mất 3,5–4,5 giờ mỗi đầu tháng; trung bình có 3–5 phòng/tháng phản ánh bị ghi nhầm chỉ số hoặc sai lệch tiền dịch vụ gây tranh cãi và chậm tiến độ thu tiền phòng từ 3–7 ngày (đọng vốn 50–150 triệu đồng) |
| Success metric (baseline → target) | Tổng thời gian tính tiền và xuất bill cho 30 phòng giảm từ **210 phút** xuống **dưới 40 phút**; tỷ lệ sai lệch chỉ số nhập liệu giảm từ **~10%** xuống **dưới 1%** |
| Phương án không dùng AI | Dùng bảng tính Excel có sẵn công thức tính tiền: người dùng vẫn phải tự mở từng ảnh chụp trong Zalo, căng mắt đọc số và gõ tay từng dòng vào Excel, sau đó vẫn phải copy số tiền sang app ngân hàng để tạo mã QR gửi từng phòng |
| Giả thuyết về AI (nếu có) | AI (Vision model / OCR chuyên dụng) tự động nhận diện và trích xuất số công tơ điện nước từ ảnh chụp; Rule/Script tự động lấy chỉ số mới trừ số cũ tháng trước, áp bảng giá dịch vụ để sinh hóa đơn và mã VietQR thanh toán; chủ trọ chỉ cần nhìn lướt ảnh đối chiếu số đã nhận diện, bấm "Duyệt" là tin nhắn tự gửi qua Zalo webhook |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 7 phút/phòng (x 30 phòng = 210 phút mỗi đầu tháng)

[1. Tải ảnh đồng hồ điện nước từ Zalo: 1,0']
→ [2. Soi ảnh, đọc chỉ số & gõ tay vào Excel: 3,0'] ← BOTTLENECK (phần 1)
→ [3. Excel tự tính tổng tiền các khoản: 0,5']
→ [4. Mở app ngân hàng tạo mã VietQR & soạn tin gửi Zalo từng khách: 2,0'] ← BOTTLENECK (phần 2)
→ [5. Xử lý phản hồi khiếu nại sai số: 0,5']
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi chạy thử nghiệm huấn luyện mô hình nhiều lần trong ngày, tôi muốn ghi lại tự động các tham số và kết quả lỗi của từng lần chạy, để không chạy trùng lại cấu hình đã thất bại |
| Actor | Kỹ sư IT / Lập trình viên trong nhóm R&D (quy mô 2–10 người) đang thực hiện fine-tuning mô hình ngôn ngữ hoặc huấn luyện mô hình thị giác máy tính |
| Thời điểm / bối cảnh | Trong các đợt chạy thử nghiệm lặp (experiment loop) trên Google Colab, Kaggle hoặc máy chủ GPU nội bộ với 10–15 lần chạy thử mỗi ngày |
| Quy trình hiện tại (3–7 bước) | 1. Sửa tham số (`learning_rate`, `batch_size`, `lora_r`, dataset split, prompt template) trong file script hoặc cell notebook · 2. Bấm chạy script train và chờ kết quả hoặc gặp lỗi crash giữa chừng (OOM, NaN loss, CUDA error) · 3. Mở cửa sổ terminal đọc traceback / eval metric cuối cùng · 4. Copy tay các tham số vừa sửa + kết quả metric/lỗi sang bảng Notion hoặc Google Sheets · 5. Khi bắt đầu lần chạy mới, dò lại bảng ghi chú cũ xem tổ hợp tham số này đã từng thử và bị lỗi chưa |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 4 & Bước 5 (Copy tay cấu hình + tóm tắt nguyên nhân lỗi vào bảng theo dõi và tra cứu lại trước lần chạy mới): mất 6–8 phút/lần chạy; khi đang vội debug thường bỏ qua không ghi, dẫn đến hôm sau chạy lặp lại đúng cấu hình từng bị lỗi |
| Impact (nếu không giải thì sao) | Mất 60–90 phút/ngày ghi chép thủ công hoặc quên ghi dẫn đến chạy trùng 2–3 cấu hình lỗi/tuần (lãng phí 3–5 giờ thuê GPU/tuần và làm chậm tiến độ bàn giao model cho team) |
| Success metric (baseline → target) | Thời gian ghi nhận và tra cứu lịch sử mỗi lần chạy giảm từ **7 phút/lần** xuống **dưới 30 giây/lần**; số lần chạy trùng cấu hình đã thất bại giảm từ **2–3 lần/tuần** xuống **0 lần/tuần** |
| Phương án không dùng AI | Viết một hàm wrapper Python (`atexit` / decorator) tự động dump file config YAML + exit code + dòng cuối của `stderr` vào một file `experiments.csv` kèm hash của bộ tham số để cảnh báo nếu trùng hash (Rule/Script giải quyết được ~80% nhu cầu ghi log) |
| Giả thuyết về AI (nếu có) | Rule/script tự động bắt config và kiểm tra trùng hash; AI chỉ can thiệp khi run bị crash phức tạp hoặc loss bất thường để tóm tắt stack trace dài thành 1 câu nguyên nhân gốc + gợi ý tham số cần tránh ở lần chạy kế tiếp |
| Cảm nhận nhanh | Rule (kết hợp Workflow nhẹ khi cần tóm tắt log lỗi dài) |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — ~7 phút/lần thử nghiệm (x 12 lần/ngày = ~84 phút/ngày)

[1. Sửa tham số trong config/notebook: 1,5']
→ [2. Chạy train & chờ kết quả/lỗi: (thời gian máy chạy)]
→ [3. Đọc terminal log & tìm nguyên nhân crash/metric: 1,5']
→ [4. Copy tay tham số + log lỗi sang Notion/Sheets: 2,5'] ← BOTTLENECK (hay bị bỏ qua khi vội)
→ [5. Dò lại bảng cũ trước khi chỉnh lần chạy tiếp theo: 1,5'] ← BOTTLENECK
```

### Card muốn pitch nhất

- Card số: **Card #1 — Đối chiếu bảng giá sỉ/lẻ, tồn kho & soạn báo giá cho khách qua Zalo/FB (#1)**
- Vì sao:
  1. **Tần suất lặp lại cao & tác động trực tiếp tới doanh thu:** Xảy ra 40–60 lần/ngày ở các đại lý/shop bán sỉ lẻ; giảm thời gian phản hồi từ 5,5 phút xuống dưới 1,5 phút giúp tăng trực tiếp tỷ lệ chốt đơn trước khi khách hỏi shop đối thủ.
  2. **Rất khả thi để làm sản phẩm thật (MVP) và thương mại hóa (B2B SaaS):** Kiến trúc bài toán này phân tách rất rõ ràng và an toàn giữa **AI** (bóc tách tên hàng viết tắt/tự nhiên từ tin nhắn khách sang mã SKU chuẩn) và **Rule/Script** (tra bảng giá theo bậc chiết khấu và cộng tổng chính xác 100%, không lo LLM tính nhẩm sai số học). Có thể đóng gói thành Chrome Extension hoặc Webhook bot thu phí thuê bao hàng tháng (subscription).
  3. **Dễ kiểm chứng thực tế ngay trong buổi lab:** Có thể phỏng vấn trực tiếp các chủ shop / nhân viên sale online và lấy 10–20 tin nhắn hỏi giá thật để đo thời gian trước/sau.
- Câu hỏi muốn nhóm phản biện:
  - *"Bước nghẽn thật sự nằm ở việc đọc tin nhắn khách và tra bảng giá sỉ/lẻ trên Sheets, hay nằm ở việc dữ liệu tồn kho trên file Sheets không khớp với kho thực tế khiến sale phải nhắn hỏi thủ kho?"*
  - *"Nếu không dùng AI mà chỉ chuẩn hóa bảng Google Sheets có sẵn ô tìm kiếm gần đúng (fuzzy search) + công thức tính sẵn bậc chiết khấu (Rule/No AI) thì đã giải quyết được 70–80% thời gian chưa?"*

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Ở Card #1, nếu để LLM tự tính tổng tiền và áp phần trăm chiết khấu thì rất dễ xảy ra lỗi tính toán số học (hallucination về con số) gây thiệt hại tiền thật cho shop | Đồng ý hoàn toàn | Tách bạch rõ trong giả thuyết: AI chỉ bóc tách thực thể (tên hàng, số lượng) và khớp mã SKU; bước tra bậc giá và nhân/cộng tiền bắt buộc do **Rule/Script** thực hiện; nhân viên sale duyệt trước khi bấm gửi |
| Ở Card #2, ảnh đồng hồ điện nước chụp thực tế từ khách thuê gửi qua Zalo thường bị mờ, lóa đèn flash, góc nghiêng hoặc số đang kẹt nửa vòng quay, OCR rất dễ đọc sai số hàng chục/hàng đơn vị gây tranh cãi lớn | Đồng ý hoàn toàn | Thiết kế boundary và giao diện Human-in-the-loop: AI OCR nhận diện và hiển thị ảnh crop bên cạnh ô số để chủ trọ chỉ cần nhìn lướt xác nhận (1 click) trước khi xuất hóa đơn và gửi mã VietQR |
| Ở Card #3 (log tham số train model), AI chỉ ra rằng các công cụ như MLflow / Weights & Biases đã giải quyết phần lớn bài toán, nếu tự làm lại từ đầu sẽ thành "reinventing the wheel" | Đồng ý | Sửa lại cảm nhận nhanh của Card #3 từ **Workflow** sang **Rule (kết hợp Workflow nhẹ)** và bổ sung câu hỏi cần kiểm chứng xem vì sao người dùng không bật sẵn W&B/MLflow |
| AI gợi ý nâng cấp Card #1 thành "Agent tự động trả lời và tự chốt đơn thu tiền khách trên Zalo 24/7 không cần người" | Không đồng ý | Giữ mức can thiệp ở **Workflow** có con người kiểm duyệt (Human-in-the-loop), vì khách mua sỉ thường mặc cả hoặc hỏi điều kiện giao hàng đặc thù, nếu bot tự chốt sai chính sách sẽ làm mất khách lớn |

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
| CP1 Scan | Gợi ý mở rộng danh sách problem theo 4 lăng kính có tiềm năng thương mại hóa (B2B/SME) và chuẩn hóa cấu trúc câu Job Story ("Khi... tôi muốn... để...") | Giúp rà soát nhanh xem câu Job Story có vô tình gài giải pháp ("cần chatbot/AI...") vào trong mô tả vấn đề hay không; gợi ý thêm góc nhìn ở mảng TMĐT và trung tâm giáo dục | Ban đầu AI hay đưa ra các ý tưởng quá rộng ("trợ lý ảo toàn năng") hoặc thiếu các con số định lượng thực tế (tần suất, thời gian mất, thiệt hại chi phí) tại thị trường Việt Nam | Tự lọc bỏ các ý chung chung/rủi ro cao; tự bổ sung quy trình làm tay thực tế (Zalo, Excel, sao kê ngân hàng, Shopee) và ước lượng số phút/tần suất sát với vận hành thật của các shop/SME |
| CP2 Problem Card | Đóng vai một Product Manager hoài nghi để phản biện 3 Problem Card (kiểm tra xem quy trình có thật không, bottleneck có cụ thể không, rủi ro ảo giác số học và so sánh với phương án No AI/Rule) | Giúp phát hiện rủi ro chí mạng nếu để LLM tự tính tiền ở Card #1 (hallucination về số học) và chỉ ra các công cụ logging có sẵn ở Card #3 (W&B, MLflow) | AI có xu hướng vội vàng đề xuất biến bài toán thành "Autonomous Agent tự động hóa 100% không cần người duyệt", bỏ qua các tình huống thực tế của khách hàng tại Việt Nam | Giữ vững nguyên tắc Human-in-the-loop (con người kiểm tra trước khi gửi); phân tách rạch ròi bước nào dùng AI (bóc tách văn bản, OCR), bước nào dùng Rule/Code (nhân chia tiền, kiểm tra tồn kho, sinh mã VietQR) |
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
