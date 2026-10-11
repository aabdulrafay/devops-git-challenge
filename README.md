
# DevOps Git Challenge

Practical Version Control Workflow Verification Challenge

**Student Name:** Abdul Rafay
**SAP ID:** 54689
**Section:** SE 7-1
**University:** Riphah International University, Islamabad

---

## Project Description

This repository demonstrates a complete Git and GitHub workflow. It covers repository setup, branching, stashing, merge conflict resolution, and Pull Requests.

## Repository Contents

| File | Description |
|------|-------------|
| deploy.sh | Sample deployment script used for the branching and merge exercises |
| README.md | Project documentation (this file) |
| PROOF_OF_WORK.md | Git log output and answers to the reflection questions |

## Branches

| Branch | Purpose |
|--------|---------|
| main | Stable branch containing the final merged work |
| development | Branch where the script was updated and the merge conflict was resolved |
| staging | Branch created from main to simulate a conflicting change |

## Tasks Completed

1. **Global Setup and Repository Initialization:** Configured Git credentials, created the public repository, and cloned it locally.
2. **Local Architecture and Initial Commits:** Created deploy.sh and README.md, then committed and pushed them to main.
3. **Context Switching with Stashing:** Edited the script on the development branch, stashed the changes, switched branches, and restored them using git stash pop.
4. **Merge Conflict Resolution:** Edited the same line on the staging and development branches, merged them, and resolved the conflict manually.
5. **Pull Request Workflow:** Pushed all branches and merged a Pull Request from development into main on GitHub.
6. **Verification Artifact:** Added PROOF_OF_WORK.md containing the commit history and reflection answers.

## Commit History

    4a5fa4b Merge pull request #1 from aabdulrafay/development
    b4e7bea fix: resolved merge conflict
    ad1d845 fix: staging label
    9732de9 feat: updated script with staging env
    af198a7 feat: initial commit with deploy script

## Key Commands Used

    git config --global user.name "Abdul Rafay"
    git clone <repository-url>
    git add .
    git commit -m "message"
    git push origin main
    git checkout -b development
    git stash
    git stash pop
    git merge staging
    git pull origin main
    git log --oneline

## Submission

Repository URL: https://github.com/aabdulrafay/devops-git-challenge

