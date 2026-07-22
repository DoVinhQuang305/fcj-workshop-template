---
title: "Worklog Tuần 11"
date: 2026-07-20
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

# Worklog Tuần 11 (13/07/2026 – 19/07/2026)

#### 1. Mục tiêu công việc
- Khởi tạo AWS API Gateway HTTP API với proxy /{proxy+}
- Kết nối API Gateway với AWS Lambda Function integration

#### 2. Chi tiết công việc thực hiện trong tuần
Khởi tạo và cấu hình AWS API Gateway (HTTP API) đóng vai trò cổng giao tiếp công khai cho hệ thống với route proxy /{proxy+}. Cấu hình chính sách CORS mở rộng cho phép Frontend truy cập an toàn. Xử lý triệt để định dạng UTF-8 và cấu hình Binary Media Types để khắc phục lỗi font chữ tiếng Việt trên trình duyệt.

#### 3. Bảng phân công & Tiến độ chi tiết
| Thứ | Nội dung công việc thực hiện | Trạng thái | Nguồn tài liệu |
| :---: | :--- | :---: | :--- |
| **Thứ 2** | Khởi tạo AWS API Gateway HTTP API với proxy /{proxy+} | Complete | AWS Documentation |
| **Thứ 3** | Kết nối API Gateway với AWS Lambda Function integration | Complete | AWS Documentation |
| **Thứ 4** | Cấu hình CORS Policy cho phép truy cập từ mọi Origin | Complete | Project Source Code |
| **Thứ 5** | Xử lý UTF-8 encoding khắc phục lỗi font tiếng Việt | Complete | Project Source Code |
| **Thứ 6** | Kiểm thử, rà soát tính năng & tối ưu hóa | Complete | Self-testing / Postman |

#### 4. Kết quả đạt được
- **Hoàn thành**: Khởi tạo AWS API Gateway HTTP API với proxy /{proxy+}, Kết nối API Gateway với AWS Lambda Function integration, Cấu hình CORS Policy cho phép truy cập từ mọi Origin, Xử lý UTF-8 encoding khắc phục lỗi font tiếng Việt.
- **Kỹ năng tích lũy**: Nắm vững quy trình làm việc trên AWS Cloud, triển khai thành công các thành phần của hệ thống GearStore.
