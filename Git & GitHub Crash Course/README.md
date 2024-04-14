# Git & GitHub Crash Course

### 1. What is Version control System
Version control, also known as source control, is tracking and managing software code changes.

Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later

Famous VCS:

-  Git (Most Famous)
- Apache SubVersion
- Piper (Used by Google)


### 2. Introduction to Git VCS
- What is Git?
- Installation of Git CLI
- Git Basic Concept (working)
- Basic Git Commands
    - Setting up Git Global Configuration
        - To check `git config --global user.name ` 
        - To Set  `git config --global user.name “[firstname lastname]”` 
        - To check `git config --global user.email` 
        - To Set.    `git config --global user.email “[valid-email]”` 
        - To Check `git config --global color.ui` 
        - To set `git config --global color.ui false` 


### 3. Version Controlling with Git
- Initializing Git Project
    - `git init` 
- Adding Files to VCS
    - `git add <FILE PATH>` 
    - `git add .` 
- Removing Files from VCS
    - `git rm <FILE PATH>` 
- Introduction to Commits
    - Working Area
        - `git status` 
        - `git diff` 
        - `git blame <FILE PATH>` 
    - Staging Area
        - `git stash` 
        - `git stash list` 
        - `git stash pop` 
        - `git stash drop` 
    - Committing Files
        - `git commit -m "MESSAGE"` 
    - Logging Commit History
        - `git log` 
        - `git log --oneline` 
        - `git log --stat` 
    - Reverting Back
        - `git reset --hard <SHA>` 
        - `git revert <SHA>` 
    - Show git commit
        - `git show <SHA>` 


### 4. Git VS GitHub
- What are Git and GitServer
- Popular Git Servers
    - GitHub
    - GitLab
    - BitBucket
- Git Remotes
    - `git remote add origin <REMOTE REPO URL>` 
- Pushing and Pulling in Git
    - `git push -u origin master` 
    - `git fetch` 
    - `git pull`
 
### 5. Branching in Git
- Introduction to Branching Concept.
- Creating Branches
    - `git branch <BRANCH NAME>` 
    - `git checkout <BR_NAME>` 
    - `git checkout -b "BR_NAME"` 
- Pushing branch code
    - `git push --set-upstream origin feat-a` 
    - `git push -u origin feat-b` 
- Branch Tags
    - FEAT-A
    - FEAT-B
- Merging Branches
    - Merge
    - Rebase



