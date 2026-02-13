# 🚀 CI/CD Pipeline for Static Website (GitHub Actions)

This project demonstrates how to automate the deployment of a static web application (HTML, CSS, JavaScript) using GitHub Actions.

The CI/CD pipeline automatically runs whenever code is pushed to the `main` branch.

---

## 📌 Task Objective

To set up a CI/CD pipeline that:

- Triggers on push to `main`
- Automatically runs workflow
- Builds and deploys a static web app
- Uses GitHub Actions for automation

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- GitHub
- GitHub Actions

---

## 📂 Project Structure

Jayant_Resume/
│
├── index.html
├── .github/
│ └── workflows/
│ └── html-ci.yml
├── README.md
└── LICENSE

---

## ⚙️ CI/CD Workflow

The workflow is defined inside:

.github/workflows/html-ci.yml

### 🔄 Trigger

```yaml
on:
  push:
    branches:
      - main
This means whenever new code is pushed to the main branch, the pipeline runs automatically.
________________________________________
🔁 CI/CD Process Flow
1️⃣ Developer pushes code to GitHub
2️⃣ GitHub Actions triggers automatically
3️⃣ Workflow executes defined steps
4️⃣ Website is built/deployed
________________________________________
🚀 What This Project Demonstrates
•	Continuous Integration using GitHub Actions
•	Workflow automation using YAML
•	Trigger-based deployment
•	Basic CI/CD implementation for static web apps
________________________________________
🎯 Learning Outcome
By completing this task, I learned:
•	How CI/CD pipelines work
•	How to write GitHub Actions workflow files
•	How automation is triggered on push events
•	How modern DevOps practices improve deployment process
