---
title: "Week 8 Worklog"
date: 2026-07-20
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

# Week 8 Worklog (22/06/2026 – 28/06/2026)

#### 1. Weekly Objectives
- Provision S3 Bucket `gearstore-data-images` & configure CORS
- Develop POST /products/upload endpoint handling Multipart File

#### 2. Technical Activities Summary
Developed multipart product image upload functionality uploading directly to Amazon S3 bucket (`gearstore-data-images`). Implemented unique filename generation and saved public S3 object URLs into DynamoDB product records.

#### 3. Task Breakdown & Schedule
| Day | Task Activity | Status | Reference / Tool |
| :---: | :--- | :---: | :--- |
| **Mon** | Provision S3 Bucket `gearstore-data-images` & configure CORS | Complete | AWS Documentation |
| **Tue** | Develop POST /products/upload endpoint handling Multipart File | Complete | AWS Documentation |
| **Wed** | Generate unique timestamped filenames to prevent S3 overwrites | Complete | Project Source Code |
| **Thu** | Store public S3 image URLs directly into DynamoDB records | Complete | Project Source Code |
| **Fri** | Integration testing, optimization & review | Complete | Self-testing / Postman |

#### 4. Key Deliverables & Outcomes
- **Completed Deliverables**: Provision S3 Bucket `gearstore-data-images` & configure CORS, Develop POST /products/upload endpoint handling Multipart File, Generate unique timestamped filenames to prevent S3 overwrites, Store public S3 image URLs directly into DynamoDB records.
- **Skill Acquisition**: Gained practical hands-on experience with AWS Cloud services and successful implementation of GearStore system components.
