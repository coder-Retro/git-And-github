# Basic Git Commands

### Setting up the User

First your need to setup a user account so that git knows that which
github user it is currently dealing with. For this, you need to give
your username and email to git using command line through following:

    git config --global user.name "YourGithubUsername"
    git config --global user.email "YourEmail" 

### Checking the User Status

Now that you are done with setup of your username and email, let's
verify if it has been setup properly using the following command:

    git config --list

### Making folder for a Local Repo
    mkdir YourRepoName

### Initializing a local Repository
    git init

### Connecting Local Repo to Remote Repo
    git remote add origin YourRemoteRepoURL

### Selecting a Branch of Repo
    git branch YourBranchName