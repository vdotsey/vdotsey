<h1 align="center">Hi 👋, I'm Vivienne Dotsey</h1>
<h3 align="center">🚀 DevOps Engineer | Cloud & Infrastructure | CI/CD | Monitoring</h3>

---

🌱 I’m passionate about building and automating cloud-native systems using tools like:

- ☁️ **AWS (EKS, VPC, Lambda,EC2, S3, ECS, Cloudwatch)**  
- 🔧 **Terraform, Ansible, Jenkins, GitHub Actions**  
- 📦 **Docker, Kubernetes**  
- 📊 **Prometheus, Grafana, Loki**  
- 🧪 **SonarQube, Trivy**  
- 📜 **Scripting:** Bash, Python, YAML

---

📂 Featured Projects

# 🚀 Terraform AWS ECS Fargate Deployment

This project provisions a **highly available ECS Fargate cluster** on AWS using Terraform. It automates the entire infrastructure setup, including networking, compute, security, and load balancing, to deploy a containerized application.

---

## 🧱 Architecture

**Core Components:**
- 🌐 **VPC** with public/private subnets across multiple Availability Zones
- 🖧 **Application Load Balancer (ALB)** for routing traffic
- 🚀 **ECS Cluster (Fargate)** running a Dockerized web app
- 📦 **Amazon ECR** for container image storage
- 🔐 **IAM** roles and policies for secure resource access
- 🔒 **Security Groups** for ALB and ECS
- 📈 **CloudWatch Logs** for centralized monitoring
- 🧪 **Auto Scaling** based on CPU/Memory usage
- 📛 **Route 53** for custom domain management
- 📂 **S3** for static assets or artifact storage
- 🔁 **CI/CD Integration** (via GitHub Actions)

---

## 🛠️ Tools Used

- **Terraform** (Infrastructure as Code)
- **AWS ECS (Fargate)** – container orchestration
- **AWS VPC, ALB, ECR, Route 53, IAM, CloudWatch, S3**
- **CI/CD** – GitHub Actions
- **Docker** – containerized web app
- **Auto Scaling** & Logging
---

## 📂 Project Structure

```bash
Terra-Infra-Ecs-project/
├── modules/
│   ├── vpc/
│   ├── ecs/
│   ├── alb/
│   ├── iam/
│   ├── ecr/
│   └── route53/
├── main.tf
├── variables.tf
├── outputs.tf
├── terraform.tfvars
└── README.md

---

📫 **How to reach me**  
📧 vivienneyahaya86@gmail.com  
🌐 [LinkedIn](https://www.linkedin.com/in/viviennedotsey1)

---
