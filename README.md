# Git-Learning
$ git init - to initialize git repositry.<br>
$ git status - to watch the status of files in repositry.<br>
$ git add . - puts files into staged area from working area.<br>
$ git log - to see the log of git commits.<br>
$ git checkout <commit id> - to go to specific commit in the repositry.<br>
$ git log --all - to see the log of all branches commits.<br>
$ git log --all --oneline - to see the log of all branches commits in oneline.<br>
$ git log --all --oneline --graph - to see the log of all branches commits in oneline and in graph.<br>
$ git branch --delete <branch name> - It deleates the given branch **NOTE** -(but execute code from different branch)<br>
$ git reset --hard <commit id> - It deletes all the  commits after it  and brings head to given commit id and remove the changes from local.<br> 
$ git reset --soft <commit id> - It deletes all the  commits after it  and brings head to given commit id and bring back changes to staged area(does not remove changes from local).<br>
$ git remote show origin  - shows that if you are connected to a remote repository or not.<br>
$ git commit -m "<commit message>" - It commits the staged area changes to the repository and generates a commit id.<br>
 
## Fast forward merge 
In this no commit is created only the pointer shifts to the current commit and the branch get updated with the latest commit branch code.<br>