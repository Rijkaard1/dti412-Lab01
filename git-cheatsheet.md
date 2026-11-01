# Git Command Cheat Sheet

A quick reference of the Git commands I learned in DTI412 Lab 01.

## Setup

### Check Git Version
```
git --version
```
Purpose: Check the installed Git version.

---

### Configure Username
```
git config --global user.name "Paing Htoo Kyaw"
```
Purpose: Set your Git username.

---

### Configure Email
```
git config --global user.email "your@email.com"
```
Purpose: Set your Git email address.

---

### Display Configuration
```
git config --list
```
Purpose: Show Git configuration information.

---

## Working with Repositories

### Clone Repository
```
git clone repository-url
```
Purpose: Download a GitHub repository.

---

### Check Status
```
git status
```
Purpose: Display file status.

---

### Add Files
```
git add .
```
Purpose: Add all modified files to staging.

---

### Commit Changes
```
git commit -m "message"
```
Purpose: Save changes locally.

---

### Upload to GitHub
```
git push
```
Purpose: Upload local commits to GitHub.

---

### Download Updates
```
git pull
```
Purpose: Download changes from GitHub.

---

### View Commit History
```
git log --oneline
```
Purpose: Display project history.

---

## Branching

### Create Branch
```
git branch branch-name
```
Purpose: Create a new branch.

---

### Switch Branch
```
git checkout branch-name
```
Purpose: Change to another branch.

---

### Merge Branch
```
git merge branch-name
```
Purpose: Merge another branch into current branch.

---

## Extras

### Add a Specific File
```
git add filename
```
Purpose: Stage only one file instead of everything.

---

### Show Current Branch
```
git branch
```
Purpose: List branches and mark the one you are on.

---

### Undo Staging
```
git restore --staged filename
```
Purpose: Remove a file from staging without losing changes.