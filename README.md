# 🚀 DevOps Task 3 – Infrastructure as Code (IaC) with Terraform

## 📌 Task Objective
The goal of this task was to implement Infrastructure as Code (IaC) using Terraform to provision a Docker container running the NGINX web server locally.

---

## ✅ What I Did

- Installed and configured **Terraform** and **Docker** on my local machine.
- Created a project directory containing a `main.tf` file.
- Used the **Docker provider** in Terraform to:
  - Pull the official `nginx:latest` image from Docker Hub.
  - Provision a container running the NGINX web server.
  - Expose the container on port `8080` to access it via `http://localhost:8080`.
- Ran key Terraform lifecycle commands:
  - `terraform init` to initialize the project.
  - `terraform plan` to preview resource changes.
  - `terraform apply` to create the container.
  - `terraform state list` to inspect managed resources.
  - `terraform destroy` to remove the container.

---

## 🛠 Tools Used

- Terraform
- Docker
- Git & GitHub
- PowerShell / Git Bash (for CLI commands)

---

## 📂 Files Submitted

- `main.tf` – Terraform configuration file
- `README.md` – This summary document
- `.gitignore` – To exclude Terraform state files
- `screenshots/` – CLI and browser screenshots (optional)

---

## 🌐 Outcome

Successfully provisioned and destroyed a Docker container using Terraform. Understood how Terraform providers work, how resources are declared, and how Terraform manages infrastructure as code.

---

## 📤 Submission

The entire task was submitted as a GitHub repository link as required by the internship assignment.
