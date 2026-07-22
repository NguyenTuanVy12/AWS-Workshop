---
title: "Tuần 11"
date: 2026-05-04
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---


### Mục tiêu tuần 11:

* Xây dựng quy trình tự động hóa triển khai ứng dụng (CI/CD Pipeline).
* Giám sát hệ thống, tối ưu hóa hiệu năng, chi phí và cấu hình các lớp bảo mật nâng cao cho đồ án (Giai đoạn 3).

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Thiết lập pipeline CI/CD (sử dụng GitHub Actions hoặc AWS CodePipeline) <br> - Tự động hóa quá trình chạy kiểm thử đơn vị, build Docker image và deploy lên ECS Fargate | 13/07/2026 | 13/07/2026 | |
| 3 | - Đăng ký tên miền và cấu hình phân giải DNS bằng Amazon Route 53 <br> - Tạo và liên kết SSL/TLS Certificate bằng AWS Certificate Manager (ACM) để kích hoạt HTTPS | 14/07/2026 | 14/07/2026 | |
| 4 | - Cấu hình giám sát tài nguyên chi tiết bằng CloudWatch Container Insights <br> - Thiết lập thông báo cảnh báo lỗi hệ thống về Discord/Slack/Email sử dụng Amazon SNS | 15/07/2026 | 15/07/2026 | |
| 5 | - Cấu hình CloudFront CDN làm tăng tốc độ phản hồi của Frontend <br> - Thiết lập Auto Scaling cho ECS Tasks dựa trên phần trăm CPU tiêu thụ | 16/07/2026 | 16/07/2026 | |
| 6 | - Triển khai tường lửa ứng dụng web AWS WAF để bảo vệ website khỏi tấn công cơ bản (SQL Injection, DDoS, XSS) <br> - Đánh giá hệ thống theo khung chuẩn AWS Well-Architected | 17/07/2026 | 17/07/2026 | |

### Kết quả đạt được tuần 11:

* Triển khai quy trình CI/CD hoàn chỉnh, giảm thiểu thời gian deploy thủ công xuống dưới 3 phút.
* Kích hoạt thành công bảo mật HTTPS trên tên miền tùy chỉnh, tăng độ tin cậy của dịch vụ.
* Tạo dashboard giám sát hiệu suất CPU/Memory và thiết lập cảnh báo chủ động khi có sự cố.
* Hệ thống tự động scale-out tăng số lượng task khi lượng truy cập tăng đột biến nhờ Auto Scaling.
* Tích hợp AWS WAF chặn đứng các IP xấu và bot độc hại tấn công hệ thống ứng dụng web.
