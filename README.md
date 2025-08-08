
## TASK-4-Version-Controlled-DevOps-Project-with-Git

## Description
This project demonstrates Git best practices including branching, merging, pull requests, tags, and documentation.

## Git
Git is a distributed version control system used to track changes in source code during software development. It helps teams collaborate, manage code versions, and keep a history of every change made to a project.
Git can tracks the every changes from work directory to remote repository. 
1. Working directory 
2. Stagging area  
3. Local repository 
4. Remote repository

## Git connection:
SSH keypair
HTTPS
PAT

## GIT WORKFLOW COMMON CMDS
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
git config --list
mkdir folder_name
cd folder_name
git init
git add .
git commit -m "commits"
git log --oneline
git remote add origin <repository URL>
git push origin master
git branch
git checkout <branch_name>
git checkout -b <branch_name>
git rm --cached <filename>
.gitignore
git status
git remote -v
git pull origin master
git merge <branch_name>

## Tag
git tag -a v1.0 -m "First stable version"
git push origin v1.0

## ## Branch Strategy
main → Stable production code
dev → Development integration
feature → New features

## Features
- Proper Git branching
- Pull request workflow
- Git tagging for releases
- Markdown documentation
