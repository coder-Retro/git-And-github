# Basic Git Commands

### Checking git version
    git --version

### Setting up the User
    git config --global user.name "YourGithubUsername"
    git config --global user.email "YourEmail" 

### Checking the User Status
    git config --list

### Making folder for a Local Repo
    mkdir YourRepoName
    cd YourRepoName

### Initializing a Local Repo
    git init

### Connecting Local Repo to Remote Repo
    git remote add origin YourRemoteRepoURL

### Verify Remote
    git remote -v

### Rename Current Local Repo Branch
    git branch -M NewBranchName

### Check current branch
    git branch

### Creating & Switching a Branch in Local Repo
    git switch -c NewBranchName

### Switching Branch within Local Repo
    git switch TargetBranchName

### Delete a Branch
    git branch -d TargetBranchName

### Pull Contents of Remote's Branch to Local's Branch
    git pull origin TargetBranchName

### Check Status of Changes Made in files
    git status

### Add & Commit a file to start push process
    git add TargetFileName
    git commit -m "AnyCommitMessage"

### Push file from Local Repo to Remote Repo
    git push origin TargetBranchName

### Cloning Someone's Repo
    git clone TargetRepoURL

---
# Intermediate Git Commands

### Compare Current Branch to Another Branch
    git diff TargetBranchName

### Merge Another Branch with Current Branch
    git merge TargetBranchName

### Abort a merge
    git merge --abort