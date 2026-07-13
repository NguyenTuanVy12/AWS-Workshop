---
title: "Worklog Tuần 7"
date: 2026-05-04
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---


### Mục tiêu tuần 7:

* Đi sâu nghiên cứu và thực hành kiến trúc ứng dụng không máy chủ (Serverless) trên AWS.
* Triển khai các ứng dụng thực tế thông qua chuỗi bài thực hành Book Store Series, Document Management System (DMS) và Serverless Chat App.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Bắt đầu Book Store Series: Xây dựng serverless backend với Lambda, S3 và DynamoDB <br> - Sử dụng AWS SAM (Serverless Application Model) để tự động hóa định nghĩa hạ tầng | 15/06/2026 | 15/06/2026 | <https://cloudjourney.awsstudygroup.com/vi/4-modernize/> |
| 3 | - Tích hợp cơ chế bảo mật xác thực người dùng bằng Amazon Cognito <br> - Xây dựng GraphQL API bằng AWS AppSync và tự động hóa quy trình CI/CD cho ứng dụng | 16/06/2026 | 16/06/2026 | <https://cloudjourney.awsstudygroup.com/vi/4-modernize/> |
| 4 | - Khởi động DMS Series: Thiết lập backend CRUD với Lambda & DynamoDB <br> - Phát triển giao diện frontend và quản lý xác thực bằng AWS Amplify | 17/06/2026 | 17/06/2026 | <https://cloudjourney.awsstudygroup.com/vi/4-modernize/> |
| 5 | - Triển khai CDN CloudFront tối ưu hóa tốc độ tải file của DMS <br> - Thêm tính năng tìm kiếm tài liệu và cấu hình truy vết hệ thống bằng AWS X-Ray | 18/06/2026 | 18/06/2026 | <https://cloudjourney.awsstudygroup.com/vi/4-modernize/> |
| 6 | - Thực hành Serverless Web App Workshop: Xây dựng serverless APIs kết hợp DynamoDB <br> - Phát triển ứng dụng nhắn tin thời gian thực (Serverless Chat App) dùng WebSockets | 19/06/2026 | 19/06/2026 | <https://cloudjourney.awsstudygroup.com/vi/4-modernize/> |

### Kết quả đạt được tuần 7:

* Thiết lập thành thạo tài nguyên serverless (Lambda, API Gateway) kết nối cơ sở dữ liệu DynamoDB.
* Làm chủ framework AWS SAM để đóng gói, kiểm thử local và deploy ứng dụng serverless nhanh chóng.
* Tích hợp thành công API Gateway/AppSync GraphQL với Cognito làm lớp bảo vệ truy cập.
* Hiểu cách cấu hình AWS Amplify để đồng bộ hóa nhanh frontend React/Vue với backend AWS.
* Biết cách debug lỗi hệ thống phân tán phức tạp nhờ dịch vụ giám sát AWS X-Ray.
* Phát triển thành công một ứng dụng chat thời gian thực hai chiều chạy hoàn toàn trên serverless WebSocket.
