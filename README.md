## 🔗 Hybrid Cloud Integration using AWS VPC Peering

This project demonstrates secure communication between two Amazon VPCs using VPC Peering without using the public internet.

---

## 🧩 Architecture Overview
- Two VPCs connected using VPC Peering
- Private communication over AWS backbone
- No internet exposure for inter-VPC traffic

---

## 🛠 AWS Services Used
- Amazon VPC
- VPC Peering Connection
- Route Tables
- Subnets (Public & Private)
- Internet Gateway
- Amazon EC2

---

## 📍 Scenarios Implemented
✔ Same AWS account – different regions  
✔ Different AWS accounts – same region  
✔ Direct VPC-to-VPC connectivity  

---

## 🔐 Security Design
- No public internet routing between VPCs
- Controlled routing via route tables
- Security Groups allow only required traffic
- Network isolation maintained

---

## 🚀 Implementation Steps
1. Created two VPCs with non-overlapping CIDR blocks
2. Created public and private subnets
3. Launched EC2 instances in each VPC
4. Created VPC Peering connection
5. Updated route tables in both VPCs
6. Verified connectivity using private IPs

---

## ✅ Outcome
- Successful private communication between EC2 instances
- No internet dependency for VPC traffic
- Low-latency and secure connectivity

---

## 📌 Use Cases
- Hybrid cloud architectures
- Microservices communication
- Multi-account AWS networking
- Secure internal traffic routing
