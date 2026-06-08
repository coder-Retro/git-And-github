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

### Name your current Local Repo Branch as main
    git branch -M main

### Pulling Contents of Remote's Branch
    git pull origin TargetBranchName

### Creating & Switching a Branch in Local Repo
    git switch -c NewBranchName

### Switching Branch within Local Repo
    git switch TargetBranchName

### Check Status of Changes Made in files
    git status

### Add & Commit a file to start push process
    git add TargetFileName
    git commit -m "AnyCommitMessage"

### Push file from Local Repo to Remote Repo
    git push origin TargetBranchName

---
# Intermediate Git Commands