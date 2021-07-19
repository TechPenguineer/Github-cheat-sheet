**ALL OF THIS DOCUMENT IS REFFERENCED FROM OTHER DOCUMENTS**
# Snapshots
`
git status
` Show modified files in working directory

` git add {FILE} .` Add a file as it looks now to your next commit

` git reset {FILE} .` Unstage a file while retaining the changes in working directory

` git diff` Check what is changed but not staged

` git diff --staged` Check what is staged but not yet commited

` git commit -m {COMMIT NAME}` Commit your staged content as a new commit snapshot

# Setup 
`git config --global user.name {firstname/lastname}` Set a name that is identifiable when reviewed version history

`git config --global user.email {email}` Set an email address that will be associated with each history marker

`git config --global color.ui auto` Set automatic command line coloring for Git for easy reviewing

# Branches & Merging

`git branch` Get a list of all the branches

`git branch {BRANCH NAME}` Creates a new branch when a new commit is  made

`git checkout` Switch to a new branch

`git merge {branch}` Mege the current branch with the specified one

`git log` Get a log of all commits under that branch

# Setup & Init
`git init` Initialize an existing directory as a Git repository

`git clone {GIT HTTPS}` Retrieve an entire repository from a hosted location via URL

# Inspect & Compare

`git log` Show the commit history for the currently active branch

`git log branchB..branchA` Show the commits on branchA that are not on branchB

`git log --follow {file}` Show the commits that changed file, even across renames

`git diff branchB...branchA` Show the diff of what is in branchA that is not in branchB

`git show {SHA}` Show any object in Git in human-readable format

# Share & Update

`git remote add {alias} {url}` Add a git URL as an alias

`git fetch {alias}` Fetch down all the branches from that Git remote

`git merge {alias}/{branch}` Merge a remote branch into your current branch to bring it up to date

`git push {alias} {branch} ` Transmit local branch commits to the remote repository branch

`git pull` Fetch and merge any commits from the tracking remote branch

