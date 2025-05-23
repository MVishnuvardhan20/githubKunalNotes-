*The History of the entire Protect & stored in the folder named. git which it provides by the git and it's a hidden folder.
* git init  is used to initialized empty. Git repository or folder.
* git status it is used to the see the unsaved or untracked files and they will Not appear in the git history
*) To see the history of the untracked files or unsaved file's use git add "filename" it will appear in green color if it's not saved it will appear in Red color and use the 
(git commit -m "file name" file added")  Modified, deleted
* If you don't want to save the history of a charge  the use git restore  -- stogged "file name”
* git log it is used to know details of  the file when it was added, modified, etc.
* If you want to remove a commit from the git log or history copy #code below the one you want to delete and use code git reset #code
* If you don't want make a commit/history and you don't want to delete them the you can use the code git stash. Before using this code you need to use git add .  to save the changes
* to bring back that files use git stash Pop they will  reappear but they will not be saved in history
* If you don’t want to bring them back and delete them then use git stash clear  .
* If you want to attach the Repository then copy the URL of the Repository and use code "git remote add origin "Paste the URL”
* if you want to see all the URL'S with are added to your folder then use git branch “branch name”
*if you have to push a commit by force then use push origin “branch name” -f
* to change all the commits from all the branches use git fetch --all –prune  . you need to be in main branch to use it prune  means the deleted commits will also be fetched 
* to reset the main branch of origin to the main branch of upstream use git reset –hard upstream/main after type git log you will have  the same commits as the upstream 
* to pull a commit from your upstream use git pull upstream main
* if you want to merge all the commits into one then copy the #code of a commit below then use this code “git rebase -i “paste the #code””

