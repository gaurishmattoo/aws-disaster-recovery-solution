# AWS Disaster Recovery Solution Project

## 📌 Project Overview
This project demonstrates a cloud-based Disaster Recovery (DR) solution using AWS services to ensure high availability, failover support, and reliable backup infrastructure.

---

# 🚀 AWS Services Used

- Amazon S3
- Amazon EC2
- Amazon Route 53
- Route 53 Health Checks
- DuckDNS
- NGINX Web Server

---

# 🏗️ Architecture

Primary Region:
- Mumbai (ap-south-1)

Secondary Region:
- Singapore (ap-southeast-1)

---

# 🔧 Project Implementation Steps

## 1. Created Primary S3 Bucket
![Primary Bucket](screenshots/1_primary_bucket_creation.png)

---

## 2. Primary Bucket Successfully Created
![Primary Bucket Created](screenshots/2_primary_bucket_created.png)

---

## 3. Secondary Bucket Successfully Created
![Secondary Bucket](screenshots/3_secondary_bucket_created.png)

---

## 4. S3 Buckets Dashboard
![S3 Dashboard](screenshots/4_s3_buckets_dashboard.png)

---

## 5. Test File Uploaded
![File Upload](screenshots/5_test_file_uploaded.png)

---

## 6. Route 53 Hosted Zone Created
![Hosted Zone](screenshots/6_route53_hosted_zone_created.png)

---

## 7. Route 53 Health Check
![Health Check](screenshots/7_route53_health_check.png)

---

## 8. Primary Failover Record
![Failover Record](screenshots/8_route53_primary_failover_record.png)

---

## 9. Route 53 Failover Records Created
![Failover Records](screenshots/9_route53_failover_records_created.png)

---

## 10. EC2 Instance Launch
![EC2 Launch](screenshots/10_ec2_instance_launch_success.png)

---

## 11. EC2 Connection
![EC2 Connect](screenshots/11_ec2_connect_public_ip.png)

---

## 12. NGINX Default Page
![NGINX](screenshots/12_nginx_default_page.png)

---

## 13. Final Live Website
![Final Website](screenshots/13_final_live_website.png)

---

# ✅ Final Output

The Disaster Recovery setup successfully hosted and served a live website using EC2, Route 53, and failover routing configuration.

---

# 🎯 Outcome

- High Availability Achieved
- DNS Failover Configured
- Multi-Region Backup Setup
- Website Successfully Hosted
- Disaster Recovery Successfully Implemented
