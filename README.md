# git-help
---
# Git
* version control system
* tracking code changes, who made changes
* collaboration
---
# GitHub
* web-based (repositories)
* store, manage, collaborate (cloud)
---
# Concepts
Repository: A folder where Git tracks your project and its history
Clone: Make a copy of a remote repository on your computer
Stage: Tell Git which changes you what to save next (add)
Commit: Save a snapshot of your staged changes
Merge: Combine changes from different branches
Pull: Get the latest changes from a remote repository
Push: Send your changes to a remote repository

repository link = origin

# Configure
git config --global user.name [username]
git config --global user.email [email]
git config --list

# GitHub to local repository
git clone [repository link]
git add .
git commit -m "text message"
git pull
git status

# Local repository to GitHub
# Sane name repository, local folder
git init
git add .
git commit -m "text message"
git branch -a
git branch -M main (or) git branch new_branch
git checkout main
git remote add origin [repository link]
git push -u origin main

u - changes files only upload
