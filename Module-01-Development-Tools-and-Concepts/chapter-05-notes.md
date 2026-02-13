# Week 1 - Session 5 Notes

## 1. Agenda & Introduction
- Focus: Git and GitHub setup for Data Science workflows
- Importance of version control in collaborative projects

## 2. Installing Git
- Installation via package managers (Linux/macOS/Windows)
- Verifying installation: `git --version`

## 3. Git Configuration
- Setting username and email:
  - `git config --global user.name "Your Name"`
  - `git config --global user.email "your@email.com"`
- Checking configuration: `git config --list`

## 4. SSH Key Generation
- Purpose: Secure authentication with GitHub
- Steps:
  - Generate key: `ssh-keygen -t rsa -b 4096 -C "your@email.com"`
  - Add to ssh-agent: `eval "$(ssh-agent -s)"` then `ssh-add ~/.ssh/id_rsa`
  - Copy public key and add to GitHub account

## 5. GitHub Setup
- Creating a new repository on GitHub
- Cloning repository: `git clone <repo_url>`
- Linking local repo to remote: `git remote add origin <repo_url>`

## 6. Basic Git Workflow
- Initialize repo: `git init`
- Stage changes: `git add <file>`
- Commit changes: `git commit -m "message"`
- Push to GitHub: `git push origin main`

## 7. Practical Demonstration
- Walkthrough of creating a repo, committing files, and pushing to GitHub
- Testing SSH connection with `ssh -T git@github.com`

## 8. Applications in Data Science
- Tracking code changes in projects
- Collaborating with peers using GitHub
- Ensuring reproducibility and transparency in workflows
