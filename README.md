# practice

git init
git log  // view history of the repository commit log
git show  / view the changes made in the commit
git remote add origin """"""
git pull  // is combination of git fetch and git merge
git fetch - downloads changes from the remote repository into a separate branch, good way to review changes
git merge - 
git checkout remotes/origin/master
git branch -r - view list of all remote
git checkout . - clears changes in the directory
git reset - takes files back from staging area to working directory
git reset --hard - combines git reset and git checkout
git reset --hard HEAD will clear state back to last commit
git revert - allows you to undo the commits
  - type the command :wq to save the commit message and quit vim 
git reset HEAD~1 will also allow you to undo commits
git revert HEAD...HEAD~2 - to revert the commits between HEAD and HEAD~2.


// Fixing Merge Conflicts
git merge remotes/origin/master
git checkout --ours staging.txt     or 
git checkout --theirs staging.txt
git add staging.txt
git commit --no-edit
git pull --no-edit origin master

git rebase
git pull --rebase    // will act as if you had done a pull request before each of your commits

// Experiment using branches
git branch   // will list all branches
git branch -a   // will include remote branches
git branch -v   // will include HEAD commit message for the branch
git branch -va   //  list all branches with their last commit message

git checkout master
git merge new_branch
git push <remote_name> <branch_name>   // push a branch to a remote
git branch -d <branch_name>   // delete branch



images wont be static. will be dynamic

