---
title: "Nhật ký công việc Tuần 9"
date: 2024-01-01
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---
### Mục tiêu tuần 9:

* Triển khai hoàn chỉnh đường ống CI/CD với AWS CodePipeline, CodeBuild và CodeDeploy để phân phối phần mềm tự động.
* Cấu hình tích hợp Git với AWS CodeCommit và quy trình triển khai tự động.
* Triển khai giải pháp lưu trữ hybrid với AWS Storage Gateway để tích hợp liền mạch từ on-premises lên cloud.
* Khởi động dự án ITCoach: lên ý tưởng nền tảng phỏng vấn với AI và thiết kế kiến trúc hệ thống.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Nghiên cứu AWS CI/CD services ecosystem<br>- Chuẩn bị infrastructure: VPC, Security Groups, S3 bucket<br>- Tạo IAM roles cho CI/CD services<br>- Install và configure CodeDeploy Agent trên EC2 | 15/06/2026 | 15/06/2026 | <https://000023.awsstudygroup.com/> |
| 3 | - Tạo AWS CodeCommit repository và configure Git credentials<br>- Tạo CodeBuild, CodeDeploy, CodePipeline<br>- Test CI/CD pipeline end-to-end<br>- Tìm hiểu AWS Storage Gateway và triển khai File Gateway | 16/06/2026 | 16/06/2026 | <https://000023.awsstudygroup.com/><br><https://000024.awsstudygroup.com/> |
| 4 | **Dự án ITCoach:**<br>- Brainstorming ý tưởng platform luyện phỏng vấn IT<br>- Phân tích bài toán và giải pháp<br>- Vẽ sơ đồ kiến trúc AWS Serverless<br>- Thiết kế database schema sơ bộ (8 bảng DynamoDB) | 17/06/2026 | 17/06/2026 | Nội bộ nhóm |
| 5 | **Dự án ITCoach:**<br>- Thiết kế chi tiết 8 bảng DynamoDB với partition/sort keys<br>- Định nghĩa API endpoints và request/response schema<br>- Chuẩn bị slide thuyết trình kiến trúc | 18/06/2026 | 18/06/2026 | Nội bộ nhóm |
| 6 | **Dự án ITCoach:**<br>- Trình bày ý tưởng và thiết kế cho nhóm<br>- Nhận feedback từ mentor về kiến trúc<br>- Ghi chú các góp ý cải thiện | 19/06/2026 | 19/06/2026 | Nội bộ nhóm |

### Kết quả đạt được tuần 9:

**Thứ 2-3: AWS Labs - CI/CD Pipeline + Storage Gateway**

* **Thứ 2 - CI/CD Pipeline (Bài 023):** Thành thạo AWS CodePipeline, CodeBuild, CodeDeploy và CodeCommit. Chuẩn bị hạ tầng đầy đủ với VPC, nhóm bảo mật và xô S3. Tạo vai trò IAM cho các dịch vụ CI/CD và cài đặt tác nhân CodeDeploy trên EC2. Hoàn thành đường ống CI/CD 3 giai đoạn với triển khai tự động khi commit mã nguồn.

* **Thứ 3 - Storage Gateway (Bài 024):** Nghiên cứu các loại Storage Gateway và triển khai File Gateway thành công. Tạo và cấu hình chia sẻ tệp SMB/NFS, kết nối máy on-premises với đồng bộ tự động lên S3. Thực hiện giải pháp lưu trữ hybrid cho tích hợp on-premises liền mạch.

**Thứ 4-6: Dự án ITCoach - Lên ý tưởng và thiết kế kiến trúc**

* **Lên ý tưởng:** Phát triển nền tảng luyện phỏng vấn IT với trí tuệ nhân tạo nhằm giải quyết thiếu hụt kinh nghiệm phỏng vấn thực tế cho sinh viên IT. Phân tích cạnh tranh với các nền tảng hiện có và xác định điểm khác biệt: đánh giá giọng nói AI chi tiết và yếu tố trò chơi hóa.

* **Thiết kế kiến trúc:** Thiết kế kiến trúc không máy chủ AWS toàn diện bao gồm giao diện React với mạng phân phối nội dung, cổng API với 8 hàm Lambda, cơ sở dữ liệu DynamoDB cho lưu trữ dữ liệu, Cognito cho xác thực, và bảo vệ tường lửa kép cho bảo mật nâng cao.

* **Lược đồ cơ sở dữ liệu:** Tạo thiết kế sơ bộ cho 8 bảng DynamoDB với khóa phân vùng và khóa sắp xếp phù hợp, lập kế hoạch mẫu truy cập dữ liệu để tối ưu hiệu suất.

* **Trình bày nhóm:** Thành công trình bày kiến trúc hệ thống và khái niệm thiết kế cho nhóm. Nhận được góp ý có giá trị từ người hướng dẫn và ghi chép các đề xuất cải thiện cho các giai đoạn phát triển tiếp theo.
