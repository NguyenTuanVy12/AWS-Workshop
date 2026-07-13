---
title: "Worklog Tuần 6"
date: 2026-05-04
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---


### Mục tiêu tuần 6:

* Học cách vận hành và tự động hóa hệ thống điều phối container Kubernetes sử dụng Amazon EKS.
* Nghiên cứu quy trình hiện đại hóa ứng dụng, chuyển đổi từ kiến trúc nguyên khối (Monolith) sang vi dịch vụ (Microservices) (Modernize - DevAx).

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Tìm hiểu và triển khai cluster Kubernetes với Amazon EKS <br> - Sử dụng EKS Blueprints cho CDK để khởi tạo tài nguyên hạ tầng | 08/06/2026 | 08/06/2026 | <https://cloudjourney.awsstudygroup.com/vi/5-container/> |
| 3 | - Thiết lập quy trình CI/CD tự động deploy code lên Amazon EKS <br> - Nghiên cứu dịch vụ Kubernetes doanh nghiệp: Red Hat OpenShift Service on AWS (ROSA) | 09/06/2026 | 09/06/2026 | <https://cloudjourney.awsstudygroup.com/vi/5-container/> |
| 4 | - Triển khai nhanh ứng dụng web với AWS Elastic Beanstalk (Node.js) <br> - Thiết lập pipeline deploy tự động với CDK Pipelines cho Beanstalk <br> - Triển khai mô hình WordPress trên EC2 | 10/06/2026 | 10/06/2026 | <https://cloudjourney.awsstudygroup.com/vi/4-modernize/> |
| 5 | - Bắt đầu chuỗi bài học DevAx: Phân tách hệ thống Monolith sang Microservices <br> - Xây dựng các API microservices độc lập và tích hợp CI/CD tự động | 11/06/2026 | 11/06/2026 | <https://cloudjourney.awsstudygroup.com/vi/4-modernize/> |
| 6 | - Xây dựng kiến trúc hướng sự kiện (Event-Driven Architecture) với DevAx <br> - Tích hợp cơ chế xác thực Cognito cho SPA và tích hợp các dịch vụ trí tuệ nhân tạo (AWS AI Services) | 12/06/2026 | 12/06/2026 | <https://cloudjourney.awsstudygroup.com/vi/4-modernize/> |

### Kết quả đạt được tuần 6:

* Tạo và vận hành thành công cluster EKS, hiểu cách deploy các pods, services và ingress controller.
* Tự động hóa quá trình đóng gói và deploy code ứng dụng lên EKS thông qua pipeline CI/CD.
* Triển khai nhanh ứng dụng Node.js lên Elastic Beanstalk và cấu hình auto-scaling tự động.
* Nắm vững tư duy phân tách database và logic nghiệp vụ từ Monolith sang Microservices.
* Xây dựng kiến trúc Event-Driven sử dụng EventBridge, Lambda và tích hợp các dịch vụ AI như Amazon Rekognition.
