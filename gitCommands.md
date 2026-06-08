# Git Commands - Organized by Difficulty Level

---

# Basic Git Commands
*For beginners just starting with Git and version control*

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

### Check current branch
    git branch

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

### Pull Contents of Remote's Branch to Local's Branch
    git pull origin TargetBranchName

### Cloning Someone's Repo
    git clone TargetRepoURL

---

# Intermediate Git Commands
*For users comfortable with basic Git who want to work with branches and history*

### Rename Current Local Repo Branch
    git branch -M NewBranchName

### Delete a Branch
    git branch -d TargetBranchName

### Compare Current Branch to Another Branch
    git diff TargetBranchName

### Merge Another Branch with Current Branch
    git merge TargetBranchName

### Abort a merge
    git merge --abort

### Undo Added Changes in specific file
    git reset TargetFileName

### Undo Added Changes in all Added files
    git reset

### Undo Last Commit
    git reset HEAD~1

### View Commit Logs
    git log

---

# Advanced Git Commands
*For experienced users handling complex workflows and history management*

### Undo Multiple Commits (keep changes)
    git reset TargetCommitHash

### Undo Multiple Commits & Discard Code
    git reset --hard TargetCommitHash

### Undo Commits & Keep Changes Staged
    git reset --soft TargetCommitHash

### Revert a Commit (creates new commit, safer for shared branches)
    git revert TargetCommitHash

### Rebase Current Branch onto Another Branch
    git rebase TargetBranchName

### View Detailed Commit History with Graph
    git log --oneline --graph --all

### Stash Current Changes (save temporarily)
    git stash

### Apply Stashed Changes
    git stash pop

### Cherry-pick a Specific Commit
    git cherry-pick TargetCommitHash

### Interactive Rebase (squash, reorder, edit commits)
    git rebase -i TargetCommitHash

---