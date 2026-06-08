# Basic Git Commands

### Setting up the User
<pre>
First, you need to setup a user account so that git knows that which
github user it is currently dealing with. For this, you need to give
your username and email to git using command line through following:
</pre>
    git config --global user.name "YourGithubUsername"
    git config --global user.email "YourEmail" 
<br>

### Checking the User Status
<pre>
Now that you are done with setup of your username and email, let's
verify if it has been setup properly using the following command:
</pre>
    git config --list
<br>

### Making folder for a Local Repo
<pre>
Since we have verified our user setup status now, we are ready to
make our local repository. For this, we need to make a folder on
our system first using the following commands: (Not Git Commands)
</pre>
    mkdir YourRepoName
<br>

### Initializing a local Repository
<pre>
Now that our folder is ready, let's enter it and initialize our
local repository so get started with git properly. Run the first
command to enter the folder and then second one to initialize a
local repository in that folder:
</pre>
    cd YourRepoName
    git init
<br>

### Connecting Local Repo to Remote Repo
<pre>

</pre>
    git remote add origin YourRemoteRepoURL
<br>

### Selecting a Branch of Repo
    git branch YourBranchName
<br>

### 
<pre>

</pre>