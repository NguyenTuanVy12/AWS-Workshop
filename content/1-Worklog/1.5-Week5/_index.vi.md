---
title: "Worklog Tuần 5"
date: 2026-05-04
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---


### Mục tiêu tuần 5:

* Nâng cao độ tin cậy của hệ thống (Reliability) và tối ưu hóa chi phí vận hành trên đám mây (Cost Optimization).
* Làm quen với công nghệ Container trên AWS thông qua Docker và dịch vụ Amazon ECS.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Thiết lập hệ thống sao lưu dữ liệu tập trung với AWS Backup <br> - Kết nối mạng cục bộ giữa các mạng ảo bằng VPC Peering | 01/06/2026 | 01/06/2026 | <https://cloudjourney.awsstudygroup.com/vi/3-optimize/> |
| 3 | - Quản lý mạng kết nối tập trung nhiều tài khoản bằng AWS Transit Gateway <br> - Thiết kế hệ thống truyền tin nhắn bất đồng bộ với Amazon SQS và Amazon SNS | 02/06/2026 | 02/06/2026 | <https://cloudjourney.awsstudygroup.com/vi/3-optimize/> |
| 4 | - Nghiên cứu giải pháp HA nâng cao: Windows Server Failover Clustering và SQL Server High Availability <br> - Tìm hiểu cách chia sẻ ổ đĩa bằng Amazon EBS Multi-Attach | 03/06/2026 | 03/06/2026 | <https://cloudjourney.awsstudygroup.com/vi/3-optimize/> |
| 5 | - Tối ưu hóa chi phí với các gói Savings Plans và Reserved Instances <br> - Phân tích sâu hóa đơn chi phí (Cost and Usage Report) bằng AWS Glue và Amazon Athena | 04/06/2026 | 04/06/2026 | <https://cloudjourney.awsstudygroup.com/vi/3-optimize/> |
| 6 | - Tìm hiểu và thực hành đóng gói ứng dụng với Docker <br> - Triển khai container lên đám mây sử dụng Amazon Lightsail Containers và Amazon ECS (ECS với CDK & CI/CD) | 05/06/2026 | 05/06/2026 | <https://cloudjourney.awsstudygroup.com/vi/5-container/> |

### Kết quả đạt được tuần 5:

* Cấu hình thành công lịch trình sao lưu tự động cho các tài nguyên EBS, RDS, S3 bằng AWS Backup.
* Thiết lập kết nối an toàn giữa các phân vùng mạng qua VPC Peering và Transit Gateway.
* Xây dựng thành công hệ thống trao đổi thông điệp bất đồng bộ (decoupling) với SQS và SNS.
* Nắm vững cách quản trị chi phí, dự báo và truy vấn hóa đơn sử dụng dịch vụ thông qua Athena và Glue.
* Đóng gói thành công ứng dụng vào Docker container và triển khai chạy ổn định trên Amazon ECS Fargate.
