# 🚀 Ansible Playbook for Dockerized App Deployment

Easily deploy and update any **Dockerized application** with this reusable **Ansible playbook**.  
It automates stopping old containers, cleaning up Docker images, pulling the latest code, and redeploying your app with Docker Compose.  

---

## ✨ Features
- 🔧 Stops and removes old containers  
- 🧹 Cleans up unused Docker images  
- ⬇️ Pulls the latest code from GitHub  
- 🐳 Rebuilds and restarts services with Docker Compose  
- ♻️ Fully reusable — just update variables for your project  

---

## 📂 Included Files
This repository provides everything in one place:
├── deploy.yml # The main Ansible playbook
├── vars.yml # Project-specific variables
└── README.md # Documentation
