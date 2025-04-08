# Gitflow Simulation - Zendriix Project (PowerShell Output)

Windows PowerShell
Copyright (C) Microsoft Corporation. All rights reserved.

Install the latest PowerShell for new features and improvements! https://aka.ms/PSWindows

PS C:\Users\HP> # Pushing to GitHub
PS C:\Users\HP> cd "C:\Users\HP\Downloads\zendriix-release-gitflow"

# Initialize Git
PS C:\Users\HP\Downloads\zendriix-release-gitflow> git init
Initialized empty Git repository in C:/Users/HP/Downloads/zendriix-release-gitflow/.git/

# Add remote
PS C:\Users\HP\Downloads\zendriix-release-gitflow> git remote add origin https://github.com/Mamatayadav1/zendriix-release-gitflow.git

# Stage all files
PS C:\Users\HP\Downloads\zendriix-release-gitflow> git add .
warning: in the working copy of 'zendriix-release-gitflow/README.md', LF will be replaced by CRLF the next time Git touches it

# Commit files
PS C:\Users\HP\Downloads\zendriix-release-gitflow> git commit -m "Initial commit: Gitflow simulation for Zendriix release"
[master (root-commit) 7c44f64] Initial commit: Gitflow simulation for Zendriix release
 6 files changed, 15 insertions(+)
 create mode 100644 zendriix-release-gitflow/README.md
 create mode 100644 zendriix-release-gitflow/develop/app.py
 create mode 100644 zendriix-release-gitflow/feature/login-feature/login.py
 create mode 100644 zendriix-release-gitflow/hotfix/fix-login/login_fix.py
 create mode 100644 zendriix-release-gitflow/main/app.py
 create mode 100644 zendriix-release-gitflow/release/2025-04/app.py

# Rename branch to main and push
PS C:\Users\HP\Downloads\zendriix-release-gitflow> git branch -M main
PS C:\Users\HP\Downloads\zendriix-release-gitflow> git push -u origin main
Enumerating objects: 17, done.
Counting objects: 100% (17/17), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (17/17), 1.32 KiB | 96.00 KiB/s, done.
To https://github.com/Mamatayadav1/zendriix-release-gitflow.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

# Create and push develop branch
PS C:\Users\HP\Downloads\zendriix-release-gitflow> git checkout -b develop
Switched to a new branch 'develop'
PS C:\Users\HP\Downloads\zendriix-release-gitflow> git push -u origin develop
To https://github.com/Mamatayadav1/zendriix-release-gitflow.git
 * [new branch]      develop -> develop
branch 'develop' set up to track 'origin/develop'.

# Create and push feature branch
PS C:\Users\HP\Downloads\zendriix-release-gitflow> git checkout -b feature/login-feature
Switched to a new branch 'feature/login-feature'
PS C:\Users\HP\Downloads\zendriix-release-gitflow> git push -u origin feature/login-feature
To https://github.com/Mamatayadav1/zendriix-release-gitflow.git
 * [new branch]      feature/login-feature -> feature/login-feature
branch 'feature/login-feature' set up to track 'origin/feature/login-feature'.

# Create and push release branch
PS C:\Users\HP\Downloads\zendriix-release-gitflow> git checkout -b release/2025-04
Switched to a new branch 'release/2025-04'
PS C:\Users\HP\Downloads\zendriix-release-gitflow> git push -u origin release/2025-04
To https://github.com/Mamatayadav1/zendriix-release-gitflow.git
 * [new branch]      release/2025-04 -> release/2025-04
branch 'release/2025-04' set up to track 'origin/release/2025-04'.

# Create and push hotfix branch
PS C:\Users\HP\Downloads\zendriix-release-gitflow> git checkout -b hotfix/fix-login
Switched to a new branch 'hotfix/fix-login'
PS C:\Users\HP\Downloads\zendriix-release-gitflow> git push -u origin hotfix/fix-login
To https://github.com/Mamatayadav1/zendriix-release-gitflow.git
 * [new branch]      hotfix/fix-login -> hotfix/fix-login
branch 'hotfix/fix-login' set up to track 'origin/hotfix/fix-login'.
