
git init .
git add <file name> 
git commit -m "Commit information"
git status 
git log 
git remote add "remote_repo"  // add remote repo to local system
git clone <remote_repo>  // clone repo into local system
git pull origin master
git push origin master 
git checkout -- 
git checkout -- . 
git restore <file_name> 
git restore . 
git checkout <branch_name>
git checkout <commit_id> file // to get a file from previous commit  
git annotate <file-name>
git branch --set-upstream-to=origin/master master
git reset HEAD~N (N is number of commits to revert) //revert commits on local repository
git checkout <branch_name>
git checkout HEAD~1

git rebase -i HEAD~N (N is number of commits to squash) // to combain multiple comments as a single. 
git config --global user.name "USERNAME"
git config --global user.email "USERNAME@EMAIL.COM"
git commit -m "COMMIT_ID"
git push origin master
git remote add origin "GITHUB_REPO_URL"
git add "<filename>" / git add . 
git commit -m "<commit info>"
git push origin <branch>
git checkout -- <filename> // to revert changes from git working directory area
git reset HEAD <filename> //unstage a file 
git checkout <commit_id> <filename> // move to previous commit 
git reset HEAD . //unstage all changes 
git checkout -- . 
git show <commit-id> 
git show HEAD
git show HEAD~1
git annotate <filename>
git branch --set-upstream-to=origin/master master
git branch <branch_name> // to create a new branch
git checkout -b <branch_name> // to create new branch and switch to branch 
git merge <source_branch> <dest_branch> 
git branch -d <branch_name> // to delete a branch