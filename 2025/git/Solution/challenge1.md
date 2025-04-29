# ✅ Week 4: Git and GitHub Challenge – Solution

This document covers all the steps, commands, and explanations followed as part of the 90DaysOfDevOps – Week 4 Challenge.

## 📁 Directory Structure
```bash
90DaysOfDevOps/
└── 2025/
    └── git/
        └── 01_Git_and_Github_Basics/
            └── week-4-challenge/
                ├── info.txt
                └── solution.md
```
## 🛠️ Git Commands Used
### 🔹 Task 1: Fork and Clone the Repository
```bash
# Forked the repository from GitHub
# Cloned the forked repository
git clone https://github.com/<your-username>/90DaysOfDevOps.git

cd 90DaysOfDevOps/2025/git/01_Git_and_Github_Basics
```
### 🔹 Task 2: Initialize a Local Repository and Create a File
```bash
# Created a challenge folder
mkdir week-4-challenge
cd week-4-challenge

# Initialized git repo
git init

# Created file
echo "Hi, I’m <Your Name>. I’m learning DevOps!" > info.txt

# Added and committed the file
git add info.txt
git commit -m "Initial commit: Add info.txt with introductory content"
```
### 🔹 Task 3: Configure Remote URL with PAT and Push/Pull
```bash
# Set remote using PAT (example placeholder used below)
git remote add origin https://<your-username>:<your-PAT>@github.com/<your-username>/90DaysOfDevOps.git

# If origin already exists
git remote set-url origin https://<your-username>:<your-PAT>@github.com/<your-username>/90DaysOfDevOps.git

# Push changes
git branch -M main
git push -u origin main

# Optional pull
git pull origin main
```
### 🔹 Task 4: Explore Your Commit History
```bash
# View commit history
git log
```
Example Output: (in Sql)
---
commit 123abc456def...

Author: Your Name <your@email.com>

Date:   2025-04-19

     Initial commit: Add info.txt with introductory content
---

### 🔹 Task 5: Advanced Branching and Switching
```bash
# Create new branch
git branch feature-update

# Switch to branch
git switch feature-update
# or
git checkout feature-update

# Edit info.txt and save new content
echo "This is an update with more details about my learning journey." >> info.txt

# Stage and commit changes
git add info.txt
git commit -m "Feature update: Enhance info.txt with additional details"

# Push to remote
git push origin feature-update
Then, opened a Pull Request on GitHub to merge feature-update to main.
```
## 🔹 (Optional) Merge Conflict Simulation
```bash
# From main branch, create a conflicting branch
git switch main
git branch experimental
git switch experimental

# Make a conflicting change
echo "Conflicting line from experimental" >> info.txt
git add info.txt
git commit -m "Experimental: Add conflicting line"

# Switch back and merge
git switch feature-update
git merge experimental
If conflict occurred:

# Manually edited info.txt to resolve conflict
git add info.txt
git commit -m "Resolve merge conflict between feature-update and experimental"
```
## ✍️ Why Branching Strategies Matter in Collaborative Development
---
Branching strategies are essential in software development, especially in collaborative environments. Here's why:

1. Isolating Features and Bug Fixes:
Different branches let teams work on multiple features or fixes without interfering with each other.

2. Parallel Development:
Developers can simultaneously work on various tasks (e.g., features, testing, documentation) in separate branches.

3. Reducing Merge Conflicts:
Structured workflows (like Git Flow or GitHub Flow) prevent chaos and minimize the likelihood of frequent merge conflicts.

4. Enabling Code Reviews and CI/CD:
Code in feature branches can be reviewed and tested before being merged into the main branch, maintaining stability.

Popular branching strategies include:

- Feature Branching

- GitHub Flow

- Git Flow

- Trunk-Based Development
---
## 🎁 Bonus Task: SSH Authentication
```bash
# Generate SSH key
ssh-keygen -t ed25519 -C "your@email.com"

# Added public key (~/.ssh/id_ed25519.pub) to GitHub SSH settings

# Change remote to use SSH
git remote set-url origin git@github.com:<your-username>/90DaysOfDevOps.git
```
### Push using SSH
```bash
git push origin feature-update
```
### 🔚 Summary

| Task Number | Description               | Status |
|-------------|---------------------------|--------|
| Task 1      | Fork & Clone              | ✅     |
| Task 2      | Init Repo & Commit        | ✅     |
| Task 3      | PAT Setup & Push          | ✅     |
| Task 4      | Git Log                   | ✅     |
| Task 5      | Branching & PR            | ✅     |
| Task 6      | Documenting + Explanation | ✅     |
| Bonus       | SSH Authentication        | ✅     |
