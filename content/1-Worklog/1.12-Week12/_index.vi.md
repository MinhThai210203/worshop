---
title: "Nhật ký công việc Tuần 12"
date: 2024-01-01
weight: 12
chapter: false
pre: " <b> 1.12. </b> "
---
### Mục tiêu tuần 12:

* Tối ưu kích thước phiên bản EC2 với CloudWatch Agent và AWS Compute Optimizer để tiết kiệm chi phí.
* Thành thạo mã hóa dữ liệu lưu trữ với AWS KMS và triển khai ghi nhật ký kiểm toán toàn diện với CloudTrail.
* Truy vấn và phân tích nhật ký bảo mật bằng Amazon Athena để tuân thủ và giám sát.
* Dự án ITCoach: thực hiện kiểm tra toàn diện, tối ưu hiệu năng web, ổn định hạ tầng và hoàn thành triển khai sản xuất.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Nghiên cứu CloudWatch và CloudWatch Agent<br>- Tìm hiểu EC2 Right Sizing và cost optimization<br>- Cài đặt CloudWatch Agent, configure metrics collection<br>- Bật AWS Compute Optimizer và analyze instance | 06/07/2026 | 06/07/2026 | <https://000032.awsstudygroup.com/> |
| 3 | - Nghiên cứu AWS KMS và encryption concepts<br>- Tạo Customer Managed Key (CMK)<br>- Tạo S3 bucket với KMS encryption<br>- Setup CloudTrail logging và Athena | 07/07/2026 | 07/07/2026 | <https://000033.awsstudygroup.com/> |
| 4 | **Dự án ITCoach:**<br>- Kiểm tra toàn diện functional và integration testing<br>- Test tất cả user flows end-to-end<br>- Load testing với 100 concurrent users<br>- Security testing: WAF, authentication, SSL/TLS | 08/07/2026 | 08/07/2026 | Nội bộ nhóm |
| 5 | **Dự án ITCoach:**<br>- Cải thiện UI/UX và sửa bugs<br>- Performance optimization: lazy loading, giảm bundle size<br>- Setup monitoring đầy đủ: Dashboard, alerts, X-Ray tracing | 09/07/2026 | 09/07/2026 | Nội bộ nhóm |
| 6 | **Dự án ITCoach:**<br>- Ổn định hạ tầng và optimize chi phí<br>- Viết documentation: deployment runbook, API docs, troubleshooting guide<br>- Hoàn thành dự án: deploy lên production https://itcoach24h.xyz | 10/07/2026 | 10/07/2026 | Nội bộ nhóm |

### Kết quả đạt được tuần 12:

**Thứ 2-3: AWS Labs - CloudWatch/Compute Optimizer + KMS/CloudTrail**

* **CloudWatch & Compute Optimizer:** Triển khai CloudWatch Agent để thu thập số liệu bộ nhớ và ổ đĩa. Phân tích hiệu suất EC2 với Compute Optimizer, tiết kiệm 50% chi phí bằng cách giảm kích thước từ t3.large xuống t3.medium. Tạo bảng điều khiển trực quan cho giám sát thời gian thực.

* **KMS & CloudTrail:** Nắm vững mã hóa dữ liệu với KMS, tạo khóa tùy chỉnh và bật xoay tự động. Triển khai CloudTrail để ghi nhật ký kiểm toán, truy vấn nhật ký với Athena. Tối ưu chi phí KMS giảm 99% lệnh gọi API.

**Thứ 4-6: Dự án ITCoach - Kiểm tra toàn diện và hoàn thành**

* **Kiểm tra toàn diện:** Thực hiện kiểm tra chức năng từ đầu đến cuối cho tất cả luồng người dùng (đăng ký → đăng nhập → chọn câu hỏi → ghi âm → đánh giá AI → cập nhật điểm kinh nghiệm). Kiểm tra tích hợp trên hơn 15 dịch vụ AWS. Kiểm tra tải với 100 người dùng đồng thời đạt thời gian phản hồi trung bình dưới 250ms. Kiểm tra bảo mật tường lửa, luồng xác thực và mã hóa HTTPS.

* **Tối ưu web:** Cải thiện trải nghiệm người dùng với giao diện ghi âm nâng cao, chế độ tối và thông báo tương tác. Tối ưu hiệu năng giao diện với tải lười và chia tách mã, giảm 50% kích thước gói (3.2MB → 1.6MB). Cải thiện thời gian tải trang từ 4.5 giây xuống 2.1 giây.

* **Ổn định hạ tầng:** Thiết lập giám sát toàn diện với bảng điều khiển CloudWatch, hơn 15 cảnh báo cho tình trạng hệ thống và theo dõi phân tán AWS X-Ray. Hoàn thiện tối ưu chi phí ở mức khoảng 20-22 đô la mỗi tháng bao gồm API OpenAI. Tạo tài liệu kỹ thuật đầy đủ bao gồm sổ tay triển khai và tài liệu API.

* **Hoàn thành dự án:** Triển khai thành công hệ thống sản xuất lên `https://itcoach24h.xyz`. Tất cả 15 dịch vụ AWS hoạt động ổn định với bảo vệ tường lửa kép, mã hóa HTTPS đầy đủ và xác thực Cognito. Nền tảng ITCoach sẵn sàng phục vụ người dùng như hệ thống luyện phỏng vấn IT với trí tuệ nhân tạo hoàn chỉnh trên kiến trúc không máy chủ AWS.

