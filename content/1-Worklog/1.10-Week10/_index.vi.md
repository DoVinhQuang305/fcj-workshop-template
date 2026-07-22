---
title: "Worklog Tuần 10"
date: 2026-07-20
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

# Worklog Tuần 10 (06/07/2026 – 12/07/2026)

#### 1. Mục tiêu công việc
- Tích hợp aws-serverless-java-container-springboot3
- Viết StreamLambdaHandler chuyển tiếp HttpApiV2 request

#### 2. Chi tiết công việc thực hiện trong tuần
Đóng gói ứng dụng Spring Boot theo chuẩn Serverless với thư viện aws-serverless-java-container-springboot3. Biên dịch file .jar và triển khai ứng dụng Backend lên dịch vụ AWS Lambda (gearstore). Cấu hình IAM Role cho Lambda để cấp quyền truy cập an toàn, tối giản tới DynamoDB và S3 Bucket.

#### 3. Bảng phân công & Tiến độ chi tiết
| Thứ | Nội dung công việc thực hiện | Trạng thái | Nguồn tài liệu |
| :---: | :--- | :---: | :--- |
| **Thứ 2** | Tích hợp aws-serverless-java-container-springboot3 | Complete | AWS Documentation |
| **Thứ 3** | Viết StreamLambdaHandler chuyển tiếp HttpApiV2 request | Complete | AWS Documentation |
| **Thứ 4** | Biên dịch Uber-JAR với maven-shade-plugin | Complete | Project Source Code |
| **Thứ 5** | Tạo AWS Lambda Function & gán IAM Execution Role | Complete | Project Source Code |
| **Thứ 6** | Kiểm thử, rà soát tính năng & tối ưu hóa | Complete | Self-testing / Postman |

#### 4. Kết quả đạt được
- **Hoàn thành**: Tích hợp aws-serverless-java-container-springboot3, Viết StreamLambdaHandler chuyển tiếp HttpApiV2 request, Biên dịch Uber-JAR với maven-shade-plugin, Tạo AWS Lambda Function & gán IAM Execution Role.
- **Kỹ năng tích lũy**: Nắm vững quy trình làm việc trên AWS Cloud, triển khai thành công các thành phần của hệ thống GearStore.
