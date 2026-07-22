# Myntra Clone - End-to-End DevOps & CI/CD Pipeline

A production-grade E-Commerce application deployment featuring automated CI/CD pipelines, containerization with Docker, static code analysis, and Kubernetes orchestration.

---

## 🛠️ Tech Stack & Tools

* **Application:** Node.js / React
* **CI/CD Tool:** GitHub Actions
* **Containerization:** Docker & DockerHub
* **Code Quality & Security:** SonarQube & Trivy
* **Orchestration:** Kubernetes (EKS) / Helm

---

## 🚀 Key Pipeline Features

1. **Automated Testing:** Runs unit tests on every pull request to `main`.
2. **Security Scanning:** Scans application dependencies and Docker images using Trivy.
3. **Static Code Analysis:** Integrates SonarQube quality gates for code standards.
4. **Automated Docker Build & Push:** Builds container images tagged with commit SHA and pushes to DockerHub.
5. **Kubernetes Deployment:** Continuous Deployment to Kubernetes cluster using manifests.

---

## ⚙️ Setup & Local Execution

### Prerequisites
* Docker & Docker Compose
* Node.js (v18+)
* kubectl

### Running Locally
```bash
# Clone the repository
git clone [https://github.com/salmankhan369/myntra-devops-cicd.git](https://github.com/salmankhan369/myntra-devops-cicd.git)
cd myntra-devops-cicd

# Install dependencies and start local server
npm install
npm start