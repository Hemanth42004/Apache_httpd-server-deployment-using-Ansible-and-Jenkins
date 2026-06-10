# 🚀 Apache CI/CD Automation using Jenkins and Ansible

## 📌 Project Overview
This project demonstrates a simple CI/CD pipeline using Jenkins and Ansible to automatically install and configure Apache HTTP Server on a RHEL localhost system and deploy a static web page.

The project follows a **flat structure (no directories)** for simplicity and learning purposes.

---

## 🏗️ Architecture

GitHub Repository → Jenkins Pipeline → Ansible Playbook → Apache HTTP Server → Web Page Output

---

## 🛠️ Tools Used
- Jenkins (CI/CD Automation)
- Ansible (Configuration Management)
- Git & GitHub (Version Control)
- Apache HTTP Server
- Linux (RHEL)
- YAML (Playbook)

---

## 📁 Project Structure

apache-ci-cd/
├── index.html
├── inventory.ini
├── playbook.yml
└── Jenkinsfile

---

## ⚙️ How It Works

1. Code is pushed to GitHub repository
2. Jenkins pipeline is triggered
3. Jenkins pulls the latest code
4. Ansible playbook is executed
5. Apache HTTP Server is installed and started
6. index.html is copied to /var/www/html
7. Web page is accessible via browser

---

## 🌐 Output

Open in browser:

http://localhost:80

You will see:

Apache Deployed using Jenkins + Ansible 🚀

---

## 🎯 Key Features

- Fully automated CI/CD pipeline
- Infrastructure automation using Ansible
- Apache HTTP Server deployment
- Flat and simple project structure
- Localhost-based DevOps simulation

---

## 📌 Learning Outcomes

- Jenkins CI/CD pipeline setup
- Ansible automation basics
- Linux server management
- Apache web server deployment
- GitHub integration with Jenkins

---

## 👨‍💻 Author

Nadipani Hemanth Kumar 
DevOps Engineer | Automation Enthusiast | Linux & Cloud Learner

---

## 🚀 Future Enhancements

- Parameterized Jenkins pipeline
- Dynamic webpage using variables
- Docker containerization
- Multi-node Ansible deployment
- Kubernetes deployment version
