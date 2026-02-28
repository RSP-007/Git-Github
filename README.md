# 📘 Git, GitHub & Version Control

This document provides a beginner-friendly overview of **Version Control**, **Git**, and **GitHub**. It explains essential concepts and commands required to manage and track code effectively.

---

## 📌 What is Version Control?

Version Control is a system that helps developers:

- Track changes in files  
- Maintain history of modifications  
- Restore previous versions when needed  
- Collaborate with others  
- Prevent accidental data loss  

It keeps projects organized and structured.

---

## 🛠 What is Git?

Git is a **distributed version control system** used to track changes in source code during software development.

### 🔹 Key Features of Git

- Tracks every change in a project  
- Supports branching and merging  
- Enables collaboration  
- Maintains complete project history  
- Works both online and offline  

---

## 💻 Basic Git Commands

```bash
git init              # Initialize a repository
git status            # Check repository status
git add .             # Add all files to staging area
git commit -m "msg"   # Save changes with a message
git log               # View commit history
git branch            # List all branches
git checkout branch   # Switch to another branch
git merge branch      # Merge branches
```

---

## 🌐 What is GitHub?

GitHub is a cloud-based platform that hosts Git repositories online.

### 🔹 Why Use GitHub?

- Store repositories remotely  
- Collaborate with other developers  
- Backup your projects  
- Manage issues and pull requests  

GitHub works together with Git to manage and share code efficiently.

---

## 🔗 Connecting Git to GitHub

```bash
git remote add origin <repository-url>
git push -u origin main
git pull origin main
```

---

## 🌳 Branching Concept

Branching allows developers to work on features independently without affecting the main project.

Example:

```bash
git branch feature1
git checkout feature1
```

Branches can later be merged into the main branch safely.

---

## 📁 What is .gitignore?

`.gitignore` is a file that tells Git which files or folders should not be tracked.

Example:

```
node_modules/
.env
*.log
```

This prevents unnecessary or sensitive files from being pushed to GitHub.

---

## 🚀 Importance of Git & GitHub

- Maintains complete version history  
- Enables teamwork and collaboration  
- Prevents data loss  
- Industry-standard tools for developers  
- Essential for modern software development  

---

## 📚 Summary

- **Version Control** → Tracks and manages file changes  
- **Git** → Tool used for version control  
- **GitHub** → Platform to host and share Git repositories  

---

✨ Learning Git and GitHub is a fundamental skill for every developer.
