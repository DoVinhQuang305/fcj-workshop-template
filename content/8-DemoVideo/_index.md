---
title: "Project Demo Video"
date: 2026-07-20
weight: 8
chapter: false
pre: " <b> 8. </b> "
---

# GearStore E-Commerce Platform Project Demo Video

Below is the demonstration video showcasing the **GearStore E-Commerce Platform**, built on a **Cloud-Native Serverless Architecture** on **AWS Cloud** (featuring Spring Boot 3, Java 21, AWS Lambda, API Gateway, Amazon DynamoDB, Amazon S3, Next.js, and AWS Amplify).

---

### Interactive Demo Video

<video width="100%" height="auto" controls preload="metadata" style="border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.15); margin-top: 15px; margin-bottom: 20px;">
   <source src="{{ "videos/video-demo.mp4" | relURL }}" type="video/mp4">
   Your browser does not support the HTML5 video tag. You can download the video file directly: <a href="{{ "videos/video-demo.mp4" | relURL }}">Download Demo Video (.mp4)</a>.
</video>

---

### Technical Highlights Demonstrated in the Video

1. **Frontend Interface (Next.js / AWS Amplify)**:
   - Responsive gaming gear shopping experience with Modern Dark Mode UI.
   - Product filtering, category browsing, and technical specification views.
2. **Authentication & Authorization (Auth Service)**:
   - User authentication via JWT Auth and Google OAuth2 integration.
   - Role-based access control separating customer features from Admin dashboards.
3. **Product Management & Media Storage (AWS S3 & DynamoDB)**:
   - Product creation, updates, and direct image uploads to **Amazon S3** (`gearstore-data-images`).
   - S3 public object URL persistence in **Amazon DynamoDB** (`GearStore_Products`).
4. **Serverless Backend Execution (AWS Lambda & API Gateway)**:
   - Request routing pipeline from **Amazon API Gateway** into the **AWS Lambda Java 21 Container**.
