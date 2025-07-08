# CI/CD Pipeline Templates

This repository contains reusable CI/CD pipeline templates for GitHub Actions. These templates are designed to help teams quickly adopt consistent and reliable workflows across projects in the organization.

## 📁 Templates

### 1. **Node.js Project Workflow**

- Installs dependencies
- Runs tests and linting
- Builds and optionally deploys

Path: `.github/workflows/nodejs.yml`

### 2. **Python Project Workflow**

- Set up Python environment
- Install dependencies
- Run unit tests and code checks

Path: `.github/workflows/python.yml`

### 3. **Docker Build & Push Workflow**

- Builds Docker images
- Pushes to GitHub Container Registry or Docker Hub

Path: `.github/workflows/docker.yml`

## 🚀 How to Use

1. Copy the desired YAML workflow file into your project under `.github/workflows/`.
2. Customize the workflow as needed for your project.
3. Commit and push to trigger the workflow.

## 📌 Best Practices

- Keep secrets (like API keys) in GitHub repo settings under **Secrets and variables**.
- Use environment-based deployment strategies (e.g., `staging`, `production`).
- Regularly update actions and runners to keep security up to date.

## 🤝 Contribution

If you'd like to add a template for another language or tool, feel free to submit a pull request.

---

Maintained and Developed by: ShanksTropezz 🧑‍💻🧑‍💻
