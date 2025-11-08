# Solana-Docker-Devcontainer-Setup
Easy copy paste Dockersetup + devcontainer vor VSCode to develop, test and deploy in a secure environment

# 🪄 Solana DevContainer Setup

This repository provides a ready-to-use **DevContainer configuration** for Solana development in **VS Code** (or GitHub Codespaces).  
It automatically sets up a Docker-based environment with all required Solana tools.

---

## 🚀 Requirements

1. **Visual Studio Code**  
   → [https://code.visualstudio.com/](https://code.visualstudio.com/)

2. **Dev Containers Extension**  
   → [ms-vscode-remote.remote-containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

3. **Docker Desktop** running on your system  
   → [https://www.docker.com/products/docker-desktop/](https://www.docker.com/products/docker-desktop/)

---

## 🧱 Folder Structure

.devcontainer/
├── devcontainer.json
└── Dockerfile


---

## ▶️ How to Use

1. **Clone this repository:**
   ```bash
   git clone https://github.com/<USERNAME>/Solana-Docker-Devcontainer-Setup.git
   cd Solana-Docker-Devcontainer-Setup
2. Open the folder in VS Code
   (File → Open Folder… or code . in your terminal)

3. When prompted by VS Code:
    "Folder contains a Dev Container configuration. Reopen in Container?"
    → ✅ Click “Reopen in Container”

4. Wait until the container finishes building (only needed the first time).
   Once done, your Solana development environment will be ready with:

solana-cli

rustup + cargo

node & npm

anchor-cli

🧩 Example Commands Inside the Container

Once inside the container, you can run:
solana --version
anchor --version
solana-test-validator
