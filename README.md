# Git-commands

Commonly used GitHub commands:

## SETUP
* **git init**
Initialise an existing directory as a Git repository 
* **git clone [url]**
Retrieve an entire repository from a hosted location via URL

## STAGE & SNAPSHOT
* **git add [file] / git add .**
add a file as it looks now to your next commit (stage) 
* **git status **
show modified files in working directory, staged for your next commit 
* **git reset [file] / git reset**
unstage a file while retaining the changes in working directory
* **git reset —soft HEAD.~1**
Ignore last commit changes, but will retain in the local
* **git reset —hard HEAD.~1**
Ignore last commit changes and will delete in the local
* **git commit -m “[descriptive message]” **
commit your staged content as a new commit snapshot

## BRANCH & MERGE
* **git branch **
list your branches. a * will appear next to the currently active branch 
* **git branch [branch-name] **
create a new branch at the current commit 
* **git checkout **
switch to another branch and check it out into your working directory 
* **git merge [branch] **
merge the specified branch’s history into the current one
When merge conflicts araise, modify and commit the changes

## TRACKING PATH CHANGES
* **git rm [file] **
delete the file from project and stage the removal for commit
* **git rm —cached [file]**
delete the cached file from project and stage the removal for commit

## SHARE & UPDATE
* **git fetch [alias] **
fetch down all the branches from that Git remote 
* **git merge [alias]/[branch]** 
merge a remote branch into your current branch to bring it up to date 
* **git push [alias] [branch] **
Transmit local branch commits to the remote repository branch 
* **git pull **
fetch and merge any commits from the tracking remote branch

## TEMPORARY COMMITS 
* **git stash **
Save modified and staged changes
When we move from one branch to another to save changes temporarily 
