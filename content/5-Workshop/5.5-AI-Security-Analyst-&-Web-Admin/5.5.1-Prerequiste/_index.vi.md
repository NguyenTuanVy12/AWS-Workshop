---
title : "Các bước chuẩn bị"
date : 2024-01-01 
weight : 1
chapter : false
pre : " <b> 5.5.1. </b> "
---

### Chuẩn bị hạ tầng mạng

#### Khởi tạo VPC

![alt text](/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.1-Prerequiste/image.png)

#### Khởi tạo public subnet và private subnet

![alt text](/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.1-Prerequiste/image-1.png)

#### Khởi tạo internet gateways

![alt text](/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.1-Prerequiste/image-2.png)

#### Khởi tạo NAT gateway

![alt text](/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.1-Prerequiste/image-3.png)

#### Khởi tạo Route Table

![alt text](/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.1-Prerequiste/image-4.png)

### Chuẩn bị máy chủ EC2

#### Khởi tạo hai EC2 Instance:

Bastion Host (Public Subnet)

![alt text](/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.1-Prerequiste/image-5.png)

AI Server (Private Subnet)

![alt text](/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.1-Prerequiste/image-6.png)

### Chuẩn bị Security Group

Cấu hình Security Group cho các EC2.

Bastion Host (Public Subnet)

![alt text](/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.1-Prerequiste/image-8.png)

AI Server (Private Subnet)

![alt text](/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.1-Prerequiste/image-7.png)

### Chuẩn bị IAM Role

Tạo IAM Role

![alt text](/images/5-Workshop/5.5-AI-Security-Analyst-&-Web-Admin/5.5.1-Prerequiste/image-9.png)


