# PROOF OF WORK

Student Name: Abdul Rafay
SAP ID: 54689
Section: SE 7-1
Repository: devops-git-challenge

## 1. Git Log Output

Command executed: git log --oneline

4a5fa4b (HEAD -> main, origin/main) Merge pull request #1 from aabdulrafay/development
b4e7bea (origin/development, development) fix: resolved merge conflict
ad1d845 (origin/staging, staging) fix: staging label
9732de9 feat: updated script with staging env
af198a7 feat: initial commit with deploy script

## 2. Reflection Questions

### Q1: What is the difference between Git and GitHub?

Git is a version control tool that is installed on a local computer and tracks changes made to files over time. It works offline and stores the complete history of a project inside a hidden .git folder. GitHub, on the other hand, is a cloud-based platform that hosts Git repositories online. It adds collaboration features such as Pull Requests, issue tracking, code review, and access control. In short, Git is the tool that tracks changes, while GitHub is the service that stores and shares those repositories.

### Q2: Explain the three architecture stages: Working Directory, Staging Area, and Local Repository.

The Working Directory is the folder on the computer where files are created and edited; changes here are not yet tracked for saving. The Staging Area (also called the Index) is an intermediate zone where selected changes are placed using git add, in preparation for the next commit. The Local Repository is where Git permanently stores committed snapshots of the project, created using git commit. A file therefore moves from the Working Directory, to the Staging Area, and finally into the Local Repository.

### Q3: What is the difference between git stash pop and git stash apply?

Both commands restore the most recently stashed changes into the working directory. The difference is that git stash pop restores the changes and then removes that entry from the stash list. In contrast, git stash apply restores the changes but keeps the entry in the stash list. Therefore, git stash apply is useful when the same changes need to be applied to multiple branches, while git stash pop is preferred when the stash is no longer needed.

### Q4: What is the difference between git fetch and git pull?

The git fetch command downloads the latest commits and branch information from the remote repository but does not change the working directory or the current branch. This allows the developer to review the incoming changes before integrating them. The git pull command performs a git fetch followed immediately by a merge into the current branch. As a result, git fetch is the safer option, while git pull is quicker but may trigger merge conflicts automatically.
