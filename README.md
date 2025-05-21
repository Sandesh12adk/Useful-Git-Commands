# Git Commands & Team Workflow Guide

This document provides a quick reference for essential Git commands and a step-by-step team collaboration workflow using Git and GitHub.

---

## 🔧 Basic Git Commands

```bash
git init
# Initialize a Git repository in the current directory

git status
# Show the working directory status (modified, untracked, staged files)

git add file_name
# Stage a specific modified file

git add .
# Stage all modified and new files at once

git commit -m "Your commit message"
# Commit staged files with a descriptive message

git diff
# Show unstaged changes in the working directory

git diff --staged
# Show staged changes compared to the last commit

git rm --cached file_name
# Unstage a specific file (keeps it in the working directory)

git rm --cached .
# Unstage all staged files

##🌿 Branching & Merging

git checkout file_name
# Revert file to last committed or staged version

git checkout .
# Revert all files to last committed or staged version

git branch
# List all local branches

git branch branch_name
# Create a new branch

git checkout branch_name
# Switch to the specified branch

git checkout main
# Switch to the main branch

git merge branch_name
# Merge the specified branch into main



🔄 2. Team workflow (step-by-step):

1️⃣	Clone the repo: git clone <repo-url>  
2️⃣	Create a new branch for your task: git checkout -b feature/login  
3️⃣	Work on your code, commit changes  
4️⃣	Push the branch: git push origin feature/login  
5️⃣	Create a Pull Request (PR) on GitHub   [Watch on YouTube: How to create the PR](https://youtu.be/nCKdihvneS0?si=6kY9BlNhbCX7lq_C)
6️⃣	Another team member reviews, gives feedback, and merges your PR  
✅	After merge, you pull the latest main again to stay updated  
git checkout main  
git pull origin main  

