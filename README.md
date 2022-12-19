# git

Common Git Commands 

```
1) git add fileName                     // git starts tracking the changes and will move the file to staging 
2) git commit -m "Commit Msg"           // Commits the changes and moves the file to local repo from statging
3) git push origin branchName           // Pushes the changes to remote repository from local repository 
4) git pull                             // Pulls the changes from the remote repository
4) git checkout branchName              // Switches to the branch from the current branch 
5) git checkout -b branchName           // Creates and switches to the branch from the current branch 
6) git branch                           // Displays the current branch name    
7) git branch branchName                // Creates the branch 
8) git merge branchName                 // Does a git merge 
```

```Initialising Repository
git Init
```
```Staging Files
git add <file>                            //Stages a single file
git add <file1> <file2>                   //Stages Multiple files
git add *.sh                              //Stages all shell files
git add .                                 //Stages Current Directory
```
```Viewing the status
git status                              // full status
git status -S                           //Short Status
```Commiting the Staged Files
git commit -m "Message"                 //commits with a one line msg
git commit -am "Message"                 //skips the staging area
```
```Removing or moving files
