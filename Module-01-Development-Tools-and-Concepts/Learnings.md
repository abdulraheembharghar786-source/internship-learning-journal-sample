# Module 01 – Development Tools and Concepts 🚀

This module focuses on setting up a **complete development environment** using Linux (WSL), Git, GitHub, and Python. It builds the foundation required for Software Development, DevOps, and Data Science.

---

# 📌 Module Objectives

- Install and configure Linux using WSL
- Understand Linux terminal and filesystem
- Install and use development tools (Git, Python)
- Learn version control using Git
- Connect and push code to GitHub
- Prepare a real-world development environment

---

# 🧠 Detailed Key Learnings

## 1. Linux & WSL Fundamentals

- WSL (Windows Subsystem for Linux) allows running a real Linux environment inside Windows without a virtual machine.
- It provides near-native Linux performance while being lightweight.
- Linux is the industry standard for:
  - DevOps
  - Cloud Computing
  - Data Science
  - AI/ML
  - Backend Development
- Learned Linux filesystem hierarchy:
  - `/home` → user files
  - `/etc` → system configuration
  - `/bin` → system binaries
  - `/usr` → user programs
- Understood how Linux works through the command line instead of GUI.

---

## 2. Linux Command Line Skills

Learned essential Linux commands:

### Navigation
- `ls` → list files and directories
- `cd` → change directory
- `pwd` → show current directory

### File Handling
- `mkdir` → create folder
- `touch` → create file
- `cat` → read file

### Search & Utilities
- `grep` → search text inside files
- `whoami` → current user
- `sudo` → run as administrator

Key Understanding:
- Terminal is faster and more powerful than GUI
- Most real-world development uses CLI tools

---

## 3. Package Management & Environment Setup

- Used `apt` package manager to install tools
- Installed development tools like:
  - Git
  - Python
  - Pip
- Learned how Linux manages software using repositories
- Understood importance of updating system:

```bash
sudo apt update && sudo apt upgrade
