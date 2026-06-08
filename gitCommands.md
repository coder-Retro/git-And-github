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

### Selecting Main Branch in Local Repo
    git branch -M main

### Pulling Contents of Remote's main to Local's main
    git pull origin main

### Creating & Selecting a Branch in Local Repo
    git switch -c YourBranchName

### Changing Branch within Local Repo
    git branch BranchName

### Add & Commit a file to start push process
    git add YourFileName
    git commit -m "AnyCommitMessage"

### Push file from Local Repo to Remote Repo
    git push origin YourBranchName