# 🚀 Git Commands Cheat Sheet

## 🔹 Setup & Configuration
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
git config --list

## 🔹 Creating a Repository
git init
git clone <repo-url>

## 🔹 Basic Workflow
git status
git add <file>
git add .
git commit -m "Your commit message"
git log

## 🔹 Branching
git branch
git branch <branch-name>
git checkout <branch-name>
git checkout -b <branch-name>
git merge <branch-name>

## 🔹 Remote Repositories
git remote add origin <repo-url>
git remote -v
git push origin main
git pull origin main
git fetch

## 🔹 Undoing Changes
git restore <file>
git reset <file>
git reset --hard   # ⚠️ Deletes all local changes
git revert <commit-id>

## 🔹 Stashing
git stash
git stash pop
git stash list

## 🔹 Tags
git tag
git tag v1.0
git push origin v1.0

## 🔹 Helpful Extras
git diff
git show <commit-id>
git rm <file>
git mv <old-name> <new-name>
