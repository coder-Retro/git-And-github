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

### Selecting a Branch of Repo
    git branch YourBranchName

### Add & Commit a file to start push process
    git add YourFileName

### Push file from Local Repo to Remote Repo
    git push origin YourBranchName