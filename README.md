# 🚀 GitHub CLI Practice (Terminal Workflow)

## 📌 Overview
This project demonstrates my hands-on practice using the **GitHub CLI (`gh`)** to manage repositories, issues, pull requests, and workflows directly from the terminal.

---

## 🎯 Objectives

- Understand GitHub operations via CLI
- Practice real-world DevOps workflows
- Automate common GitHub tasks

---

## 🛠️ Tools Used

- GitHub CLI (`gh`)
- Git
- VS Code
- Terminal (PowerShell / Bash)

---

## ✅ Tasks Performed

### 🔹 Repository Management
- Created repository using CLI  
- Cloned repository  
- Viewed repository details  
- Deleted repository  

---

### 🔹 Issue Management
- Created issues from terminal  
- Listed issues  
- Viewed issue details  
- Closed issues  

---

### 🔹 Pull Request Workflow
- Created branch  
- Made code changes  
- Pushed changes  
- Created pull request  
- Reviewed PR  
- Merged PR  

---

### 🔹 GitHub Actions (Preview)
- Listed workflow runs  
- Viewed workflow run status  

---

## 🔧 Sample Commands

```bash
# Create repo
gh repo create my-repo --public

# Create issue
gh issue create --title "Bug" --body "Fix login"

# Create PR
gh pr create --title "Fix" --body "Bug fix"

# List workflows
gh run list
