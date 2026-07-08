---
title: "Nhật ký công việc Tuần 11"
date: 2024-01-01
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---
### Mục tiêu tuần 11:

* Thành thạo Ranh giới Quyền IAM để ngăn chặn leo thang đặc quyền và hạn chế quyền người dùng hiệu quả.
* Triển khai quản lý máy chủ toàn diện với AWS Systems Manager cho vận hành hạm đội tập trung.
* Thực hiện truy cập từ xa an toàn, vá lỗi tự động và thực thi lệnh trên nhiều phiên bản EC2.
* Dự án ITCoach: triển khai hạ tầng AWS hoàn chỉnh với hơn 15 dịch vụ và phát triển giao diện React TypeScript.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Nghiên cứu IAM Permission Boundary concepts<br>- Hiểu về effective permissions calculation<br>- Tạo Permission Boundary policy và test | 29/06/2026 | 29/06/2026 | <https://000030.awsstudygroup.com/> |
| 3 | - Tìm hiểu AWS Systems Manager: Session Manager, Patch Manager, Run Command<br>- Tạo IAM Role, launch EC2 instances<br>- Configure Patch Manager và Run Command<br>- Test Session Manager connections | 30/06/2026 | 30/06/2026 | <https://000031.awsstudygroup.com/> |
| 4 | **Dự án ITCoach:**<br>- Deploy frontend: S3 bucket, CloudFront, Route 53, ACM<br>- Tạo API Gateway REST API<br>- Deploy 8 Lambda functions với Node.js runtime | 01/07/2026 | 01/07/2026 | Nội bộ nhóm |
| 5 | **Dự án ITCoach:**<br>- Tạo 8 DynamoDB tables<br>- Setup Cognito User Pool và SQS queue<br>- Tạo 2 WAF Web ACLs (CloudFront + API Gateway)<br>- Setup CloudWatch Log Groups và SNS topics | 02/07/2026 | 02/07/2026 | Nội bộ nhóm |
| 6 | **Dự án ITCoach:**<br>- Phát triển React + TypeScript frontend<br>- Build components và integrate AWS Amplify SDK<br>- Deploy code: build React app và upload lên S3<br>- Deploy Lambda code và test integration | 03/07/2026 | 03/07/2026 | Nội bộ nhóm |

### Kết quả đạt được tuần 11:

**Thứ 2-3: AWS Labs - Permission Boundary + Systems Manager**

* **Thứ 2 - Permission Boundary (Bài 030):** Thành thạo Ranh giới Quyền IAM để ngăn chặn các cuộc tấn công leo thang đặc quyền. Tạo chính sách ranh giới quyền toàn diện để hạn chế khả năng của người dùng trong khi duy trì quyền truy cập vận hành. Thành công triển khai tính toán quyền hiệu quả và kiểm tra các tình huống mà người dùng không thể tạo người dùng IAM mới hoặc sửa đổi quyền hiện có mặc dù có chính sách quản trị được gắn kèm.

* **Thứ 3 - Systems Manager (Bài 031):** Triển khai giải pháp quản lý máy chủ toàn diện với Session Manager cho truy cập shell an toàn không cần khóa SSH, Patch Manager cho cập nhật hệ điều hành tự động trên toàn bộ hạm đội, và Run Command cho thực thi từ xa. Thiết lập quản lý tập trung giảm 80% chi phí vận hành đồng thời tăng cường tư thế bảo mật thông qua kết nối mã hóa và dấu vết kiểm toán.

**Thứ 4-6: Dự án ITCoach - Triển khai hạ tầng**

* **Triển khai 15 dịch vụ AWS:** Thành công triển khai hạ tầng không máy chủ hoàn chỉnh bao gồm S3/CloudFront cho giao diện, cổng API với 8 hàm Lambda, 8 bảng DynamoDB với chỉ mục phụ toàn cục, nhóm người dùng Cognito, hàng đợi SQS, bảo vệ tường lửa kép và giám sát CloudWatch toàn diện với thông báo SNS.

* **Phát triển giao diện React:** Xây dựng ứng dụng React TypeScript đáp ứng với khả năng ghi âm giọng nói, giao diện phản hồi trí tuệ nhân tạo, hệ thống trò chơi hóa và tích hợp bộ công cụ AWS Amplify. Triển khai giao diện người dùng hiện đại với Tailwind CSS và quản lý trạng thái hiệu quả.

* **Triển khai mã nguồn:** Hoàn thành triển khai từ đầu đến cuối với bản dựng React tối ưu tải lên S3, các hàm Lambda được đóng gói với phụ thuộc, cấu hình biến môi trường và kiểm tra tích hợp đầy đủ. Xác minh luồng người dùng từ đăng ký đến đánh giá AI và cập nhật điểm kinh nghiệm.

* **Chỉnh sửa hạ tầng:** Tinh chỉnh hạ tầng với sửa lỗi quyền IAM, tăng thời gian chờ Lambda lên 30 giây cho lệnh gọi API OpenAI, tối ưu quy tắc tường lửa dựa trên mẫu lưu lượng và triển khai giám sát toàn diện. Thiết lập đường cơ sở chi phí khoảng 17 đô la mỗi tháng qua trình khám phá chi phí AWS.

