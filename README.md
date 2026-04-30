# 🚀 Git Commands Cheat Sheet

A quick reference guide for commonly used Git commands.

---

## 🔧 Setup & Configuration
```bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
git config --list


git init
git clone <repo-url>


git status
git add <file>
git add .
git commit -m "Your commit message"
git log


git branch
git branch <branch-name>
git checkout <branch-name>
git checkout -b <branch-name>
git merge <branch-name>

git remote add origin <repo-url>
git remote -v
git push origin main
git pull origin main
git fetch

git restore <file>
git reset <file>
git reset --hard   # ⚠️ Deletes all local changes
git revert <commit-id>


git stash
git stash pop
git stash list

git tag
git tag v1.0
git push origin v1.0


git diff
git show <commit-id>
git rm <file>
git mv <old-name> <new-name>
