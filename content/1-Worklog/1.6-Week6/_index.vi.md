---
title: "Worklog Tuần 6"
date: 2026-07-20
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

# Worklog Tuần 6 (08/06/2026 – 14/06/2026)

#### 1. Mục tiêu công việc
- Tích hợp AWS SDK v2 (dynamodb-enhanced) vào pom.xml
- Viết ProductEntity & ProductRepository với StaticTableSchema

#### 2. Chi tiết công việc thực hiện trong tuần
Cấu hình tích hợp thư viện AWS SDK for Java (v2) vào dự án Spring Boot để kết nối với cơ sở dữ liệu DynamoDB. Lập trình các REST API cốt lõi phục vụ nghiệp vụ hệ thống: Truy vấn danh sách sản phẩm, lấy chi tiết thông số kỹ thuật (Laptop, Phụ kiện) và số lượng tồn kho. Viết các hàm ánh xạ dữ liệu (Data Mapper) để chuyển đổi giữa đối tượng Java và các bản ghi NoSQL trên DynamoDB.

#### 3. Bảng phân công & Tiến độ chi tiết
| Thứ | Nội dung công việc thực hiện | Trạng thái | Nguồn tài liệu |
| :---: | :--- | :---: | :--- |
| **Thứ 2** | Tích hợp AWS SDK v2 (dynamodb-enhanced) vào pom.xml | Complete | AWS Documentation |
| **Thứ 3** | Viết ProductEntity & ProductRepository với StaticTableSchema | Complete | AWS Documentation |
| **Thứ 4** | Phát triển REST APIs GET /products và GET /products/{id} | Complete | Project Source Code |
| **Thứ 5** | Xây dựng Data Mapper chuyển đổi giữa Java Object & DynamoDB Item | Complete | Project Source Code |
| **Thứ 6** | Kiểm thử, rà soát tính năng & tối ưu hóa | Complete | Self-testing / Postman |

#### 4. Kết quả đạt được
- **Hoàn thành**: Tích hợp AWS SDK v2 (dynamodb-enhanced) vào pom.xml, Viết ProductEntity & ProductRepository với StaticTableSchema, Phát triển REST APIs GET /products và GET /products/{id}, Xây dựng Data Mapper chuyển đổi giữa Java Object & DynamoDB Item.
- **Kỹ năng tích lũy**: Nắm vững quy trình làm việc trên AWS Cloud, triển khai thành công các thành phần của hệ thống GearStore.
