---
title: "Worklog Tuần 8"
date: 2026-07-20
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

# Worklog Tuần 8 (22/06/2026 – 28/06/2026)

#### 1. Mục tiêu công việc
- Khởi tạo S3 Bucket gearstore-data-images & cấu hình CORS
- Phát triển API POST /products/upload tiếp nhận MultipartFile

#### 2. Chi tiết công việc thực hiện trong tuần
Phát triển tính năng upload hình ảnh sản phẩm trực tiếp từ giao diện lên dịch vụ AWS S3 Bucket (gearstore-data-images). Thiết lập cơ chế tự động mã hóa tên file hình ảnh để tránh trùng lặp dữ liệu trên Cloud. Chuyển đổi liên kết URL hình ảnh từ S3 và lưu vết vào bản ghi dữ liệu sản phẩm tương ứng trên DynamoDB.

#### 3. Bảng phân công & Tiến độ chi tiết
| Thứ | Nội dung công việc thực hiện | Trạng thái | Nguồn tài liệu |
| :---: | :--- | :---: | :--- |
| **Thứ 2** | Khởi tạo S3 Bucket gearstore-data-images & cấu hình CORS | Complete | AWS Documentation |
| **Thứ 3** | Phát triển API POST /products/upload tiếp nhận MultipartFile | Complete | AWS Documentation |
| **Thứ 4** | Tự động sinh tên file unique tránh đè file trên S3 | Complete | Project Source Code |
| **Thứ 5** | Lưu vết đường dẫn S3 URL vào DynamoDB Product record | Complete | Project Source Code |
| **Thứ 6** | Kiểm thử, rà soát tính năng & tối ưu hóa | Complete | Self-testing / Postman |

#### 4. Kết quả đạt được
- **Hoàn thành**: Khởi tạo S3 Bucket gearstore-data-images & cấu hình CORS, Phát triển API POST /products/upload tiếp nhận MultipartFile, Tự động sinh tên file unique tránh đè file trên S3, Lưu vết đường dẫn S3 URL vào DynamoDB Product record.
- **Kỹ năng tích lũy**: Nắm vững quy trình làm việc trên AWS Cloud, triển khai thành công các thành phần của hệ thống GearStore.
