-Notes for Terminal!

- ls is to list
- cd space ___ is to change direction
- pwd is to bring u to primary users files
- cd with nothing after will bring u to starting user
- code space . will bring u to code app that youve made
- to go backwards: cd .. for one level, cd ... for 2 levels and so on
- mkdir space ___ to make directory (make new file) (- if u want to make multiple words, no spaces)
- go to where u want to go before opening vs code unless u want a fried pc 
- ol 5 li for multiples lists


## Reading 3 Seeing your remote

- *git stash* command to hide a part but not lose it, *git stash apply* to unhide it
- *git remote* to view all short names of remote handlers
- *git remote -v* to view their urls
- *git remote add "shortname" space url* to create to repository with shortname
- dont understand fetching, ask! *git fetch [remote-name]*
- *git push [remote-name][branch-name]* for pushing
- *git remote rename old shortname then new shortname* (ex: js jn) to rename short name
- *git remote rm "shortname"* to remove shortname
- Dont understand commit changes, ASK! *git commit --amend* 
- *git revert "HEAD"* to undo changes on new commit
- *git checkout -- name* to to have a file return to previous state
- *git branch test* to create new branch towards your most recent commmit and wont switch you over to the new branch
- *git checkout* to switch to another branch
- *git checkout -b test2* to create new branch and switch to it
- *git branch* to list all branches
-  *git checkout master* and then *git merge test* to seitch to master nad merge changes from tests to master
- Ask about fast forward and three way merge confused
- *git pull* to fetch and merge changes
- *git branch -d test* to delete a branch
- *git status to veiw unmerged files*
- *git branch -v* to view latest commits
- *git branch --merged* to see if they have been merged
- *git branch --no-merged* to see which havent
- *git checkout test* then seperately *git rebase master* to rebase 
- *git log* to view committed cnapshots and this can be filtered in many ways, research if need
- *git tag* with info after to flag certain points as important
- Annotated tag is very important, Lightweight is a pointer
- *git checkout -b "[branchname][tagname]"* to create new branch with tag
- *git config --"global alias.br branch"* to set up aliases
- once tracked with git its considered a repository
- 


# class 3 lecture

- *code .* should bring up vs code

## VS Code changes

- Auto Save feature on!
- THe Dot at the top means that there are changes you have not saved
- Must save files before sending to github!!!!!
- *git status* will tell you what changes it can see, it will be red
- *git add exact name of file(s)* (ACP) add, commit, publish? (exact name) then git status to see the difference should turn green
- git commit -m "" to make a copy the -m is a flag and the quotes are the mssage must be double quotes(ex: updated read.me)
- always check status 
- origin/main means computer version is ahead of github
-  *git push origin main* should say up to date with branch main now
- make the rest of the changes in vs code once set up, changes on github wont be tracked for computer
- ACP IS VERY IMPORTANT, MUST FOLLOW PROCESS
- *git add .* will add all changes, then git commit -m "__" as before, git push origin main
- case sensitive
-  push up to github and pull down to local computer
- local is computer, remoteis github
-git pull origin main     git config pull.rebase false then the one before to merge w/ github
- No punctuation in commit messages !!!!!!!


