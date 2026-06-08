# Basic Git Commands

### Setting up the User

First your need to setup a user account so that git knows that which
github user it is currently dealing with. For this, you need to give
your username and email to git using command line through following:

    git config --global user.name "YourGithubUsername"
    git config --global user.email "YourEmail" 

<br>

### Checking the User Status

Now that you are done with setup of your username and email, let's
verify if it has been setup properly using the following command:

    git config --list

<br>

### Making folder for a Local Repo
    mkdir YourRepoName

<br>

### Initializing a local Repository
    git init

<br>

### Connecting Local Repo to Remote Repo
    git remote add origin YourRemoteRepoURL

<br>

### Selecting a Branch of Repo
    git branch YourBranchName

<br>

### 