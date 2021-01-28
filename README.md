# Git Commands
### git config
#### Usage: git config –-global user.name “[name]”  
git config --global user.name "john"
#### Usage: git config –global user.email “[email address]”  
git config --global user.email "john@gmail.com"

### git clone
#### Usage: git clone [url]  
git clone https**.git

### git add
#### Usage: git add [file]  
git add filename
git add *  

### git commit
#### Usage: git commit -m “[ Type in the commit message]”  
git commit -m "First commit"

### git diff
#### Usage: git diff  
git diff
git diff –staged (differences between the files in the staging area and the latest version present)
#### Usage: git diff [first branch] [second branch]  
git diff branc_2 branch_3 (differences between the two branches mentioned)

### git reset 
#### Usage: git reset [file]  
git reset site.css (unstages the file, but preserves its contents)
#### Usage: git reset [commit]
git reset HEAD~1 (undoes all the commits after the specified commit and preserves the changes locally)
#### Usage: git reset –hard [commit]  
git reset --hard HEAD~1 (discards all history and goes back to the specified commit)

### git rm
#### Usage: git rm [file]
git rm example.txt (deletes the file from your working directory and stages the deletion)

### git log
#### Usage: git log  
git log (lists the version history for the current branch)
#### Usage: git log –follow[file]  
git log --follow project_1 (lists version history for a file, including the renaming of files also)

### git show
#### Usage: git show [commit]  
(shows the metadata and content changes of the specified commit)

### git branch
#### Usage: git branch  
(lists all the local branches in the current repository)
#### Usage: git branch [branch name]
git branch branch_1 (creates a new branch)
#### Usage: git branch -d [branch name]  
git branch -d branch_1 (deletes the branch)

### git checkout
#### Usage: git checkout [branch name]  
git checkout branch_2 (switch from one branch to another)
#### Usage: git checkout -b [branch name]  
git checkout -b branch_3 (creates a new branch and switches to it)

### git merge
#### Usage: git merge [branch name]  
git merge branch_2 (merges the specified branch’s history into the current branch)

### git remote
#### Usage: git remote add [variable name] [Remote Server Link]  
git remote add origin https**.git

### git push
#### Usage: git push [variable name] [branch name]
git push origin master (sends the branch commits to your remote repository)
#### Usage: git push -–all [variable name]
git push --all origin (pushes all branches to your remote repository)

### git pull
#### Usage: git pull [Repository Link]  
git pull https**.git
