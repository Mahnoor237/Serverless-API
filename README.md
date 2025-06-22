# 🛠️ Serverless CRUD API

A fully serverless REST API built using AWS Lambda, API Gateway, and DynamoDB—managed via Terraform and deployed via GitHub Actions CI/CD.

---

## 🚀 Features
- CRUD operations for `items` (Create, Read, Update, Delete)
- Infrastructure-as-Code using **Terraform**
- **Serverless compute** via AWS Lambda + API Gateway
- **Automated CI/CD** pipeline: lint, test, deploy with GitHub Actions
- **IAM least-privilege** roles & environment-specific configurations
- **Monitoring** through CloudWatch (logs & metrics)

---

## 🧰 Tech Stack
| Layer           | Technology             |
|----------------|------------------------|
| Compute         | AWS Lambda (Node.js)   |
| API             | API Gateway (HTTP API) |
| Database        | DynamoDB               |
| Infrastructure  | Terraform              |
| CI/CD           | GitHub Actions         |
| Monitoring      | AWS CloudWatch         |

---

## 🏛️ Architecture
![Architecture Diagram](docs/architecture.png)

An overview of the components:
Lambda functions handle API logic, API Gateway routes requests, and DynamoDB stores data.

---

## ⚙️ Setup & Deployment

```bash
git clone https://github.com/your-username/Serverless-API.git
cd Serverless-API/infra
terraform init
terraform apply -auto-approve
