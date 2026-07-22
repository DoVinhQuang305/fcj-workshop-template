---
title: "Video Demo Dự Án"
date: 2026-07-20
weight: 8
chapter: false
pre: " <b> 8. </b> "
---

# Video Demo Giới Thiệu Dự Án GearStore E-Commerce Platform

Dưới đây là video demo trực quan toàn bộ hệ thống thương mại điện tử **GearStore E-Commerce Platform** được triển khai theo kiến trúc **Cloud-Native Serverless** trên nền tảng **AWS Cloud** (sử dụng Spring Boot 3, Java 21, AWS Lambda, API Gateway, Amazon DynamoDB, Amazon S3, Next.js & AWS Amplify).

---

### Video Trình Chiếu Demo Dự Án

<video width="100%" height="auto" controls preload="metadata" style="border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.15); margin-top: 15px; margin-bottom: 20px;">
  <source src="/videos/video-demo.mp4" type="video/mp4">
  Trình duyệt của bạn không hỗ trợ thẻ phát video HTML5. Bạn có thể tải video về trực tiếp để xem: <a href="/videos/video-demo.mp4">Tải Video Demo (.mp4)</a>.
</video>

---

### Tóm Tắt Các Nội Dung Kỹ Thuật Trong Video Demo

1. **Tổng quan Giao diện Frontend (Next.js / AWS Amplify)**:
   - Trải nghiệm mua sắm thiết bị gaming gear với giao diện Modern Dark Mode responsive.
   - Tìm kiếm, lọc danh mục sản phẩm và hiển thị thông số kỹ thuật chi tiết.
2. **Xác thực Người dùng & Phân quyền (Auth Service)**:
   - Đăng nhập, đăng ký tài khoản qua JWT Auth / Google OAuth2.
   - Phân quyền Admin quản trị danh mục sản phẩm và người dùng.
3. **Quản lý Sản phẩm & Upload Ảnh (AWS S3 & DynamoDB)**:
   - Thêm mới, chỉnh sửa sản phẩm và upload hình ảnh trực tiếp lên **Amazon S3** (`gearstore-data-images`).
   - Tự động lưu vết S3 Image URL vào cơ sở dữ liệu **Amazon DynamoDB** (`GearStore_Products`).
4. **Vận hành Serverless Backend (AWS Lambda & API Gateway)**:
   - Phân tích luồng xử lý HTTP request qua **API Gateway HTTP API** và **AWS Lambda Java 21 Container**.
