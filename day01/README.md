# 🚀 TerraWeek Challenge - Day 01

## Getting Started with Terraform & Infrastructure as Code (IaC)

Welcome to **Day 01** of my **#TerraWeekChallenge** journey! 🎉

This repository contains my first Terraform project, where I learned the fundamentals of **Infrastructure as Code (IaC)** and provisioned an **Amazon S3 bucket** on AWS directly from my Ubuntu terminal using Terraform.

---

## 📚 What I Learned

### 🔹 What is Infrastructure as Code (IaC)?

Infrastructure as Code (IaC) is the practice of managing and provisioning infrastructure through **code** instead of manual configuration.

### 🔹 Benefits of IaC

* Automation of infrastructure provisioning
* Consistent and repeatable deployments
* Version-controlled infrastructure
* Reduced human errors
* Faster environment creation and management

---

## 🔥 Why Terraform?

Terraform is one of the most popular IaC tools because it is:

* 🌍 Cloud-agnostic (AWS, Azure, GCP, Kubernetes, etc.)
* 📝 Declarative in nature
* ♻️ Supports reusable modules
* 🔄 Enables version-controlled infrastructure
* 🤝 Backed by a large community and provider ecosystem

---

## 🧠 Key Terraform Concepts Covered

* Providers
* Resources
* Configuration Files (`.tf`)
* State Files (`terraform.tfstate`)
* Terraform Workflow:

  ```bash
  terraform init
  terraform plan
  terraform apply
  terraform destroy
  ```

---

## 🛠️ Project Objective

Provision an **Amazon S3 Bucket** using Terraform.

---

## 📂 Project Structure

```text
.
├── main.tf
├── terraform.tfvars
└── README.md
```

---

## ⚙️ Prerequisites

* Ubuntu/Linux Machine
* AWS Account
* AWS CLI configured
* Terraform installed

Verify installations:

```bash
terraform -version
aws --version
```

---

## 🚀 Steps to Run

### 1. Clone the repository

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
```

### 2. Initialize Terraform

```bash
terraform init
```

### 3. Review the execution plan

```bash
terraform plan
```

### 4. Create the infrastructure

```bash
terraform apply
```

Type:

```text
yes
```

when prompted.

---

## ✅ Resources Created

* Amazon S3 Bucket

---

## 📸 Output

* Terraform `init`
<img width="1799" height="388" alt="image" src="https://github.com/user-attachments/assets/76e30c01-b2aa-432e-8069-bac9d3902784" />

* Terraform `plan`
<img width="1747" height="858" alt="image" src="https://github.com/user-attachments/assets/02824cc7-9c54-4875-859e-a5b3bb0d395a" />

* Terraform `apply`
<img width="1756" height="912" alt="image" src="https://github.com/user-attachments/assets/a9c7f846-c1e2-4b16-9144-2e9ea47278bb" />


* AWS Console showing the created S3 bucket

<img width="1054" height="255" alt="image" src="https://github.com/user-attachments/assets/020ed742-3a66-4317-b16e-af604c29897d" />

---

## 🎯 Key Takeaway

> "If infrastructure can be defined in code, it can be automated, versioned, and reproduced consistently."

---

## 🌱 What's Next?

In the upcoming days of the challenge, I will explore:

* Variables and Outputs
* State Management
* Modules
* Remote Backend
* Provisioners
* Real-world Infrastructure Deployment

---

## 🙏 Acknowledgements

A huge thanks to **TrainWithShubham** and Shubham Londhe for organizing the **#TerraWeekChallenge** and making Terraform easy to understand.

---

## 🔗 Connect With Me

* GitHub: https://github.com/Sakshi-Saxena
* LinkedIn: https://www.linkedin.com/in/sakshi-saxena11/

---

### ⭐ If you found this repository useful, consider giving it a star!

#Terraform #AWS #IaC #DevOps #CloudComputing #TrainWithShubham #TerraWeekChallenge
