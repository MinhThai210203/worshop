---
title: "Nhật ký công việc Tuần 10"
date: 2024-01-01
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---
### Mục tiêu tuần 10:

* Triển khai AWS WAF để bảo vệ ứng dụng web khỏi các tấn công phổ biến (SQL injection, XSS, DDoS).
* Thành thạo chiến lược gắn thẻ tài nguyên toàn diện và Nhóm tài nguyên để tổ chức tài nguyên hiệu quả.
* Triển khai chính sách IAM dựa trên thẻ (ABAC) để kiểm soát truy cập dựa trên thẻ tài nguyên cho quản trị nâng cao.
* Dự án ITCoach: hoàn thiện thiết kế hệ thống, hoàn thành lược đồ cơ sở dữ liệu chi tiết và định nghĩa các điểm cuối API.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Nghiên cứu AWS WAF và OWASP Top 10 vulnerabilities<br>- Tạo Web ACL, configure managed rules và rate-based rules<br>- Tạo custom rules: SQL injection, XSS protection | 22/06/2026 | 22/06/2026 | <https://000026.awsstudygroup.com/> |
| 3 | - Enable WAF logging và analyze logs<br>- Nghiên cứu resource tagging strategies<br>- Tag resources và tạo Resource Groups<br>- Implement IAM tag-based access control (ABAC) | 23/06/2026 | 23/06/2026 | <https://000026.awsstudygroup.com/><br><https://000027.awsstudygroup.com/><br><https://000028.awsstudygroup.com/> |
| 4 | **Dự án ITCoach:**<br>- Review feedback từ tuần trước và điều chỉnh kiến trúc<br>- Bổ sung SQS cho async AI processing<br>- Finalize database schema cho 8 bảng DynamoDB | 24/06/2026 | 24/06/2026 | Nội bộ nhóm |
| 5 | **Dự án ITCoach:**<br>- Thiết kế chi tiết API endpoints với schema<br>- Thiết kế GSI cho query patterns<br>- Lập checklist hạ tầng: 15+ AWS services | 25/06/2026 | 25/06/2026 | Nội bộ nhóm |
| 6 | **Dự án ITCoach:**<br>- Estimate chi phí: ~$12-20/tháng AWS + $1-5 OpenAI<br>- Hoàn thiện tài liệu thiết kế<br>- Cập nhật sơ đồ kiến trúc phiên bản cuối | 26/06/2026 | 26/06/2026 | Nội bộ nhóm |

### Kết quả đạt được tuần 10:

**Thứ 2-3: AWS Labs - WAF + Resource Tagging**

* **Thứ 2 - AWS WAF (Bài 026):** Thành thạo kiến trúc WAF và bảo vệ các lỗ hổng OWASP Top 10. Triển khai thành công Web ACL với quy tắc quản lý cho phòng chống SQL injection và XSS. Cấu hình quy tắc dựa trên tốc độ để chống DDoS và quy tắc tùy chỉnh cho các mối đe dọa cụ thể. Bật ghi nhật ký và giám sát toàn diện qua CloudWatch cho phân tích bảo mật.

* **Thứ 3 - Resource Tagging (Bài 027+028):** Triển khai chiến lược gắn thẻ cấp doanh nghiệp với phân loại chuẩn hóa (Môi trường, Trung tâm chi phí, Dự án, Chủ sở hữu). Tạo chính sách gắn thẻ tự động qua giao diện điều khiển và thao tác dòng lệnh. Triển khai Nhóm tài nguyên để quản lý hiệu quả và thực hiện kiểm soát truy cập IAM dựa trên thẻ (ABAC) cho quản trị bảo mật nâng cao.

**Thứ 4-6: Dự án ITCoach - Hoàn thiện thiết kế**

* **Hoàn thiện thiết kế:** Hoàn thành kiến trúc hệ thống tích hợp tất cả góp ý từ các buổi đánh giá trước. Tăng cường thiết kế với các lớp bảo mật bổ sung và tối ưu luồng dữ liệu. Tạo tài liệu kỹ thuật toàn diện sẵn sàng cho giai đoạn triển khai.

* **Cơ sở dữ liệu chi tiết:** Hoàn thiện thiết kế cơ sở dữ liệu với 8 bảng DynamoDB bao gồm primary keys, sort keys và Global Secondary Indexes. Định nghĩa mối quan hệ dữ liệu, mẫu truy cập và chiến lược tối ưu truy vấn. Thiết lập thực hành tốt nhất về mô hình dữ liệu cho khả năng mở rộng.

* **Điểm cuối API:** Tài liệu hóa 25+ REST API endpoints trên 7 nhóm chức năng (Authentication, Questions, Sessions, Answers, Quiz, Gamification, Results). Định nghĩa đầy đủ lược đồ yêu cầu/phản hồi, xử lý lỗi và yêu cầu xác thực cho từng endpoint.

* **Danh sách kiểm tra hạ tầng:** Tạo danh sách kiểm tra triển khai toàn diện bao gồm 15+ dịch vụ AWS như giao diện (S3, CloudFront, Route 53), máy chủ (API Gateway, Lambda, DynamoDB), bảo mật (WAF, Cognito) và giám sát (CloudWatch, SNS). Thiết lập ước tính chi phí và quy trình vận hành.
