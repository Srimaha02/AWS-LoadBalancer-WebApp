# Highly Available Cloud Load Balancing Web Application on AWS

### 👩‍💻 Developed by: **Srimahalakshmi R**

---

## 📌 Project Overview

This project demonstrates how to deploy a highly available and fault-tolerant web application using **Amazon EC2** instances and an **Application Load Balancer** (ALB).  
The Load Balancer distributes incoming user traffic across multiple servers to ensure **maximum uptime**, **scalability**, and **performance**.

---

## 🧩 Architecture

Users → Application Load Balancer → EC2 Server-1 + EC2 Server-2
↘ Health Checks ↙


---

## ☁️ AWS Services Used

| Service | Purpose |
|--------|---------|
| EC2 | Hosts the web servers |
| Application Load Balancer | Distributes requests between servers |
| Target Group | Health monitoring & routing to active servers |
| Security Groups | Firewall protection and controlled access |
| VPC & Subnets | High Availability in multiple AZs |

---

## 🚀 What This App Does

- Runs **2 separate web servers** (Server-1 & Server-2)
- Displays different content from each server
- Refreshing Load Balancer DNS alternates responses:
  - _“Hello from Server-1”_
  - _“Hello from Server-2”_
- Confirms **Load Balancing + High Availability**

---

## 🛠 Technologies

- Amazon Linux (EC2)
- Apache HTTP Server
- HTML Webpages
- AWS Load Balancer
- Cloud Networking

---

## 📸 Output Screenshots
(Add your screenshots here)

- EC2 Instances running
- ALB Active state
- Target Group Healthy state
- Browser showing Server-1 page
- Browser showing Server-2 page

---

## 📍 Folder Structure

AWS-LoadBalancer-WebApp/
│
├── index-server1.html
├── index-server2.html
└── Screenshots/



---

## 🧠 Key Learnings

- Deploying scalable cloud applications
- Configuring Load Balancers & routing rules
- AWS network-level security
- Building fault-tolerant architecture

---

## 🔮 Future Enhancements

✔ Auto Scaling Group  
✔ HTTPS with SSL certificate  
✔ Real application UI (e.g., portfolio site)  
✔ Database integration (RDS / DynamoDB)

---

### ✨ Completed Successfully!  
Cloud Engineer in the making 🚀🔥  
