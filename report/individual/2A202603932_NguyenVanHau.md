# Báo cáo cá nhân — 2A202603932_NguyenVanHau

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
| 6 | Cần đọc, tổng hợp nhiều thông tin | Khi tìm việc làm mới trong mùa tuyển dụng, tôi muốn quét và tổng hợp các tin tuyển dụng (JD) từ nhiều trang web (TopCV, ITviec, LinkedIn, VietnamWorks) để so khớp với kỹ năng trong CV của mình, để ứng tuyển nhanh các vị trí phù hợp nhất mà không phải mở từng web đọc thủ công hàng chục tab mỗi ngày | Người tìm việc / Ứng viên ngành CNTT & kỹ thuật (Fresher/Junior) | Diễn ra hàng ngày trong 1–3 tháng tìm việc; mỗi ngày mở 4–5 trang web đọc 30–50 JD mất 60–90 phút/ngày; nhiều tin yêu cầu kinh nghiệm thực tế không khớp với tiêu đề (ghi tuyển Junior nhưng yêu cầu 3 năm kinh nghiệm) làm mất công đọc |
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
| 2 | Quét tin tuyển dụng (JD) từ nhiều trang web để so khớp với CV (#6) | Nỗi đau thực tế, diễn ra hàng ngày của người tìm việc khi phải mở hàng chục tab trên 4–5 trang tuyển dụng; có tiềm năng thương mại hóa thành ứng dụng Job Matching (thu phí người tìm việc hoặc gói giới thiệu ứng viên cho doanh nghiệp); quy trình so khớp ngữ cảnh JD với CV phát huy rất tốt năng lực của AI | Các trang tuyển dụng lớn có chặn bot cào dữ liệu (anti-scraping) khi quét số lượng lớn JD không? |
| 3 | Tìm kiếm và tổng hợp mốc hạn chót từ Portal trường, LMS và email (#5) | Trải nghiệm đau thực tế lặp đi lặp lại hàng tuần của sinh viên/học viên khi học song song nhiều môn; quy trình rõ, dễ kiểm chứng ngay trong lớp học; có thể làm MVP dạng tiện ích mở rộng (extension) hoặc bot Telegram/Zalo | Cơ chế xác thực (SSO/Captcha) của các cổng thông tin trường có cho phép kết nối tự động an toàn không? |

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
| Job Story | Khi tìm kiếm cơ hội việc làm mới, tôi muốn quét và đối chiếu tự động các tin tuyển dụng (JD) mới đăng trên nhiều trang web (ITviec, TopCV, LinkedIn, VietnamWorks) với kỹ năng và kinh nghiệm trong CV của mình, để chọn ra các công việc phù hợp nhất để ứng tuyển trong ngày mà không phải lướt thủ công hàng chục tab trình duyệt |
| Actor | Ứng viên tìm việc ngành IT & công nghệ (Fresher, Junior, hoặc người đang chủ động tìm việc làm mới) |
| Thời điểm / bối cảnh | Hàng ngày vào các khung giờ cập nhật tin tuyển dụng (sáng 8h–9h hoặc chiều 17h–18h) trong giai đoạn cao điểm tìm việc kéo dài 1–3 tháng |
| Quy trình hiện tại (3–7 bước) | 1. Mở lần lượt 4–5 trang web việc làm (ITviec, TopCV, LinkedIn, VietnamWorks) · 2. Nhập từ khóa chuyên môn (ví dụ "Python", "Data", "AI", "Frontend"), chọn bộ lọc địa điểm và cấp bậc (Fresher/Junior) · 3. Bấm mở 20–30 tin tuyển dụng (JD) ra các tab trình duyệt khác nhau · 4. Đọc chi tiết từng JD: mức lương, số năm kinh nghiệm thật, tech stack bắt buộc và đãi ngộ để so sánh với CV của bản thân · 5. Lưu lại 3–5 link JD phù hợp nhất vào bảng Notion/Sheets hoặc gửi CV ứng tuyển ngay |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 & Bước 4 (Mở 20–30 tab đọc lướt nội dung JD, bóc tách yêu cầu kinh nghiệm thật ẩn dưới mô tả và so khớp với năng lực trong CV): mất 45–60 phút mỗi ngày; nhiều tin tuyển dụng bị trùng lặp giữa các trang hoặc ghi tiêu đề Junior nhưng nội dung đòi hỏi 2–3 năm kinh nghiệm làm mất công đọc |
| Impact (nếu không giải thì sao) | Mất 6–8 giờ/tuần chỉ để tìm kiếm và sàng lọc JD thủ công; ứng viên nộp chậm sau 2–3 ngày thường bị trôi hồ sơ xuống cuối danh sách của nhà tuyển dụng (giảm 40% cơ hội được gọi phỏng vấn); nộp nhầm các JD không khớp thực tế làm mất thời gian phỏng vấn hỏng |
| Success metric (baseline → target) | Thời gian quét và tìm các JD phù hợp trong ngày giảm từ **75 phút/ngày** xuống **dưới 10 phút/ngày**; tỷ lệ JD được đề xuất khớp thực tế trên 80% tiêu chí trong CV đạt **trên 85%**; không bỏ sót tin tuyển dụng mới đăng trong vòng 24 giờ |
| Phương án không dùng AI | Đăng ký tính năng "Job Alert qua email" của từng trang tuyển dụng: email tự động gửi tin mới về hộp thư mỗi ngày, nhưng chỉ lọc theo từ khóa cứng (keyword search thô) nên nhận về rất nhiều tin rác (Senior đòi 5 năm kinh nghiệm hoặc ngành khác), người dùng vẫn phải mở từng link đọc lại thủ công |
| Giả thuyết về AI (nếu có) | Rule/script quét và gom các JD mới đăng trong ngày từ các trang web việc làm; AI (LLM) đọc văn bản JD để bóc tách yêu cầu thực chất (kinh nghiệm thật, tech stack cốt lõi, đãi ngộ), sau đó so khớp ngữ cảnh với CV của người dùng để chấm điểm phù hợp (Match Score) kèm 2–3 gạch đầu dòng giải thích điểm mạnh/yếu; người dùng chỉ cần mở 1 bảng tổng hợp để duyệt và bấm ứng tuyển |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 75 phút/ngày (~6–8 giờ/tuần trong đợt tìm việc)

[1. Mở 4–5 trang web tuyển dụng & gõ từ khóa: 10']
→ [2. Mở 20–30 tab JD có tiêu đề liên quan: 15']
→ [3. Đọc chi tiết từng JD & bóc tách yêu cầu thật: 35'] ← BOTTLENECK (phần 1)
→ [4. So sánh với CV cá nhân & lọc tin rác/trùng: 10'] ← BOTTLENECK (phần 2)
→ [5. Lưu link phù hợp vào Sheets & gửi CV: 5']
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi tìm kiếm thông báo học vụ, lịch thi và quy định nộp bài trên cổng thông tin trường, LMS và email, tôi muốn biết ngay các mốc hạn chót trong tuần của mình, để không bị trễ hạn |
| Actor | Sinh viên / Học viên đại học hoặc các khóa đào tạo kỹ thuật có lịch học và bài tập dày đặc (đang theo học 4–6 môn song song) |
| Thời điểm / bối cảnh | Đầu mỗi tuần (sáng thứ Hai) và trước các tuần thi giữa kỳ/cuối kỳ, khi giảng viên các môn liên tục cập nhật thông báo dời hạn, giao thêm bài tập phụ trên các kênh khác nhau |
| Quy trình hiện tại (3–7 bước) | 1. Đăng nhập cổng thông tin đào tạo (Portal trường) xem lịch thi và thông báo chung của khoa/trường · 2. Đăng nhập hệ thống LMS (Canvas/Moodle/Google Classroom) của từng môn để kiểm tra mục thông báo và deadline bài tập tuần · 3. Mở hòm thư sinh viên (Gmail/Outlook) đọc email từ giảng viên hoặc trợ giảng về việc sửa đề/dời lịch nộp · 4. Lướt qua các nhóm chat Zalo/Discord môn học để xem thông báo quan trọng có bị bỏ sót không · 5. Tự ghi chép các hạn chót và lịch thi sắp tới vào sổ tay hoặc app Google Calendar/Notion |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2, Bước 3 & Bước 4 (Đăng nhập lần lượt 4–5 hệ thống rời rạc, đọc các thông báo dài và đối chiếu ngày giờ hạn chót): mất 15–20 phút mỗi ngày (~90–120 phút/tuần), thông báo đổi hạn chót hay bị trôi lẫn trong hàng chục email và tin nhắn chat |
| Impact (nếu không giải thì sao) | Mất 1,5–2 giờ/tuần chỉ để rà soát lịch; trong mỗi học kỳ có khoảng 15–20% sinh viên từng bị nộp muộn ít nhất 1 bài tập hoặc lỡ bài kiểm tra phụ do không cập nhật kịp thông báo đổi lịch của giảng viên (bị trừ điểm chuyên cần hoặc nhận điểm 0 bài tập, ảnh hưởng điểm tổng kết GPA) |
| Success metric (baseline → target) | Thời gian tổng hợp hạn chót và lịch thi trong tuần giảm từ **90 phút/tuần** xuống **dưới 5 phút/tuần**; số sự cố nộp bài trễ hạn hoặc lỡ lịch thi do quên thông báo giảm từ **1–2 lần/kỳ** về **0 lần** |
| Phương án không dùng AI | Dùng tính năng đồng bộ lịch Google Calendar có sẵn của LMS hoặc cài app nhắc việc (Todoist, Notion): giúp hiển thị lịch nếu LMS có hỗ trợ xuất file `.ics`, nhưng hoàn toàn không đọc được các thông báo đổi lịch hoặc thông báo gia hạn đột xuất gửi qua email dạng văn xuôi hoặc tin nhắn Zalo của giảng viên |
| Giả thuyết về AI (nếu có) | Rule/Script tự động kéo thông báo mới từ LMS và email sinh viên (qua API/OAuth2); AI (LLM) đọc nội dung email/thông báo thông thường, trích xuất chính xác: môn học, tên bài tập/kỳ thi, thời hạn chót cũ và thời hạn chót mới; sau đó tự động cập nhật vào Google Calendar và gửi tin nhắn tóm tắt danh sách hạn chót trong tuần vào sáng thứ Hai |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — 90 phút/tuần (~15 phút/ngày x 6 ngày)

[1. Đăng nhập Portal trường xem lịch thi & thông báo: 3']
→ [2. Mở từng môn trên LMS kiểm tra deadline bài tập: 5'] ← BOTTLENECK (phần 1)
→ [3. Đọc email sinh viên & lọc thông báo đổi lịch: 4'] ← BOTTLENECK (phần 2)
→ [4. Check tin nhắn nhóm lớp Zalo/Discord: 2']
→ [5. Ghi hạn chót vào Google Calendar/Notion: 1']
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
| Ở Card #1, nếu để LLM tự tính tổng tiền và áp phần trăm chiết khấu thì rất dễ xảy ra lỗi tính toán số học (hallucination về con số) gây thiệt hại tiền thật cho shop | Đồng ý | Tách bạch rõ trong giả thuyết: AI chỉ bóc tách thực thể (tên hàng, số lượng) và khớp mã SKU; bước tra bậc giá và nhân/cộng tiền bắt buộc do **Rule/Script** thực hiện; nhân viên sale duyệt trước khi bấm gửi |
| Ở Card #2 (quét JD từ nhiều trang web), các trang web việc làm như LinkedIn, TopCV thường có cơ chế chặn bot cào dữ liệu (anti-scraping, Cloudflare, rate-limit), nếu cố tình crawl tự động từ server sẽ dễ bị chặn IP | Đồng ý | Thiết kế giải pháp kỹ thuật dạng Chrome Extension chạy trực tiếp trên phiên duyệt web của người dùng (client-side) hoặc tận dụng RSS feed/API đối tác công khai, không xây hệ thống backend crawl dữ liệu chui |
| Ở Card #3 (tổng hợp deadline học vụ), việc tự động đăng nhập vào Portal trường thường vấp phải rào cản xác thực (SSO, OTP, Captcha) và vi phạm chính sách bảo mật của trường nếu dùng bot cào dữ liệu | Đồng ý | Xác định rõ boundary trong giải pháp: Chỉ tích hợp dữ liệu từ các kênh chuẩn hóa có cấp quyền (LMS iCal link, Google Classroom API và email cá nhân được cấp quyền OAuth2); không viết bot giải Captcha hay đăng nhập chui qua Portal trường |
| AI gợi ý nâng cấp Card #1 thành "Agent tự động trả lời và tự chốt đơn thu tiền khách trên Zalo 24/7 không cần người" | Không đồng ý | Giữ mức can thiệp ở **Workflow** có con người kiểm duyệt (Human-in-the-loop), vì khách mua sỉ thường mặc cả hoặc hỏi điều kiện giao hàng đặc thù, nếu bot tự chốt sai chính sách sẽ làm mất khách lớn |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Pitch 3 Problem Cards cá nhân (Báo giá sỉ/lẻ Zalo/FB, Quét JD so khớp CV, Hạn chót học vụ LMS/Email) với đầy đủ quy trình, bottleneck và số liệu định lượng | Đóng góp 3 candidate rõ ràng về quy trình và bottleneck vào kho 12 candidate chung của nhóm |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: *"Nếu app ShopeeFood không mở API backend, nhóm lấy đâu ra dữ liệu GPS tài xế thời gian thực để AI dự báo? Liệu giải pháp Rule đếm ngược 5–7 phút có giải quyết được 80% vấn đề mà không cần đến AI không?"* | Giúp nhóm nhận diện sớm rào cản Feasibility, tránh sa đà vào việc vẽ ra mô hình AI dự báo bất khả thi |
| Nhận phản biện | Câu hỏi tôi nhận được: *"Ở Card #1 (Báo giá sỉ/lẻ), nếu dùng Google Sheets có sẵn bộ lọc và hàm lookup thì đã giải quyết được chưa mà cần đến AI?"* | Tôi đã sửa gì: Thừa nhận vai trò của Rule trong việc tra bảng giá và tính toán số học, chỉ giữ AI ở bước đọc hiểu văn bản tự nhiên viết tắt của khách trên Zalo để khớp mã SKU |
| Gom cluster / cây OST | | |
| Chọn candidate problem | Tham gia thảo luận bảng chấm điểm shortlist 3 bài toán; đồng thuận chọn bài ShopeeFood | Thống nhất chọn ShopeeFood vì có tính khả thi kiểm chứng cao nhất trong buổi lab (dễ phỏng vấn và trích xuất lịch sử đơn thật) |
| Kiểm chứng / research | Hỗ trợ kiểm chứng & research | |
| Quy trình nhóm |  |  |
| Problem Statement | Tham gia xây dựng Problem Statement v0 và hoàn thiện bản v1 có bổ sung Boundary và Tiêu chí đánh giá bản nháp | Đảm bảo Problem Statement không chứa từ khóa giải pháp, có metric đo lường định lượng và ranh giới an toàn (không tự ý hủy đơn của khách) |
| Mức can thiệp AI | Phân tích ma trận độ mơ hồ × độ phức tạp, so sánh 4 mức (No AI, Rule, Workflow, Agent) và đánh giá 2 câu hỏi Google PAIR |  |
| Quyết định | Tham gia đánh giá 4 rủi ro và thiết kế kịch bản pilot  | Nhóm thống nhất chốt quyết định **GO, phạm vi nhỏ** với giải pháp Rule-based; giữ quyền tự quyết cho người dùng|

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Gợi ý mở rộng danh sách problem theo 4 lăng kính có tiềm năng thương mại hóa (B2B/SME) và chuẩn hóa cấu trúc câu Job Story ("Khi... tôi muốn... để...") | Giúp rà soát nhanh xem câu Job Story có vô tình gài giải pháp ("cần chatbot/AI...") vào trong mô tả vấn đề hay không; gợi ý thêm góc nhìn ở mảng TMĐT và trung tâm giáo dục | Ban đầu AI hay đưa ra các ý tưởng quá rộng ("trợ lý ảo toàn năng") hoặc thiếu các con số định lượng thực tế (tần suất, thời gian mất, thiệt hại chi phí) tại thị trường Việt Nam | Tự lọc bỏ các ý chung chung/rủi ro cao; tự bổ sung quy trình làm tay thực tế (Zalo, Excel, sao kê ngân hàng, Shopee) và ước lượng số phút/tần suất sát với vận hành thật của các shop/SME |
| CP2 Problem Card | Đóng vai một Product Manager hoài nghi để phản biện 3 Problem Card (kiểm tra quy trình thực tế, rủi ro ảo giác số học ở Card #1, rào cản kỹ thuật anti-scraping ở Card #2, và rào cản xác thực SSO/Captcha ở Card #3) | Giúp phát hiện rủi ro chí mạng nếu để LLM tự tính tiền ở Card #1 (hallucination về số học) và chỉ ra rào cản bị chặn bot nếu crawl JD tự động ở Card #2 | AI có xu hướng vội vàng đề xuất biến cả 3 bài toán thành "Autonomous Agent tự động hóa 100% không cần người duyệt" (như tự gửi CV ứng tuyển hoặc tự gửi báo giá) | Giữ vững nguyên tắc Human-in-the-loop (con người kiểm tra trước khi gửi); phân tách rạch ròi bước nào dùng AI (bóc tách văn bản, so khớp ngữ cảnh JD với CV), bước nào dùng Rule/Code (nhân chia tiền, kiểm tra tồn kho, đồng bộ calendar) |
| CP4 Research | Tìm kiếm các case study và giải pháp tương tự trên thế giới về bài toán theo dõi trạng thái giao vận (Domino's Pizza Tracker, GrabFood, Uber Eats) | Cung cấp nhanh thông tin tham khảo về cơ chế Status Transparency của Domino's và chính sách Latest Arrival By của Uber Eats | AI thường đề xuất các hệ thống AI điều phối logistics quy mô lớn của hãng vận tải, không liên quan đến góc nhìn người dùng cuối | Lọc bỏ các giải pháp backend nặng nề; chắt lọc bài học cốt lõi về trải nghiệm người dùng: minh bạch hóa các mốc trạng thái (Status Transparency) và cung cấp quyền tự quyết |
| CP5 Quy trình | Hỗ trợ chuẩn hóa định dạng sơ đồ quy trình dạng ASCII (Before/After) và tạo cấu trúc bảng phân tích 4 vai trò (Rule, Con người, Boundary, Fallback) | Giúp căn chỉnh format sơ đồ trực quan, nhanh chóng, đảm bảo rõ các mốc thời gian từng bước | AI có xu hướng tự ý thêm các bước "AI tự động gọi điện cho tài xế" hoặc "AI tự đặt đơn khác" vào sơ đồ quy trình tương lai | Loại bỏ hoàn toàn các bước tự động hóa tùy tiện đó; tái lập quy trình bám sát nguyên tắc Human-in-the-loop (hệ thống chỉ gửi cảnh báo, người dùng tự quyết định) |
| CP5–6 Problem Statement | Rà soát câu Problem Statement v0 và v1 theo các tiêu chí chuẩn (có bị gài giải pháp không, metric có đo được không, boundary có an toàn không) | Phát hiện câu chữ bị mơ hồ và gợi ý các tiêu chí đánh giá bản nháp (Success Criteria) rõ ràng | AI hay đề xuất các chỉ số viển vông như "tăng độ hài lòng 100%" hoặc "đoán trước ý định người dùng" | Đưa vào các chỉ số định lượng đo được bằng log và quan sát thực tế (giảm $\ge 30\%$ số lần mở app, giảm $\ge 50\%$ thời gian nhận biết đơn hủy) |
| CP6 Mức can thiệp / quyết định | So sánh 4 mức (No AI, Rule, Workflow, Agent), lập AI Canvas và trả lời 2 câu hỏi Google PAIR cho bài toán ShopeeFood | Giúp làm rõ rủi ro Báo nhầm (False Alarm) tệ hơn Bỏ sót (False Negative), làm cơ sở thiết kế thông báo an toàn | AI ban đầu hay đề xuất đưa sang mô hình AI dự báo phức tạp hoặc Agent tự động hủy/đặt đơn | Tôi kiên quyết thuyết phục nhóm chọn mức **Rule-based** vì bài toán có đúng/sai rõ ràng và thiếu dữ liệu nội bộ sàn; bảo vệ nguyên tắc giữ quyền kiểm soát cho con người |


---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
> Nhiều problems đến từ vấn đề đơn giản hàng ngày, không cần phải phức tạp.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**


**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

> Tôi đã đổi ý hoàn toàn ở vòng chấm điểm shortlist chọn candidate problem của nhóm. Ban đầu, tôi rất thích Card #1 của mình (Báo giá sỉ/lẻ qua Zalo/FB) vì tôi thấy bài toán này giải quyết nỗi đau vận hành của các shop online, có tiềm năng kinh doanh, Nhưng vì phạm vi của bài lab, phương án trên rất khó triển khai

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**
Không hẳn, tôi thấy tâm lý người dùng chung là như nhau.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**
> Phải nêu problem khách quan ,không đưa solution vào.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
Ngay từ bước scan phải xác định tính khả thi của các bước sau này lên problems.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

>. Bài toán của nhóm tập trung vào người đặt đồ ăn ShopeeFood, chịu rủi ro vì không biết đơn có được tài xế nhận hay nguy cơ bị hủy để kịp đổi quán khác. Trong quy trình 5 bước hiện tại, điểm nghẽn nằm ở 15p đầu khi khách hàng không nắm được thông tin. mức thành công là giảm $\ge 30\%$ số lần khách phải tự mở app canh chừng và giảm $\ge 50\%$ thời gian từ lúc đơn bị hủy đến khi khách nhận biết.
Phải đảm bảo không tự ý hủy đơn hay tự đặt lại món khác thay cho người dùng. Chọn **Rule-based** vì bài toán có ranh giới đúng/sai rõ ràng và nhóm không có dữ liệu nội bô cho AI. Cuối cùng, nhóm đưa ra quyết định **GO, phạm vi nhỏ** để triển khai một đợt pilot thử nghiệm Rule trong 2 tuần trên 10–20 đơn hàng thực tế nhằm kiểm chứng baseline và phản ứng của người dùng.S

---

## 7. Tài liệu tham khảo

- Google PAIR (People + AI Research) Guidebook: *Design patterns for Human-AI Interaction & Augment vs Automate*.
- Teresa Torres (2021), *Continuous Discovery Habits: Discover Products that Create Customer Value and Business Value*, Product Talk LLC.
- Marty Cagan (Silicon Valley Product Group), *Inspired: How to Create Tech Products Customers Love*, Wiley (Framework 4 Product Risks: Value, Usability, Feasibility, Viability).
- David Bland & Alex Osterwalder (2019), *Testing Business Ideas*, Strategyzer Series, Wiley (Assumption Mapping).
- Rob Fitzpatrick (2013), *The Mom Test: How to talk to customers & learn if your business is a good idea when everyone is lying to you*.
