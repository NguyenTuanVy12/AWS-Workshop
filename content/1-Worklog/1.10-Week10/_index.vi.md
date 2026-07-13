---
title: "Worklog Tuần 10"
date: 2026-05-04
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---


### Mục tiêu tuần 10:

* Phát triển các tính năng cốt lõi của ứng dụng (Backend & Frontend).
* Triển khai cơ sở dữ liệu thực tế và thiết lập dịch vụ chạy container/serverless trên AWS (Giai đoạn 2).

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Phát triển các API nghiệp vụ chính (RESTful API hoặc GraphQL) ở phía Backend <br> - Xây dựng các hàm xử lý dữ liệu và kết nối database | 06/07/2026 | 06/07/2026 | |
| 3 | - Xây dựng giao diện Frontend (React/Vue/Next.js) và tích hợp gọi API từ Backend <br> - Thiết kế giao diện responsive thân thiện với người dùng | 07/07/2026 | 07/07/2026 | |
| 4 | - Khởi tạo và thiết lập database trên AWS (Amazon RDS MySQL/PostgreSQL hoặc DynamoDB Tables) <br> - Cấu hình bảo mật Security Groups cho phép Backend truy cập an toàn | 08/07/2026 | 08/07/2026 | |
| 5 | - Thực hành viết Dockerfile đóng gói mã nguồn ứng dụng Backend và Frontend <br> - Build Docker images và đẩy lên kho lưu trữ riêng tư Amazon ECR | 09/07/2026 | 09/07/2026 | |
| 6 | - Cấu hình Task Definitions và triển khai container chạy trên Amazon ECS Fargate <br> - Sử dụng AWS Secrets Manager để lưu trữ và nạp tự động credentials của Database | 10/07/2026 | 10/07/2026 | |

### Kết quả đạt được tuần 10:

* Hoàn thành 80% mã nguồn ứng dụng (gồm cả frontend và backend API).
* Khởi tạo cơ sở dữ liệu RDS/DynamoDB thành công trên đám mây và kết nối thông suốt từ ứng dụng.
* Đóng gói mã nguồn thành Docker images tối ưu và đẩy thành công lên Amazon ECR.
* Triển khai chạy ứng dụng thành công trên Amazon ECS Fargate, kiểm tra giao diện hiển thị đúng qua Public IP của ALB.
* Đảm bảo an toàn thông tin bằng cách loại bỏ hardcode password, chuyển sang gọi động qua Secrets Manager.
