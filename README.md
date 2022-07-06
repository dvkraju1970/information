# information

gitbash commands

1)git branch <NewBranch>    (create new local branch)  
2)git push -u origin <NewBranch>    (pushes the newly created "NewBranch"(which is not there in git repo) to remote origin)  
3)git fetch origin <NewBranch>   (It pulls the NeBranch(which is not present in local) from origin to local)  
4)git checkout <Branch>    (switch to MynewBranch)  
5)git pull  (pulls the files from origin to local, if there are any extra files added in git repo that needs to be updated in local)  
6)git push  (pushes the commits to the origin)
7)git status (shows what are the staged and unstaged files if any otherwise it shows the commits added)
8)git restore <Branch>   (restores the uncommited changes)  
9)git add <fileName> (will add the file to the staging environment)
10)git add .  (it will add all the files from unstaged to staging environment)
11)git commit -m "commit message" (To commit the staged files with a message)
12)git remote -v  (shows the origins details from which git location you are fetching and pushing the code)  
13)git branch  
14)git branch -a  (or)  -r    ("-a" gives the list of both local and remote branches, "-r" gives only remote branches)
15)git branch -d <Branch> (deletes the branch in local)    
16)git revert <commitId>  (to revert back the commit)
17)git revert <commitId> -m <1 or 2>  (when it is a merge commit, we can revert and comeback to the specific commit mentioned)
18)git log  (will display the list of commits)
19)git reset --soft HEAD~2  (it will reset the last two commits of the specified branch)
20)git push origin +<branchName> --force  (It will push the reseted(deleted) commits to the origin)

git switch <Branch>  ===== git checkout <Branch>  (both do the same work of moving to different branch)--- need to know the difference   
