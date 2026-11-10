# Nhóm 911 — Day 02 Discovery & Problem Framing

## Thông tin nhóm

- Tên nhóm: 911
- Repo chung: https://github.com/MinhTrannnnn/K5-L3B-DAY02-911-DiscoveryProblemFraming
- Candidate problem nhóm chọn: Khi đơn ShopeeFood chờ tài xế hoặc tiến độ chưa rõ, người đặt cần biết lúc nào nên kiểm tra và quyết định tiếp tục chờ hay đổi phương án ăn trước khi quá muộn.
- Quyết định cuối: **Go — thử nghiệm nhỏ bằng Rule theo mốc thời gian**; chưa triển khai dự báo bằng AI.

## Thành viên

Nhóm có 5 thành viên theo chấp thuận của lab coach. Mỗi người tự điền tài khoản GitHub của mình; Kim tự điền MSSV khi thêm báo cáo cá nhân.

| STT | Họ và tên | MSSV | Vai trò trong nhóm | Tài khoản GitHub |
|---:|---|---|---|---|
| 1 | Lê Quân Bảo | 2A202603888 | Lead CP3; hỗ trợ CP5 | [LeBao403](https://github.com/LeBao403) |
| 2 | Trần Quang Minh | 2A202603929 | Lead CP4; hỗ trợ CP3 | [MinhTrannnnn](https://github.com/MinhTrannnnn) |
| 3 | Nguyễn Hải Quang | 2A202603936 | Lead CP5; hỗ trợ CP4 | Tự điền |
| 4 | Nguyễn Văn Hậu | 2A202603932 | Đồng lead CP6; hỗ trợ CP4 | Tự điền |
| 5 | Nguyễn Bá Kim | Tự điền | Đồng lead CP6; hỗ trợ CP5 | Tự điền |

Không ghi email hoặc số điện thoại của thành viên và người được phỏng vấn vào repo.

## Phân công theo checkpoint

| Checkpoint | Người chính | Người hỗ trợ | Sản phẩm trong báo cáo nhóm |
|---|---|---|---|
| CP3 — Hội tụ nhóm | Lê Quân Bảo | Trần Quang Minh | Pitch, cluster, Opportunity Solution Tree và shortlist ở mục 2. |
| CP4 — Kiểm chứng | Trần Quang Minh | Nguyễn Hải Quang, Nguyễn Văn Hậu | Assumption map, ba interview snapshot và điều chỉnh problem ở mục 3.1–3.2. |
| CP4 — Research | Trần Quang Minh | Nguyễn Văn Hậu, Nguyễn Hải Quang | Bảng đối chiếu giải pháp có nguồn ở mục 3.3. |
| CP5 — Quy trình trước/sau | Nguyễn Hải Quang | Lê Quân Bảo, Nguyễn Bá Kim | Luồng hiện tại/tương lai và bảng before/after ở mục 4; Quang bổ sung số liệu baseline đã đo. |
| CP5 — Problem Statement v0 | Nguyễn Hải Quang | Lê Quân Bảo, Nguyễn Bá Kim | Problem Statement v0 ở mục 5. |
| CP6 — Mức can thiệp + Problem Statement v1 | Nguyễn Văn Hậu, Nguyễn Bá Kim | — | So sánh No AI/Rule/Workflow/Agent, boundary, tiêu chí đánh giá và v1 ở mục 6–7. |
| CP6 — Quyết định | Nguyễn Văn Hậu, Nguyễn Bá Kim | — | Bốn rủi ro, quyết định và pilot ở mục 8. |

## Đóng góp cá nhân

Các mục dưới đây ghi phân công và phần thể hiện trong [báo cáo nhóm](report/team/group_report.md). Mỗi thành viên tự xác nhận việc mình thực sự làm, bổ sung tài khoản GitHub/commit và viết điều học được của chính mình.

### LeQuanBao-2A202603888

- **Phần việc phụ trách:** Lead CP3; hỗ trợ Quang ở CP5.
- **Đóng góp thể hiện trong báo cáo:** Tổng hợp bảng pitch, nhóm các candidate, dựng cây cơ hội và bảng chấm shortlist; hỗ trợ rà quy trình trước/sau và mốc bottleneck.
- **Bằng chứng:** `report/team/group_report.md` mục 2 và mục 4–5; commit của Bảo trên nhánh `2A202603888` và `main`.
- **Điều học được từ phần nhóm:** Nhận ra tầm quan trọng của việc gạt bỏ tư duy công nghệ làm trước để tập trung mổ xẻ đúng nỗi đau người dùng; hiểu rõ ranh giới giữa quy tắc thông thường với can thiệp mô hình và biết cách phối hợp nhịp nhàng giữa phân tích luồng di chuyển thực tế với tính khả thi hệ thống.

### TranQuangMinh-2A202603929

- **Phần việc phụ trách:** Lead CP4; hỗ trợ Bảo ở CP3; đề xuất Problem Card #8 ShopeeFood.
- **Đóng góp thể hiện trong báo cáo:** Đưa trải nghiệm đặt món vào phần pitch; tổng hợp ba câu trả lời của người ngoài nhóm, assumption map và bảng research; thu hẹp problem sau kiểm chứng.
- **Bằng chứng:** `report/team/group_report.md` mục 2.1, 3.1–3.3; `report/individual/2A202603929_TranQuangMinh.md` mục 2–3; bổ sung commit của Minh.
- **Điều học được từ phần nhóm:** Qua quá trình làm việc nhóm, tôi học được cách xác định và phân tích một vấn đề dựa trên bằng chứng thực tế thay vì chỉ dựa vào cảm nhận cá nhân. Đặc biệt, khi phụ trách CP4, tôi nhận ra tầm quan trọng của việc phỏng vấn người dùng, kiểm chứng các giả định và đối chiếu với những thông tin nghiên cứu để hiểu rõ nguyên nhân của vấn đề. Bên cạnh đó, việc trao đổi và phản biện với các thành viên giúp tôi nhìn nhận vấn đề từ nhiều góc độ và biết cách thu hẹp phạm vi để tập trung vào khó khăn cốt lõi của người dùng. Tôi cũng hiểu rằng không phải vấn đề nào cũng cần áp dụng AI, mà quan trọng nhất là lựa chọn giải pháp phù hợp, có tính khả thi và thực sự mang lại giá trị.

### NguyenHaiQuang-2A202603936

- **Phần việc phụ trách:** Lead CP5; hỗ trợ Minh ở CP4.
- **Đóng góp thể hiện trong báo cáo:** Phụ trách quy trình trước/sau, bảng so sánh và Problem Statement v0; hỗ trợ kiểm chứng với người dùng. Quang đã đo baseline; cần tự bổ sung số mẫu và các mốc đo vào mục 4–5 để đối chiếu với mục tiêu pilot.
- **Bằng chứng:** `report/team/group_report.md` mục 3–5; `report/individual/2A202603936_NguyenHaiQuang.md`; bổ sung dữ liệu và commit của Quang.
- **Điều học được từ phần nhóm:** Quang tự điền.

### NguyenVanHau-2A202603932

- **Phần việc phụ trách:** Đồng lead CP6; hỗ trợ Minh ở CP4.
- **Đóng góp thể hiện trong báo cáo:** Hỗ trợ research và phản biện khả năng dùng dữ liệu giao thông; so sánh bốn mức can thiệp, rủi ro và quyết định pilot.
- **Bằng chứng:** `report/team/group_report.md` mục 3.3 và 6–8; `report/individual/2A202603932_NguyenVanHau.md`; bổ sung commit của Hậu.
- **Điều học được từ phần nhóm:** Hậu tự điền.

### NguyenBaKim-MSSV_TuDien

- **Phần việc phụ trách:** Đồng lead CP6; hỗ trợ Quang ở CP5.
- **Đóng góp thể hiện trong báo cáo:** Phản biện boundary và bước người dùng kiểm tra/xác nhận; cùng Hậu rà bốn mức can thiệp, tiêu chí đánh giá và quyết định pilot.
- **Bằng chứng:** `report/team/group_report.md` mục 4–8; Kim bổ sung báo cáo cá nhân và commit của mình.
- **Điều học được từ phần nhóm:** Kim tự điền.
