# java-dsa-tutorial
## Fork and Pull Requests

1. Go to original github repo and fork it.
2. Clone the repo which is now copied to your github account
3. *use this command* git fetch upstream 'link of the original repo' *to sync your fork*
4. Make changes and push it to your remote repo
5. Create a pull request

## git log
*this command is used to see the entries

## git reset commit id
*this is used to reset the all the commits after the specific commit id

## git push --force 
Do this when your repo is only used by you (if other people are using your repo it can lead to fatal errors)

## Head branch
*currently active or checked out branch*
git checkout review -> Head branch will change to review

## git checkout vs switch
### git checkout
As Dan Fabulich notes, git checkout does three things:
1. switch branches
2. copy files from the stage to the working tree
3. copy files from a tree-ish to the working tree


### git switch
If you have to switch branches, use the git switch command instead of git checkout. Why? Because it was created for this specific task.


## git branch -m nameOfTheBranch
*to rename a branch*


